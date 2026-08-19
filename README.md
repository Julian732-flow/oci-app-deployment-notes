# Implementación de Aplicación en la Nube con OCI
Documentación y registro de avance del curso de Oracle Cloud Infrastructure.

## 💻 Módulo 3: Arquitectura OCI — Gestión de Usuarios y Cloud Shell

### Configuración realizada:
* **Creación de Usuarios/Grupos:** Definición del grupo de trabajo y asignación del usuario correspondiente.
<img width="412" height="368" alt="Captura de pantalla 2026-08-18 102906" src="https://github.com/user-attachments/assets/a4d49dcf-1f97-4fb3-b33d-62a2a8a376cf" />
<img width="492" height="410" alt="Captura de pantalla 2026-08-18 103044" src="https://github.com/user-attachments/assets/c6e043d5-d2af-4b34-b0eb-35ab26d055b2" />
<img width="774" height="307" alt="image" src="https://github.com/user-attachments/assets/787ee8e2-42fa-4967-9ea3-30733f5b9eb8" />

* **Políticas de Seguridad (Policies):** Aplicación del principio de menor privilegio (*least privilege*) para restringir o permitir acciones sobre recursos de OCI.
<img width="711" height="360" alt="image" src="https://github.com/user-attachments/assets/69b905aa-21fc-443e-a151-fee35f278e7f" />

* **Autenticación:** Configuración de credenciales de acceso y llaves API / SSH según el caso.
* **Conexión Segura con Cloud Shell:**
  * ### Generación de Llaves RSA en Cloud Shell

Se ingresó al directorio `.ssh` y se generó el par de llaves RSA (`cloudshellkey` y `cloudshellkey.pub`) para las conexiones SSH.
| :---: | :---: |
| ![Comando ssh-keygen](<img width="968" height="224" alt="image" src="https://github.com/user-attachments/assets/24cd451b-5742-4ef0-99fb-5cd5e2dfae16" />
) | ![Resultado Llave RSA](<img width="763" height="474" alt="image" src="https://github.com/user-attachments/assets/1d41fefa-5f5a-4ad8-95be-8d0607c0bcda" />
) |
