# ISAL-L

To regenerate new autotool files run the following commands

```
aclocal
$(libtoolize --quiet --automake --copy --force || glibtoolize --quiet --automake --copy --force)
autoconf
automake --add-missing --copy --foreign

```
