# Sistema Forense Legal

**Por:** jusegora (Abogado Especialista en Derecho Penal y Criminalística)

## ¿De qué trata esto?
Actualmente, herramientas como Magnet AXIOM son excelentes para recolectar datos y encontrar evidencia técnica. Sin embargo, en el mundo real, un juez no lee archivos JSON ni consolas de código. El paso final (convertir todos esos hallazgos en un informe legal estructurado y defendible en juicio) sigue siendo un proceso manual y muy propenso a errores humanos.

Desarrollé este sistema para automatizar esa brecha. 

## ¿Qué hace el sistema?
El código fuente de este proyecto es privado porque hace parte de mi propiedad intelectual. Sin embargo, las capacidades que tiene el motor incluyen:

- **Aseguramiento de Evidencia:** Calcula hashes criptográficos (SHA-256) para garantizar que los archivos no fueron alterados.
- **Detección de Fugas:** Analiza los logs de Microsoft 365 para detectar descargas masivas o accesos desde IPs sospechosas.
- **Triaje con IA Local:** Extrae nombres de personas y montos de dinero usando procesamiento de lenguaje natural (NLP), sin enviar datos a la nube (garantizando la confidencialidad).
- **Generación de Informes:** Consolida todo lo anterior en un documento PDF con formato pericial, listo para presentar ante un juez.

## Contacto y Demostración
Si eres reclutador, investigador o representante de una firma de auditoría y quieres ver una demostración en vivo del sistema, o revisar el código fuente bajo un acuerdo de confidencialidad (NDA), puedes escribirme directamente:

- **Correo:** jusegora@gmail.com
- **GitHub:** [@jusegora](https://github.com/jusegora)
