# odoo-learning

# start Odoo Server
/opt/odoo/odoo/odoo-bin -c /opt/odoo/etc/odoo.conf

# Update module (student) in database (odoo-testing)

/opt/odoo/odoo/odoo-bin -c /opt/odoo/etc/odoo.conf -u student -d odoo-testing

# Scaffold
 /opt/odoo/odoo/odoo-bin scaffold  module_name new_directory_location
 /opt/odoo/odoo/odoo-bin scaffold student /opt/odoo/extra-addons/bharti-addons/
