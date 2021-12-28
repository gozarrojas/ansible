# ¿Cómo creo una clave de acceso de AWS?

Una clave de acceso concede programático a sus recursos. Esto significa que la clave de acceso debe guardarse con la misma precaución que las credenciales de inicio de sesión de usuarios raíz de la cuenta de AWS.

Se recomienda realizar lo siguiente:

1. Crear un usuario de IAM y, a continuación, definir los permisos del usuario del modo más restrictivo posible. 
2. Crear la clave de acceso correspondiente a ese usuario de IAM

Modificar en main:
- **access_key:** tu_access_key
- **secret_key:** tu_secret_key
- **keyname:** como_se_llamara_tu_key
- **ec2name:** como_se_llamara_tu_instancia
- **ami**: ami
- **region**: region
