# Cinnamon-Layout

Cinnamon-Layout is a utility to switch between different Cinnamon desktop layouts based on pre-defined gschema.override files. Cinnamon-Layout is run for each user wanting to change their desktop layout. The user is then prompted to run cinnamon-layout-system, which would change the system default by placing a symlink to the chosen gschema.override file in /usr/share/glib-2.0/schemas, effectively making it the system default.

There are different branches of Cinnamon-Layout depending on the version of Cinnamon. Check the different branches for the source.

The default layout does not depend on any additional Cinnamon applets or extensions. However, other layouts may depend on them. The additional applets or extensions that are used by different Cinnamon-Layouts are bundled as part of Cinnamon-Layout to ensure that they will be found.
