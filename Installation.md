# The easy way #

The easiest way to install PrettyTable is to use the "easy\_install" command which is part of Python setuputils.  From the command line, you can simply type

```
easy_install prettytable
```

and everything should just work.

You can upgrade an existing PrettyTable installation to a newer version by typing

```
easy_install -U prettytable
```

# The harder way #

If you can't use easy\_install for some reason, you can always do the installation manually.  Download the latest version of PrettyTable from the Downloads tab at this Google code project site.  Save the file as "prettytable.py" (not prettytable-x.y.py) in your Python installation's "site-packages" directory.  Depending on your operating system, this directory might be something like:

  * FreeBSD: `usr/local/lib/python2.5/site-packages/`
  * Linux: `/usr/lib/python2.5/site-packages/` (some distros will be more like Free/OpenBSD)
  * NetBSD: `/usr/pkg/lib/python2.5/site-packages/`
  * OpenBSD: `usr/local/lib/python2.5/site-packages/`
  * OS X: <I've never used it, can someone let me know?>
  * Windows: `C:\Program Files\Python25\Lib\site-packages\`

That should be enough for "import prettytable" to work.