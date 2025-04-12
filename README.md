# Despliegue de Sitio Web

# Estructura del Proyecto:
  index.html: Página principal del sitio.
  style.css: Estilos del sitio.
  assets/: Carpeta con imágenes y otros recursos.
  Dockerfile: Archivo con instrucciones para construir la imagen Docker.
  deployment.yaml: Manifiesto de Kubernetes para desplegar el contenedor.
  README.md: Documentación del proyecto.
  
1. Cloné el repositorio desde GitHub con el comando:
  git clone https://github.com/Sofi-Gomez/static-website.git
  cd static-website
2. Ingresé al directorio del proyecto:
  cd static-website
3. Verifiqué los archivos con dir 
4. Creé el archivo Dockerfile para empaquetar el sitio.
5. Construí la imagen:
docker build -t static-website:v1 .
6. Inicié Minikube:
minikube start
7. Apliqué el manifiesto de Kubernetes (deployment.yaml):
kubectl apply -f deployment.yaml
Accedí al sitio web a través del servicio expuesto.

🌐 5. Resultado
Podés poner una captura de pantalla del sitio funcionando o cómo se ve en el navegador.
