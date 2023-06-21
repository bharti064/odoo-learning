# odoo-learning

#start Odoo Server
/opt/odoo/odoo/odoo-bin -c /opt/odoo/etc/odoo.conf

# Update module (student) in database (odoo-testing)

/opt/odoo/odoo/odoo-bin -c /opt/odoo/etc/odoo.conf -u student -d odoo-testing
