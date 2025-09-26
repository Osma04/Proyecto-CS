# Proyecto-CS
Proyecto de evaluación usando C# .NET Framework

Tecnologías utilizada:
Lenguaje:C# .NET Framework
IDE: Visual Studio 2022
Base de datos: Microsoft SQL Server
Control de versiones: Git y GitHub


El sistema está dividido en capas para mejorar la mantenibilidad:

CapaEntidad : Define las entidades del sistema (Producto, Cliente, Trabajador, etc.).  
CapaDatos : Maneja la conexión a la base de datos y operaciones CRUD.  
CapaNegocio : Contiene la lógica de negocio y validaciones.  
CapaPresentacion : Interfaces gráficas en WinForms para el usuario.  
Base de Datos : Incluye scripts y backups para la creación del esquema y datos de prueba.


Dentro de la carpeta Base de Datos:

"dbventas_Script.sql" : script para crear tablas, procedimientos almacenados y datos iniciales.  
"dbventas_Bakup.bak" : backup de la base de datos completa.  
