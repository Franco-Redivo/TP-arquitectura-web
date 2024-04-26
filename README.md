# TP-arquitectura-web

## Nombre del negocio: MovieList

## Descripcion del negocio:
MovieList es una plataforma para ver información sobre películas y armar listas con el fin de mantener un registro de todas las que ya viste y las que planeas ver. Te permite darle una calificación a las películas y escribir reseñas para postear en la plataforma. Además podés compartir tus listas y armar discusiones con otros usuarios.

## Entidades principales:
1. Usuarios
2. Películas
3. Listas 

## Servicios:
- **Crud de usuarios**: Registrar, eliminar y modificar usuarios
- **Crud de peliculas**: Crear, eliminar y modificar películas
- **Exploracion del contenido**: Permite a los usuarios explorar películas disponibles.
- **Creacion de listas**: Permite a los usuarios crear listas de películas que planean ver o que ya vieron.
- **Recomendaciones personalizadas**: Sugiere contenido basado en el historial de visualización y las preferencias del usuario.
- **Detalle de contenido**: Proporciona información detallada sobre una película específica (genero , elenco ,plataforma en donde se encuentra, etc).

## Endpoints:
### Usuarios:
- /usuarios
- /usuarios/{id}
### Peliculas:
- /peliculas
- /peliculas/{id}
### Listas:
- /listas
- /listas/{id}
### Exploracion contenido:
- /exploracion-peliculas
### Creacion listas:
- /usuarios/{usuario_id}/listas
### Recomendaciones:
- /usuarios/{usuario_id}/recomendaciones
### Detalle de contenido:
- /peliculas/{id}/detalle

