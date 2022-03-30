[![Copr build status](https://copr.fedorainfracloud.org/coprs/faultline/emacs-pgtk-nativecomp/package/emacs/status_image/last_build.png)](https://copr.fedorainfracloud.org/coprs/faultline/emacs-pgtk-nativecomp/package/emacs/)

## Pure Gtk and native compilation builds of GNU Emacs 28

This package is mostly aligned with the GNU Emacs package from
official Fedora repositories.
- [https://src.fedoraproject.org/rpms/emacs](https://src.fedoraproject.org/rpms/emacs)

## Credits & Licensing
- This copr was forked from [deathwish/emacs-pgtk-nativecomp-copr](https://github.com/deathwish/emacs-pgtk-nativecomp-copr) but pinned to version 28 as version 29 has some breaking changes
- Thanks to [flatwhatson/emacs](https://github.com/flatwhatson/emacs) who maintains a repo of emacs-28 with pgtk and nativecomp

The repository
[faultlin3/emacs-pgtk-nativecomp-copr](https://github.com/faultlin3/emacs-pgtk-nativecomp-copr)
containing build recipes for [Copr project
emacs-gtk-native-comp](https://copr.fedorainfracloud.org/coprs/faultlin3/emacs-pgtk-nativecomp/)
is a fork of [Copr project
emacs-gtk-native-comp](https://copr.fedorainfracloud.org/coprs/deathwish/emacs-pgtk-nativecomp/) which is a fork of
[https://src.fedoraproject.org/rpms/emacs](https://src.fedoraproject.org/rpms/emacs).

This fork as well as the original repository ([according to
FPCA](https://fedoraproject.org/wiki/Legal:Fedora_Project_Contributor_Agreement#Other_FAQs))
are licensed under MIT License. See
[LICENSE](https://github.com/A6GibKm/emacs-pgtk-nativecomp-copr/blob/master/LICENSE)
for the full license text.

## How to install/update
- Enable this copr repository,
  ```sh
  $ dnf copr enable faultlin3/emacs-pgtk-nativecomp
  ```
- Install latest pretest,
  ```sh
   $ dnf install emacs
  ```
  or update the installed version,
  ```sh
  $ dnf update emacs
  ```

## Reporting issues
If you face any issues while installing or updating, please create an
issue on [GitHub repository
here](https://github.com/faultlin3/emacs-pgtk-nativecomp-copr).
