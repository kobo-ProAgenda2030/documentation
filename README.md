# documentation
Documentation for KoBoToolbox (ProAgenda2030) project, in SPANISH!

## Root

Some introduction videos into the project's documents (folders have been renamed but file names remain the same)
- Introduction groots-pa2030-docs-1.mp4
- Introduction groots-pa2030-docs-2.mp4
- Introduction groots-pa2030-docs-3.mp4

## Architecture
- Análisis - CAPY Profile
  - Evaluation of "CAPY Profile" Feature, was never implemented
- Architectura - Definición por FASES
  - Initial evaluation of project scope and requirements, largely obsolete but contains some mostly valid architecture, network and flow diagrams (Fase 2 - Arquitectura Candidate B is the closest to actual implementation)
- Architectura - KoboToolbox vs ODK - Pros y Cons
  - Although the document recommends using KoboToolbox over ODK, ODK was used in the end since its code base was newer & better (updated to recent KoboToolbox changes) and had stronger community support
- **Arquitectura - Requerimientos técnicos para instituciones beneficiarias candidatas**
  - Main document for target organizations/government entitities. Describes princicpal tecnical requirements and recommendations for on premise server setup. 

## Deployment
- Deployment - AWS deployment considerations - Groots
  - Description of AWS deployment process and required services
- Deployment - Runbook - Fase 1.docx
  - Principal document for "KoBoToolbox" deployment process (using a Python script)
- Deployment - Runbook + Support API – Fase 2
  - Principal document for "Support API" deployment process (for Developers and for Live Deployment)
- Deployment – Support API – Docker estructures
  - Describes Docker containers of Support API
- Maintenance - Backups de base de datos
  - Describes backup processes of different DBs + known issues. USE AT OWN RISK, NO WARRANTIES!

### Deployment/scripts
- some usefull commands and logs for different deployment processes. USE AT OWN RISK, NO WARRANTIES!
 
## Development
- Dashboards - Gestión de archivos R
  - Describes process to install and update R Dashboard files to server
  - Video Tutorial: dashboards-para-sys-admins.mp4
- Development – KoBoToolbox customizations
  - Describes custom changes done to forked "KoBoToolbox" and related repos
- Development - Repos & Dockerization
  - Lists all repos and describes how to merge any future changes to the original repos (Bugfixes) into our custom forks
- Development - Support API Requirements
  - Describes Development Guidelines + technical requirements of project (for new Developers)
