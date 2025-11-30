sudo mkdir -p /run/uwsgi
sudo chown quangtrioj:quangtrioj /run/uwsgi
sudo supervisorctl restart site
sudo supervisorctl status site
