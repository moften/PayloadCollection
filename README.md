# PayloadCollection

Colección de payloads para pruebas de seguridad: XSS, SQLi, Command Injection, SSRF y más.

Desarrollado por **m10sec** – m10sec@proton.me
---

## 📘 Descripción

**PayloadCollection** es un repositorio curado de payloads utilizados en pruebas de penetración (pentesting), hacking ético y análisis de vulnerabilidades. Esta colección está orientada a facilitar el trabajo de profesionales de ciberseguridad, investigadores, estudiantes y desarrolladores que buscan comprender, mitigar o validar vulnerabilidades comunes en aplicaciones web y entornos relacionados.
---
## Contenidos

## 📂 Categorías incluidas

Los payloads están organizados por tipo de vulnerabilidad para un acceso rápido y práctico:

- **🔴 SQL Injection (SQLi)**  
  Explotación y detección de inyecciones SQL en distintos contextos (GET, POST, headers, cookies).

- **🟡 Cross-Site Scripting (XSS)**  
  Reflejado, almacenado y DOM-based. Incluye vectores clásicos y evasión de filtros.

- **⚫ Command Injection**  
  Payloads para inyección de comandos en shells UNIX y Windows.

- **📁 Directory Traversal**  
  Acceso arbitrario a archivos del sistema a través de navegación de rutas.

- **🌐 Server-Side Request Forgery (SSRF)**  
  Payloads para forzar a un servidor a hacer peticiones hacia destinos internos o externos.

- **🧪 Otros (Misceláneos)**  
  LDAP Injection, XPath Injection, XXE, Local File Inclusion (LFI), Remote File Inclusion (RFI), etc.

- ⚠️**Advertencia:** Este material es solo para uso educativo y de investigación. No utilices estos payloads en sistemas sin autorización explícita. El uso indebido puede ser ilegal.

---
## Estructura del Repositorio

## 📁 Estructura del repositorio

```bash
PayloadCollection/
├── SQL_Injection/
├── XSS/
├── Command_Injection/
├── Directory_Traversal/
├── SSRF/
└── Other/
```

Dentro de cada carpeta, los archivos están nombrados según el tipo de vulnerabilidad y el lenguaje o tecnología específica.

---
## Uso

Clona el repositorio en tu máquina local:

   ```bash
   git clone https://github.com/moften/PayloadCollection.git

   ```

---

## 📬 Contacto

¿Dudas o sugerencias?

m10sec
📧 m10sec@proton.me
🐙 github.com/moften

Este proyecto acepta contribuciones para mejorar o ampliar el conjunto de payloads. Si deseas contribuir, por favor sigue estos pasos:

	1.	Crea un fork de este repositorio.
	2.	Realiza los cambios o agrega nuevos payloads en una nueva rama.
	3.	Haz un Pull Request explicando el cambio o la adición.
