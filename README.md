# Final_proyect_MAPQ_sam
Entrega final para análisis de valores MAPQ de un archivo.sam

# Proyecto

Este proyecto analiza ficheros SAM en python y calcula nº total de lecturas alineadas y nº de lecturas con alto >

## Requisitos
- Python
- uv
- Nextflow

Revisar versiones en el fichero pyproyect.toml

## Uso

```bash
uv run main.py ruta/al/archivo.sam

## Ejecutar el pipeline en Nextflow

```bash
nextflow run main.nf --sam ruta/al/archivo.sam



