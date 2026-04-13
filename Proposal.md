# TP Java Chapter One

## Integrantes

- 52961 Figueroa, Francisco Alejandro.
- 52962 Taborda, Ignacio.
- 52847 Taborda, Santiago.

## Descripción

Chapter One es una página web orientada a lectores, donde los mismos podrán buscar libros, realizar reseñas, comentarios y recomendarlos. Podrán buscar por categoría, autor o título. Los usuarios podrán unirse a un grupo de lectura donde podrán elegir un libro a leer a una determinada fecha, para luego debatir sobre el mismo.

## Modelo

![Imagen del dominio](./DER%20Chapter%20One.drawio.png)

## Requerimientos

### Regularidad

| Requerimiento    |                        Detalle/Listado de casos incluidos |
| :--------------- | --------------------------------------------------------: |
| ABMC simple      |                       Libro, Usuario, Autor, Género, Club |
| ABMC dependiente |                         Biblioteca, Saga, Post, Historial |
| CU NO-ABMC       | Añadir reseña, Lista de lectura, Recomendación de libros. |
| Listados simples |                    Listados de: autores, libros, géneros. |

### Aprobación directa

| Requerimiento                   |                                         Detalle/Listado de casos incluidos |
| :------------------------------ | -------------------------------------------------------------------------: |
| Casos de Uso Complejos          |    Usuario solicita unirse a un club de lectura. Usuario denuncia un post. |
| Listados Complejos              | Listado libros filtrado por género. Listado clubes filtrados por temática. |
| Niveles de acceso               |                              Invitado (sin cuenta), Lector, Administrador. |
| Requerimiento extra obligatorio |                     Notificar nuevo post de un club del usuario por email. |
