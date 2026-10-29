R.L.T. - Registro de Llegadas Tarde

PUBLICAR EN GITHUB PAGES

1. Entra a https://github.com e inicia sesión.
2. Pulsa New repository y crea un repositorio, por ejemplo: sistema-rlt.
3. Sube el archivo index.html a la raíz del repositorio (no dentro de una carpeta).
4. En el repositorio entra a Settings > Pages.
5. En Build and deployment, selecciona Deploy from a branch.
6. Elige la rama main y la carpeta /(root), luego pulsa Save.
7. Espera unos minutos y abre la URL que GitHub Pages mostrará en esa pantalla.

PERFILES
- Usuario: solo consulta desde la interfaz.
- Programador: contraseña inicial RLT2026. Cámbiala antes de compartir el proyecto.

IMPORTANTE SOBRE LOS DATOS Y LA SEGURIDAD
- Esta versión guarda cambios en localStorage del navegador/dispositivo que se esté usando. Los datos no se sincronizan entre distintos usuarios o computadores y pueden perderse si se borra el almacenamiento del navegador.
- La contraseña y los permisos de una aplicación estática HTML/JavaScript no son seguridad real; una persona con conocimientos técnicos puede inspeccionar el código o alterar la página.
- Para usarlo con datos oficiales de estudiantes, conecta el proyecto a Firebase (Authentication + Firestore) y configura reglas de seguridad para que solo el perfil autorizado pueda escribir o borrar datos. No publiques datos personales reales en un repositorio público.
