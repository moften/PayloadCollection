# PayloadCollection
XSS - SQL - etc payload collection 
# m10sec@proton.me

# Payload Collection

**Payload Collection** es un repositorio dedicado a almacenar y organizar una amplia variedad de payloads útiles para pruebas de seguridad en aplicaciones web y otros entornos. Este repositorio está diseñado para servir como una referencia rápida para pentesters, profesionales de seguridad y desarrolladores interesados en comprender o mitigar vulnerabilidades de seguridad comunes.

## Contenidos

El repositorio incluye payloads organizados por categorías, tales como:

- **Inyección SQL (SQL Injection)**: Payloads para explotación y detección de vulnerabilidades de SQLi.
- **Cross-Site Scripting (XSS)**: Diversos payloads para pruebas de XSS reflejado, almacenado y DOM-based.
- **Command Injection**: Payloads para pruebas de inyección de comandos en distintos entornos y lenguajes.
- **Directory Traversal**: Ejemplos de traversal para acceso no autorizado a archivos del sistema.
- **Server-Side Request Forgery (SSRF)**: Payloads para pruebas de SSRF en diferentes servidores y entornos.
- **Otros**: Payloads para pruebas de vulnerabilidades adicionales, como LDAP Injection, XPath Injection, XXE, etc.

> **Nota:** Cada payload está destinado a ser utilizado en entornos de prueba o con permiso explícito del propietario del sistema. No intentes ejecutar estos payloads en sistemas sin autorización.

## Estructura del Repositorio

Cada categoría de payload tiene su propio directorio y está organizada en archivos de texto, proporcionando ejemplos claros y listos para usar. La estructura del repositorio es la siguiente:

PayloadCollection/
├── SQL_Injection/
├── XSS/
├── Command_Injection/
├── Directory_Traversal/
├── SSRF/
└── Other/

Dentro de cada carpeta, los archivos están nombrados según el tipo de vulnerabilidad y el lenguaje o tecnología específica.

## Uso

1. Clona el repositorio en tu máquina local:

   ```bash
   git clone https://github.com/moften/PayloadCollection.git


   Contribuciones
   * m10sec

Este proyecto acepta contribuciones para mejorar o ampliar el conjunto de payloads. Si deseas contribuir, por favor sigue estos pasos:

	1.	Crea un fork de este repositorio.
	2.	Realiza los cambios o agrega nuevos payloads en una nueva rama.
	3.	Haz un Pull Request explicando el cambio o la adición.
