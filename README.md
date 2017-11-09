# ansible_motd

Makes /etc/MOTD pretty!


Usage:
> ansible -i <inventory_file> motd_make_pretty.yml -e "host_group=<server_name|inventory_group>"


Utilizes http://artii.herokuapp.com/ site.

Full font list available at: http://artii.herokuapp.com/fonts_list

Default Font: c_ascii_ (overridable via extra vars 'font' variable)
