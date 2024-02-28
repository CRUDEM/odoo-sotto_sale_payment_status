# Odoo Sale Payment Status Add-on (sotto_sale_payment_status)

This add-on aims at providing payment status information on Odoo sale orders. For more information please visit official add-on website/Odoo platform [here](https://apps.odoo.com/apps/modules/14.0/sotto_sale_payment_status/#).

This documentation outlines the modifications made to the "sotto_sale_payment_status" addon in the Odoo platform.

Release notes:

## Version 14.0-1.0.0
Changed the value of the auto_install attribute to True in the `__manifest__.py`file. By setting auto_install to True, the addon will now automatically install along with its dependencies when the module is installed thus preventing manual installations through the UI.