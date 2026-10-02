ROADMAP DE GAMEHUB

    1. REQUISITOS
      ↓
    2. FUNCIONALIDADES
      ↓
    3. ARQUITECTURA
      ↓
    4. DISEÑO DE BASE DE DATOS
      ↓
    5. ESTRUCTURA DEL REPOSITORIO
      ↓
    6. ENTORNO DOCKER
      ↓
    7. DESARROLLO POR SPRINTS
      ↓
    8. TESTING
      ↓
    9. DEPLOY
      ↓
    10. MANTENIMIENTO Y EVOLUCIÓN



1. 📋 Requisitos

Primero definimos qué problema queremos resolver.

Objetivo de GameHub

Crear una plataforma web que permita a los usuarios descubrir y jugar videojuegos directamente desde el navegador.

Pero aquí necesitamos profundizar.

Tenemos que definir:

Usuarios
Visitante
    ↓
Usuario registrado
    ↓
Administrador
Preguntas que debemos responder

Por ejemplo:

¿Los juegos serán gratuitos? -> No, empezaremos con un juego definido el cual mientras mas sumenmos puntos nos va a dar coins para poder desbloquear nuevos juegos
¿Será necesario registrarse para jugar? -> Si seria importante registrarse para poder jugar
¿Los usuarios podrán guardar puntuaciones? -> Si, pero no sabria como hacer para que los juegos que jueguen guarden las puntuaciones
¿Habrá rankings? -> Eso lo miraremos en un futuro
¿Habrá comentarios? -> No, eso solo fomentaria el cyberbulling 
¿Habrá favoritos? -> Si, Podran colocarlos como favoritos
¿Habrá categorías? -> Si
¿Quién puede agregar juegos? -> La comunidad podra ir agregando sus juegos.
¿GameHub tendrá juegos propios, juegos externos o ambos? -> Desearia que fuera de todo, pero no sabria como encontrar las apis para los juegos esternos
¿Habrá publicidad en el futuro? -> Tal vez
¿Será únicamente web? -> El sentido es una plataforma de juegos, tal vez algun dia transformemos gamehub en un tipo de steam
¿Queremos que sea responsive para móvil? -> No, el movile es algo en lo que no me quiero meter
  


Etonces nuestro MVP debería ser mucho más pequeño

Yo propondría que GameHub v1 tenga solamente:

Usuario
Registro
Login
Logout
Perfil

Juegos
Catálogo
Categorías
Información del juego
Jugar
Favoritos

Gamificación
Puntuaciones
Coins
Juegos bloqueados/desbloqueados

Comunidad
Propuesta de juegos

Administración
Aprobar/rechazar juegos
Gestionar juegos
Gestionar categorías




GAMEHUB — Requisitos v1.0

1. Descripción del producto
2. Objetivos
3. Actores
4. Alcance
5. Requisitos funcionales
6. Requisitos no funcionales
7. Reglas del sistema
8. Sistema de Coins
9. Sistema de puntuaciones
10. Gestión de juegos
11. Roles y permisos
12. MVP
13. Funcionalidades futuras
14. Criterios de aceptación

Y después de ese documento pasamos a:

REQUISITOS
     ↓
CASOS DE USO
     ↓
ARQUITECTURA
     ↓
BASE DE DATOS
     ↓
API
     ↓
REPOSITORIO
     ↓
DOCKER
     ↓
SPRINT 1