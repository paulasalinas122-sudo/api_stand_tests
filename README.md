# API Stand Tests

## Descripción
Este proyecto contiene pruebas automatizadas para validar la funcionalidad de creación de usuarios en una API.

## Funcionalidades probadas
- Creación exitosa de usuarios con diferentes longitudes de nombres
- Validación de caracteres permitidos en nombres de usuario
- Manejo de errores para parámetros faltantes o inválidos

## Archivos principales
- `create_user_test.py` - Contiene todas las pruebas automatizadas
- `sender_stand_request.py` - Funciones para enviar solicitudes HTTP
- `data.py` - Datos de prueba y configuración
- `configuration.py` - Configuración del proyecto

## Cómo ejecutar las pruebas
```bash
pytest create_user_test.py

# API Stand Tests
Este proyecto contiene pruebas para la API de Urban Grocers.