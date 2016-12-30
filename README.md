# GrubForAtivBook6
fix for brightness problem with linux (manjaro in this case) and Ativ Book 6
------------------------------------------------------------
> /etc/default/grub

GRUB_DEFAULT=saved

GRUB_TIMEOUT=5 

GRUB_DISTRIBUTOR='Manjaro'

GRUB_CMDLINE_LINUX_DEFAULT="quiet splash acpi_backlight=video"

GRUB_CMDLINE_LINUX=""

