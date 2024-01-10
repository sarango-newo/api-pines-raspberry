# Api pines Raspberry

## Requisitos previos

- Python 3.7 o superior
- Raspberry Pi (si es aplicable)

## Instalación

1. Clona el repositorio:

    ```bash
    git clone https://github.com/tu_usuario/tu_proyecto.git
    cd tu_proyecto
    ```

2. Crea un entorno virtual (opcional, pero se recomienda):

    ```bash
    python -m venv venv
    source venv/bin/activate  # En sistemas basados en Unix
    # O
    .\venv\Scripts\activate  # En sistemas basados en Windows
    ```

3. Instala las dependencias:

    ```bash
    pip install -r requirements.txt
    ```

## Uso

1. Asegúrate de que la Raspberry Pi esté configurada correctamente (si es aplicable).

2. Ejecuta la aplicación:

    ```bash
    uvicorn main:app --host 0.0.0.0 --port 4000 --reload
    ```

3. Accede a la API desde tu navegador o herramienta de cliente API preferida.

## Endpoints

- `GET /encender/{pin}`: Enciende el pin especificado.
- `GET /apagar/{pin}`: Apaga el pin especificado.
- `GET /consultar/{pin}`: Consulta el estado del pin especificado.

## Contribuciones

¡Contribuciones son bienvenidas! Si encuentras un error o tienes alguna mejora, siéntete libre de abrir un _issue_ o enviar un _pull request_.

## Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.
