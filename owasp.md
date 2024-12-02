# Cuestionario sobre OWASP y Seguridad en el Software

### 1. ¿Qué es OWASP y cuál es su principal objetivo? (3 pts)

OWASP (Open Web Application Security Project) es una organización sin fines de lucro dedicada a mejorar la seguridad del software. Su principal objetivo es proporcionar recursos, herramientas y estándares que ayuden a los desarrolladores y empresas a crear aplicaciones más seguras.

### 2. ¿Qué es el OWASP Top 10 y por qué es importante para los desarrolladores? (4 pts)

El OWASP Top 10 es una lista de las diez principales vulnerabilidades de seguridad en aplicaciones web, basada en investigaciones y datos recopilados por la comunidad de OWASP. Es importante para los desarrolladores porque los ayuda a conocer y prevenir las amenazas más comunes, mejorando la seguridad de sus aplicaciones.

### 3. Describe brevemente dos de las vulnerabilidades del OWASP Top 10 2017. (4 pts)

- **Inyección SQL**: Ocurre cuando se puede manipular una consulta de base de datos a través de la entrada del usuario, lo que permite a los atacantes acceder o modificar datos de manera no autorizada.
- **Cross-Site Scripting (XSS)**: Permite a los atacantes inyectar scripts en el navegador de un usuario, lo cual puede llevar a la captura de información sensible o manipulación de la interfaz de usuario.

### 4. ¿Qué es OWASP ASVS y cuáles son sus niveles de verificación? (4 pts)

OWASP ASVS (Application Security Verification Standard) es un marco de trabajo para verificar la seguridad de aplicaciones. Define tres niveles de verificación:
1. **Nivel 1**: Recomendado para todas las aplicaciones.
2. **Nivel 2**: Adecuado para aplicaciones que manejan datos sensibles.
3. **Nivel 3**: Para aplicaciones de alta seguridad, como aquellas en entornos críticos.

### 5. ¿Cuál es la diferencia entre los niveles 1 y 3 de OWASP ASVS? (4 pts)

La principal diferencia entre los niveles 1 y 3 de OWASP ASVS es el rigor en los requisitos de seguridad. El Nivel 1 cubre controles básicos de seguridad, mientras que el Nivel 3 incluye controles avanzados, destinados a aplicaciones con un riesgo mayor y en entornos críticos.

### 6. ¿Qué es el modelado de amenazas y cuáles son sus beneficios? (4 pts)

El modelado de amenazas es el proceso de identificar y evaluar amenazas potenciales en una aplicación o sistema. Sus beneficios incluyen una mejor comprensión de los riesgos de seguridad, la planificación de medidas de protección y la prevención de ataques antes de que ocurran.

### 7. Nombra dos metodologías de modelado de amenazas. (3 pts)

1. **STRIDE**: Focalizada en categorizar amenazas en Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, y Elevation of Privilege.
2. **DREAD**: Permite clasificar las amenazas en función de factores como el daño, la reproductibilidad, la explotabilidad, los usuarios afectados y la detectabilidad.

### 8. ¿Qué es el SDL y cómo ayuda a la seguridad del software? (4 pts)

El SDL (Security Development Lifecycle) es un proceso que integra prácticas de seguridad en cada fase del ciclo de desarrollo de software. Ayuda a mejorar la seguridad del software al identificar y solucionar vulnerabilidades de seguridad antes de que se implementen en producción.
