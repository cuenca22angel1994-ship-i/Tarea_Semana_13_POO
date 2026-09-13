# Tarea_Semana_13_POO
Conceptos fundamentales de interfaces gráficas de usuario en restaurante_app
## Alumno:
Angel Rafael Cuenca Tamayo

## Descripción
Esta aplicación marca el inicio de la transición de *Restaurante App* hacia una Interfaz Gráfica de Usuario (GUI) desarrollada con *Tkinter* en Python, basada en la arquitectura por capas del proyecto docente.

## Propósito
Demostrar el uso de conceptos fundamentales de GUI, manteniendo una arquitectura limpia y modular mediante la separación en modelos, servicios y vistas UI, con persistencia local mediante archivos JSON.

## Estructura del Proyecto
restaurante_app/
├── datos/
│   ├── productos.json
│   └── usuarios.json
├── modelos/
│   ├── __init__.py
│   ├── producto.py
│   └── usuario.py
├── servicios/
│   ├── __init__.py
│   ├── archivo_servicio.py
│   └── restaurante_servicio.py
├── ui/
│   ├── __init__.py
│   ├── login_view.py
│   └── main_view.py
├── main.py
└── README.md

## Flujo de la Aplicación
Inicio: Ejecución de main.py inicializando Tkinter y servicios.
LoginView: Pantalla de autenticación simulada.
Validación: RestauranteServicio verifica las credenciales en usuarios.json.
MainView: Panel principal que despliega listados de productos y usuarios.
Cierre de sesión: Retorno a la pantalla de login dentro del mismo ciclo de ventana.
