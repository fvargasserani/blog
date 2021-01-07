Link a Heroku: https://stark-taiga-11193.herokuapp.com/



CREACION DE MODELOS Y CAMPOS

Terminal > rails g model user nombre_del_modelo (solo se realiza una vez este paso)

Terminal > rails g migration addCampoToModelo campo:text (o el tipo de dato que queremos ingresar)

Corroborar en db > migrate > que se encuentre el archivo con la columna del nuevo campo creado

Terminal > rails db:migrate 

Crear un nuevo campo dentro del formulario, en la pagina index.html.erb

Agregar este nuevo campo en el controlador pages, en el metodo create

Puedes corroborar el ingreso de datos al entrar a la consola, ejecutando rails c e ingresando el comando User.last

Agregar estilo con Bootstrap a nuestro formulario
