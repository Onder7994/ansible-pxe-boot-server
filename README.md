# ansible-pxe-boot-server
server for pxe linux distr boot

Edit roles/pxe-boot-server/defaults/main.yaml
If you use dhcp on mikrotik set use_local_dhcp: "no" in roles/pxe-boot-server/defaults/main.yaml.
After that add to dhcp server config "Boot file name" = pxelinux.0; "Next Server" = you_boot_server_ip
