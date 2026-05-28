# Linux-notes-

# Mis prácticas SOC

## Temas vistos
- Linux
  │   ├── comandos-basicos.md
│   ├── auth-log-analysis.md
│   ├── usuarios-y-permisos.md

- Wireshark
- │   ├── captura-http.md
│   ├── analisis-paquetes.md

- SQL
- │   ├── consultas-basicas.md
│   ├── inner-join.md
│   ├── filtros-y-like.md

- auth.log
- Python
- │   ├── variables.md
│   ├── scripts-basicos.md

- Incident - response
- │   ├── brute-force-analysis.md

## Objetivo
Aprender análisis de seguridad y documentar laboratorios.

## Comandos Linux aprendidos

### grep
Buscar texto dentro de archivos.

Ejemplo:
grep "Failed password" auth.log

## Laboratorio Wireshark

Objetivo:
Capturar tráfico HTTP y analizar paquetes.

Hallazgos:
- se identificó IP origen
- método GET observado
