# dracut-alpm-hook

This provides [alpm hooks][alpm-hooks5] for [dracut][dracut] to generate a new initramfs on kernel upgrade.

## Usage

Copy hooks (`*.hook`) to `/usr/share/libalpm/hooks` and scripts  to `/usr/share/libalpm/scripts`.

## License

[FDL 1.3][fdl]

[alpm-hooks5]:https://www.archlinux.org/pacman/alpm-hooks.5.html
[dracut]:https://github.com/dracutdevs/dracut
[fdl]:http://www.gnu.org/licenses/fdl-1.3.html

