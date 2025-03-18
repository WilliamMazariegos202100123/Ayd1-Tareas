# Usa una imagen base de Python con Flask
FROM python:3.9

# Establece el directorio de trabajo
WORKDIR /app

# Copia los archivos del proyecto
COPY . .

# Instala las dependencias desde requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Expone el puerto 80
EXPOSE 80

# Comando para ejecutar la aplicación
CMD ["python", "app.py"]
