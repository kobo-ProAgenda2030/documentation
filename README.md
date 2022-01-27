# documentation
Documentación del proyecto PRIAS (ProAgenda2030)

## Raíz

Algunos videos de introducción a los documentos del proyecto (se cambió el nombre de las carpetas pero los nombres de los archivos siguen siendo los mismos)
- Introduction groots-pa2030-docs-1.mp4
- Introduction groots-pa2030-docs-2.mp4
- Introduction groots-pa2030-docs-3.mp4

## Architecture
- Análisis - CAPY Profile
  - Evaluación de la función "Perfil CAPY", nunca se implementó
- Architectura - Definición por FASES
  - Evaluación inicial del alcance y los requisitos del proyecto, en gran parte obsoleta pero contiene algunos diagramas de flujo, red y arquitectura en su mayoría válidos (Fase 2 - Arquitectura Candidate B is the closest to actual implementation)
- Architectura - KoboToolbox vs ODK - Pros y Cons
  - Aunque el documento recomienda usar KoboToolbox sobre ODK, ODK se usó al final ya que su código base era más nuevo y mejor (actualizado a los cambios recientes de KoboToolbox) y tenía un mayor apoyo de la comunidad.
- **Arquitectura - Requerimientos técnicos para instituciones beneficiarias candidatas**
  - Documento principal para organizaciones objetivo/entidades gubernamentales. Describe los requisitos técnicos principales y las recomendaciones para la configuración del servidor local.

## Deployment
- Deployment - AWS deployment considerations - Groots
  - Descripción del proceso de implementación de AWS y los servicios necesarios
- Deployment - Runbook - Fase 1.docx
  - Documento principal para el proceso de implementación de "KoBoToolbox" (usando un script de Python)
- Deployment - Runbook + Support API – Fase 2
  - Documento principal para el proceso de implementación de "Support API" (para desarrolladores y processos de despliegue)
- Deployment – Support API – Docker estructures
  - Describe los contenedores Docker de la "Support API".
- Maintenance - Backups de base de datos
  - Describe los procesos de copia de seguridad de diferentes bases de datos + problemas conocidos. **USO BAJO PROPIO RIESGO, SIN GARANTÍAS!**

### Deployment/scripts
- algunos comandos y registros útiles para diferentes procesos de despliegue. **USO BAJO PROPIO RIESGO, SIN GARANTÍAS!**
 
## Development
- Dashboards - Gestión de archivos R
  - Describe el proceso para instalar y actualizar los archivos de R Dashboard en el servidor
  - Video Tutorial: dashboards-para-sys-admins.mp4
- Development – KoBoToolbox customizations
  - Describe los cambios personalizados realizados en "KoBoToolbox" bifurcado y repositorios relacionados
- Development - Repos & Dockerization
  - Enumera todos los repositorios y describe cómo fusionar cualquier cambio futuro en los repositorios originales (correcciones de errores) a las bifurcaciones del proyecto PRIAS
- Development - Support API Requirements
  - Describe las pautas de desarrollo y los requisitos técnicos del proyecto (para nuevos desarrolladores)
