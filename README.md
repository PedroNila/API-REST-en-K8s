# API-REST-en-K8s
API REST en K8s, se mostrarán los pasos para su realizacion y archivos .yaml
# Instructivo: Implementación de API REST en Kubernetes (K8s)

## Pasos:

1. **Preparación de Imágenes:**
   Asegúrate de tener las imágenes de tu API y su base de datos lista.

2. **Subir Imágenes a Docker Hub:**
   - Inicia sesión en Docker Hub.
   - Sube las imágenes al Docker Hub.

3. **Pull de Imágenes:**
   Haz pull de las imágenes desde Docker Hub.

4. **Iniciar Minikube:**
   Inicia Minikube.

5. **Verificación de Minikube:**
   Verifica que Minikube esté en ejecución.

6. **Crear Archivos YAML:**
   - `apiapp-deployment.yaml`
   - `postgres-deployment.yaml`
   - `postgres-pvc.yaml`
   - `ingress.yaml`

7. **Aplicar YAML a Kubernetes:**
   Aplica los archivos YAML en Kubernetes.

8. **Verificación:**
   Verifica que todo se haya desplegado correctamente.

9. **Prueba de la API:**
   Usa curl o accede a través del navegador para probar la API.

10. **Verificación Final:**
    Asegúrate de que la API sea accesible a través del dominio o la dirección IP.


