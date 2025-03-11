Importante para credenciales
# Configurar global el nombre de usuario y la dirección de correo electrónico en Git. 
# Además, se aconseja tener una cuenta de usuario en GitHub para facilitar la colaboración y la conexión remota con repositorios en la plataforma.

git config --global user.name "nombreUsuarioGithub"
git config --global user.email "exmple@gmail.com"

# Configurar el editor predeterminado que Git utilizará al abrir mensajes de confirmación (commits) o al realizar otras 
#operaciones que requieren la edición de texto, en este ejemplo "visual studio code"

git config --global core.editor "code --wait"
git branch -m main default