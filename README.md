# database_flutter

Proyecto desarrollado en Flutter por Steeven Ortega para Seminario de Sistemas.

Video Tutorial en Youtube: https://youtu.be/t-WNVNk2B9I

## Instrucciones

El proyecto es una aplicación que funciona como un CRUD de Usuarios.

Dependecias utilizadas en el archivo pubspec.yaml

SQFLite: https://pub.dev/packages/sqflite
Path Provider: https://pub.dev/packages/path_provider

Se creo 3 clases:
db_helper.dart (Clase que ayuda con la conexión de la BD asi como las sentencias SQL de CREATE, INSERT, UPDATE, DELETE)
main.dart (Clase Principal donde esta desarrollada la aplicación y sus interfaces)
user.dart (Clase que funciona como modelo para el Usuario donde se crea sus atributos ID y NAME)
