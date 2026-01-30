# Atlas Automotriz Assets

Repositorio público de assets usados por Atlas Automotriz (logos, banderas e imágenes de modelos).

## Estructura

```
/ultimatespecs_complete_db.jsonl
/ultimatespecs/...
/car-logos-dataset/...
/flags/...
```

## Uso recomendado (CDN)

Base URL:

```
https://<PROJECT_REF>.supabase.co/storage/v1/object/public/assets
```

Ejemplos:

- JSONL principal:
  - `/ultimatespecs_complete_db.jsonl`
- Imágenes de modelos:
  - `/ultimatespecs/<Brand>/<file>.jpg`
- Logos:
  - `/car-logos-dataset/logos/optimized/<slug>.png`
- Banderas:
  - `/flags/SVG/AR.svg`

## Notas

- Este repo contiene únicamente assets estáticos.
- Si actualizas los nombres de archivos, actualiza el JSONL para reflejar los cambios.

## Licencia

Define la licencia que corresponda al dataset (por ejemplo, CC BY 4.0) y agrega el archivo LICENSE.
