# 🎮 Bomberman en Java

![Java](https://img.shields.io/badge/Java-17+-orange)
![GUI](https://img.shields.io/badge/GUI-Java%20Swing-blue)
![Architecture](https://img.shields.io/badge/Architecture-Game%20Loop-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

Implementación 2D del clásico **Bomberman**, desarrollada en Java aplicando principios de **Programación Orientada a Objetos (POO)** y una arquitectura basada en **game loop**.

---

## 📌 Descripción del Proyecto

Este proyecto consiste en una versión funcional del juego Bomberman desarrollada completamente en Java.

El jugador se desplaza a través de un mapa compuesto por bloques destructibles e indestructibles, coloca bombas estratégicamente y elimina enemigos para avanzar de nivel. Cada bomba posee un temporizador y genera una explosión con un radio determinado capaz de destruir obstáculos y eliminar enemigos dentro de su alcance.

El objetivo principal del proyecto fue reforzar conocimientos en:

- Programación Orientada a Objetos
- Arquitectura de videojuegos 2D
- Detección de colisiones
- Manejo de eventos de teclado
- Organización modular de proyectos en Java
- Implementación de un ciclo principal de juego (Game Loop)

---

## 🚀 Características Principales

- 🔹 Movimiento del jugador en cuatro direcciones
- 💣 Sistema de bombas con temporizador
- 🔥 Cálculo dinámico del radio de explosión
- 👾 Enemigos con movimiento automático
- 🧱 Bloques destructibles e indestructibles
- ⭐ Sistema de power-ups
- 🏆 Ranking de jugadores
- 🎮 Motor del juego que controla el ciclo principal (Game Loop)
- 🖥️ Interfaz gráfica desarrollada con Java Swing

---

## 🛠️ Tecnologías Utilizadas

- **Lenguaje:** Java
- **Interfaz gráfica:** Java Swing
- **Paradigma:** Programación Orientada a Objetos
- **Arquitectura:** Game Loop Pattern

---

## 🧠 Arquitectura del Proyecto

El proyecto está organizado en paquetes y clases con responsabilidades bien definidas siguiendo principios de separación de responsabilidades.

### Clases principales:

- **Player** → Controla el movimiento y estado del jugador.
- **Enemy** → Gestiona la lógica y comportamiento de los enemigos.
- **Bomb** → Administra el ciclo de vida de las bombas.
- **Explosion** → Calcula y renderiza las explosiones.
- **Engine** → Controla el ciclo principal del juego (game loop).
- **AbstractCharacter** → Clase base que encapsula lógica común reutilizable.

Esta estructura permite mantener el código modular, extensible y escalable.

---

## ▶️ Cómo Ejecutar el Proyecto

1️⃣ Clonar el repositorio:

```bash
git clone https://github.com/TU_USUARIO/bomberman-java.git

