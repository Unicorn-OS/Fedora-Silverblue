# Favorite:
- https://yorickpeterse.com/articles/switching-to-fedora-silverblue/

>**Use GNOME terminal profiles for your containers**
>Distrobox can create .desktop files for your containers, making it easier to start/enter them. If you open a new tab in that terminal it will open the tab in the default shell, not in the container; at least when using GNOME terminal. To work around this I adjusted the generated .desktop file to instead start GNOME terminal with a dedicated profile like so:
>
>**Give your containers a custom home directory**
This isn't necessary if you only intend to use a single container, but if you use multiple containers it's a must: when creating a container using Distrobox, the --home flag is used to specify a custom home directory. This way the container won't pollute your actual home directory, and two different containers using the same files in your home directory won't conflict.

- https://www.redhat.com/sysadmin/fedora-silverblue

# index:
- https://github.com/fedora-silverblue/silverblue-docs/issues/1
