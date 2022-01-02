# Trucos de Odoo

Marlon Falcón Hernández | Valencia, España
- ERP, CRM y Software
- WhatsApp: +34 662 47 06 45
- Telegram: falconsoft
- Email: mfalconsoft@gmail.com , falconsof.3d@gmail.com
- Github: https://github.com/falconsoft3d
- linkedin: https://linkedin.com/in/marlon-falcón-3a2aa9a4



![Alt text](https://github.com/falconsoft3d/instalar-odoo-10/blob/master/img/logo-ynext.png?raw=true "Ynext")


- [Trucos en los Modelos](https://github.com/Odoo-10-test/trucos_odoo/blob/master/modelos.md)
- [Trucos en los Vistas](https://github.com/Odoo-10-test/trucos_odoo/blob/master/views.md)

- Actualizar
```  
service odoo stop
su - odoo -s /bin/bash
python3 /usr/bin/odoo -c /etc/odoo/odoo.conf -d db13-bim -u all --stop-after-init --logfile=/dev/stdout
service odoo start
``` 

```  
python /opt/odoo/server/odoo-bin -c /etc/odoo/odoo.conf -d db10-chile-sii -u all --stop-after-init
```  

```  
--conf=/opt/odoo13/odoo/debian/odoo.conf -u full_mobile_service_shop
``` 

``` 
erppeek --server="http://localhost:8069" -d db10-chile-sii -u admin -p x1234567890
client.upgrade('direct_credit_note')
``` 
