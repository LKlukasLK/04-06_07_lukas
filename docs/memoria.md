# Memoria de Práctica de Despliegue con Git y Tomcat

**Nombre del alumno:** Lucas Padilla Pacheco  


## Configuración de Infraestructura
*   **IP MV Cliente (Desarrollo): ** 192.168.1.33
*   **IP MV Servidor (Producción):** 192.168.1.36  
*   **Repositorio Remoto:** https://github.com/LKlukasLK/04-06_07_lukas.git 

## Flujo de Trabajo Realizado
1. Se configuró el repositorio local en la MV Cliente.
2. Se subió el código fuente y el artefacto (.war) a GitHub mediante un Personal Access Token.
3. Se clonó el repositorio en la MV Servidor.
4. Se desplegó manualmente el archivo .war en la carpeta `webapps` de Tomcat.
5. Se verificó el acceso desde el navegador de la MV Cliente.

## Cuestionario final
1. **Herramienta de registro:** Git.
2. **Servicio puente:** GitHub.
3. **Ventajas:** Control de versiones, mayor seguridad (tokens), facilidad de actualización y trazabilidad de cambios.
