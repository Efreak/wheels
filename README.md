Wheels for use with termux, to avoid the need to compile anything.

Eventually this repo should have a directory structure expeted by pip to allow installing with pip (or pipx)

Wheels generated with `pip wheel $name` on an aarch64 device; they may require native dependencies.

You *should* be able to use this repo with pip using the command `pip install --index-url=https://github.com/Efreak/wheels/raw/main $package`. For easy use, I recommend setting an alias in your .bashrc.
