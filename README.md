# Gestor de tareas contenerizado

## Integrantes
- Eleanyeris Hernandez
- Giseella Sanchez
- Angelina Ochoa

## Servicios
| Servicio | Tecnología | Función |
|---|---|---|
| frontend | nginx | Página web, puerto 8080 |
| api | Python 3.12 Flask | API de tareas |
| bd | MySQL 8.4 | Base de datos con volumen |

## Requisitos
- Docker Desktop abierto (Engine running)
- Git

## Cómo ejecutarlo
1. git clone https://github.com/gpsanchezr/fullstack-docker-task-manager.git
2. cd fullstack-docker-task-manager
3. Copy-Item .env.example .env
4. docker compose up -d --build
5. Abrir http://localhost:8080

## Cómo detenerlo
docker compose down
