# Utiliza una imagen base oficial de Node.js
FROM node:15

# Establece el directorio de trabajo
WORKDIR /usr/src/app

# Copia los archivos de configuración de la aplicación
COPY package*.json ./

# Instala las dependencias
RUN npm install

# Copia el resto del código de la aplicación
COPY . .

# Expone el puerto de la aplicación
EXPOSE 5000

# Comando para iniciar la aplicación
CMD ["node", "app.js"]
