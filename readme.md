## repo clone Command
odoo17 download command ---->      git clone https://github.com/odoo/odoo.git  --branch 17.0 --depth=1

odoo16 download command ---->      git clone https://github.com/odoo/odoo.git  --branch 16.0 --depth=1


## run Command (we have to edit this command as we needs)
python odoo-bin -r Db_user -w Db_password --addons-path=addons,Module_outer_folder_name -u Module_name --http-port=8070
