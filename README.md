# ngnix-unit-conf
Set of templates to configure nginx and uintd, and a tool to put everything by one command

Something like 

nginx-unit-conf --backend=wordpress --show-params

upstream_server 
direct_server

nginx-unit-conf domain.my --host=domain.my --path=/usr/local/www/domain.my/htdocs --nginx-conf-dir=/usr/local/etc/nginx/conf.d --sites-enabled=no --backend=wordpress --upsream_server=127.0.0.1:8900 --index_server=127.0.0.1:8901 --reload_nginx=yes --reconfigure_unitd=yes

Or maybe something briefer, or even TUI
