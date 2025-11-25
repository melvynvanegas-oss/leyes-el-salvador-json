# Documentos Legales de El Salvador - Formato JSON

Este repositorio contiene documentos legales de El Salvador convertidos a formato JSON estructurado.

## 📋 Documentos Incluidos

### Instructivo_UIF_Reformas_Septiembre_2023_2_.json

- **Tipo**: Instructivo
- **Número**: 380
- **Fecha de publicación**: 27 de octubre de 2021
- **Diario Oficial**: None
- **Títulos**: 6

### leyclda_2025_3_.json

- **Tipo**: Decreto Legislativo
- **Número**: 426
- **Fecha de publicación**: 9 de octubre de 2025
- **Diario Oficial**: No. 190
- **Títulos**: 8

## 📊 Estructura de los Archivos JSON
```json
{
  "metadata": {
    "nombre_archivo": "...",
    "tipo_documento": "...",
    "numero_decreto": "...",
    "fecha_publicacion": "...",
    "diario_oficial": "...",
    "jurisdiccion": "El Salvador",
    "idioma": "es",
    "encoding": "UTF-8"
  },
  "contenido": {
    "titulos": [
      {
        "numero": "I",
        "nombre": "...",
        "capitulos": [
          {
            "numero": "I",
            "nombre": "...",
            "articulos": [
              {
                "numero": "1",
                "titulo": "...",
                "contenido": "..."
              }
            ]
          }
        ]
      }
    ]
  }
}
```

## 🔍 Uso

Los archivos JSON pueden ser usados para:
- Búsqueda y análisis de textos legales
- Aplicaciones de consulta legal
- Sistemas de gestión documental
- Investigación y análisis de datos

## 📝 Codificación

Todos los archivos están codificados en **UTF-8** para garantizar la correcta visualización de caracteres especiales del español (tildes, eñes, etc.).

## 📅 Fecha de Generación

Generado el: 2025-11-25 22:10:01

## ⚖️ Fuente

Documentos oficiales de la República de El Salvador.

## 📜 Licencia

Los documentos legales son de dominio público. Esta estructuración en JSON está disponible para uso libre.
