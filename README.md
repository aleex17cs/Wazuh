# Wazuh

## Introducción 
Wazuh es una plataforma de seguridad de código abierto (open-source) diseñada para la detección de amenazas, el monitoreo de la integridad y la respuesta ante incidentes.
Básicamente, funciona como un "vigilante" centralizado que recolecta y analiza datos de todos tus equipos (servidores, computadoras, la nube) para avisarte si algo anda mal.

## ¿Qué hace?
- :eyes: **Detección de Intrusos:** Identifica ataques externos, malware, rootkits y anomalías en el comportamiento del sistema.
- :bust_in_silhouette: **Análisis de Registros (Log Analysis):** Recolecta los mensajes que generan tus programas y sistemas para buscar patrones sospechosos.
- :clipboard: **Monitoreo de Integridad (FIM):** Te avisa si alguien modifica, crea o borra archivos críticos del sistema.
- :rotating_light: **Detección de Vulnerabilidades:** Escanea tus equipos en busca de software desactualizado o configuraciones inseguras que los hackers podrían aprovechar.
- :white_check_mark: **Cumplimiento Normativo:** Ayuda a cumplir con estándares de seguridad como PCI DSS, GDPR o HIPAA mediante informes automáticos.

## ¿Cómo funciona?
- **Agentes:** Pequeños programas que instalas en tus dispositivos (Windows, Linux, macOS) para monitorearlos.
- **Servidor central:** Recibe la información de los agentes, la analiza mediante reglas y genera alertas.
- **Interfaz (Dashboard):** Una consola visual (basada en OpenSearch) donde puedes ver gráficas y detalles de todo lo que ocurre en tu red.

## Requisitos
| Agentes | CPU | RAM | Almacenamiento (90 dias) |
| :---: | :---: | :---: | :---: |
| 1-25 | 4vCPU | 8GiB | 50 GB |
| 25-50 | 8vCPU | 8GiB | 100 GB |
| 50-100 | 8vCPU | 8GiB | 200 GB |

## Sistema operativo

- Amazon Linux 2, Amazon Linux 2023
- CentOS Stream 10
- Red Hat Enterprise Linux 7, 8, 9, 10
- Ubuntu 16.04, 18.04, 20.04, 22.04, 24.04

## Ejemplos
[Detención de vulnerabilidades](dett_vuln.md)
