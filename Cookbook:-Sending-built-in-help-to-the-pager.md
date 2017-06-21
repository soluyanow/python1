IPython's %pinfo (?) and %pinfo2 (??) interactive help commands
use the pager to avoid flooding the shell with long blocks of
text.

Here is a magic command to give the same behavior to Python's
built-in (pydoc) help command (tested in Python 2.7):

```
from IPython.core import page
from IPython.core.magic import register_line_magic

@register_line_magic('help')
def magic_help(s):
    """Retrieve the pydoc help for an object and display it through a pager.

    See http://stackoverflow.com/a/1176180/1410871
    """
    import pydoc
    import sys
    obj = reduce(getattr, s.split("."), sys.modules[__name__])
    page.page(pydoc.plain(pydoc.render_doc(obj)))
del magic_help
```

After running this code from the interactive prompt or via your
local config settings, you can send help through the pager like so:

```
import re
%help re
```