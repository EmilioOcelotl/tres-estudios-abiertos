
# Cuarto semestre

Estructura de la carpeta de este semestre:

- Escritura.- Tiene los avances del índice y antecedentes
- Lecturas.- Apuntes sobre las lecturas que he realizado
- anti.- Aspectos específicos del primer capítulo que podrían funcionar como una artículo.  

## Avances 

- Índice tentativo 
- Antecedentes ( añadidos y expandidos ) 
- Primeros textos sobre anti
- Ideas generales que están presentes en las piezas presentadas 
- No cuajaron algunos proyectos vinculados con la investigación > ecosistema e interfaz quedan pendientes. Incluso podrían estar difuminados en los casos
- Delimitación inicial de la siguiente pieza y la posibilidad de ponerla en marcha en colaboración con otras instituciones 
- Inicio de escritura del planteamiento del proyecto del segundo caso. La documentación quedaría pendiente para el siguiente semestre 
- Diseño editorial y organización 

## Preguntas

- ¿ Será relevante hablar extensamente de piezas cercanas de otras personas ?
  - Casos en antecedentes y en el contexto de anti 
- Uso de otros recursos (páginas, imágenes videos) y cómo eso se puede integrar en una versión compilada para la web de la tesis 

## Pendientes

- [ ] Índice como si fuera un diagrama > Idealmente algo interactivo, representación de información en el espacio tridimensional  
- [ ] Lecturas
- [ ] Una especie de metodología
- [ ] Estudiar webRTC (posible punto en común con anti) > https://webrtc.org/getting-started/overview
- [ ] Imágenes y otros recursos > ¿ imágenes como hipervínculos en latex?
- [ ] Hacer un mapa local de recursos relevantes 
- [ ] Portada
- [ ] Errores en los hipervínculos del índice 
- [ ] Glosario 
- [ ] Arreglar bibtex para que  no arroje errores 

## Compilaciones

Para compilar glosario

`makeglossaries nombre`

Para compilar todo lo necesario, primero es necesario ir a la carpeta del tex principal, luego: 

`pdflatex tresEstudiosAbiertos && bibtex tresEstudiosAbiertos && makeglossaries tresEstudiosAbiertos && pdflatex tresEstudiosAbiertos`

## Referencias

- https://tex.stackexchange.com/questions/54927/how-to-insert-an-image-that-also-acts-as-a-link
- https://tex.stackexchange.com/questions/192378/list-of-glossaries-not-displaying


