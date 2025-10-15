# C++ Object Oriented Snake Game

## Project Overview
A complete C++ Object-Oriented Design implementation of the classic Snake game, developed for McMaster University's COMP ENG 2SH4 course. This project demonstrates advanced OOD principles including composition, encapsulation, and dynamic memory management while delivering a fully functional gaming experience.

---

## System Architecture

### Core Components
- **Game Engine:** Custom game loop with real-time input processing and rendering
- **Player Class:** Snake entity with state machine-based movement control
- **Game Mechanics:** Centralized game state management and rule enforcement
- **Data Structures:** Custom array list implementation for snake body management

### Key Classes & Relationships
- **`objPos`** – Fundamental position and symbol container with heap-managed coordinates
- **`objPosArrayList`** – Dynamic array implementation for efficient snake body tracking
- **`Player`** – Snake entity with FSM-based movement and collision detection
- **`GameMechs`** – Game state container managing input, scoring, and game conditions

---

## Technical Features

### Gameplay Mechanics
- **Smooth Movement:** Four-directional control with wraparound boundary logic
- **Dynamic Growth:** Snake length increases with each food consumption
- **Collision Detection:** Self-collision detection for game-over conditions
- **Randomized Food:** Procedurally generated food items avoiding snake body positions
- **Score Tracking:** Real-time score calculation based on snake length

### Object-Oriented Design Principles
- **Encapsulation:** Strict data hiding with well-defined class interfaces
- **Composition:** Player class composed with objPosArrayList for body management
- **Memory Management:** Proper implementation of Rule of Six with destructors
- **Object Interaction:** Clean separation of concerns between game entities

### Advanced C++ Features
- **Dynamic Memory Allocation:** Heap management for game objects and data structures
- **Special Member Functions:** Custom constructors, destructors, and copy semantics
- **Constant Correctness:** Proper use of const members and methods
- **Pointer Management:** Reference-based object interaction patterns

---

## Development Tools & Technologies

### Programming Environment
- **Language:** C++17 with Object-Oriented paradigms
- **IDE:** Platform-independent C++ development
- **Build System:** Custom Makefile for multi-file compilation
- **Debugging:** Comprehensive unit testing and memory leak detection

### Key Libraries & Patterns
- **Custom Array List:** Tailored container class for game object management
- **Finite State Machine:** Direction-based movement system
- **Game Loop Architecture:** Real-time input processing and rendering
- **Memory Profiling:** Heap allocation tracking and leak prevention

---

## Project Highlights

### Technical Achievements
- **Zero Memory Leaks:** Robust destructor implementation and heap management
- **Modular Design:** Easily extensible architecture for additional features
- **Performance Optimized:** Efficient list operations for real-time gameplay
- **Code Quality:** Professional-grade documentation and formatting

### Educational Value
- **OOD Mastery:** Practical application of object-oriented design patterns
- **C++ Best Practices:** Modern C++ programming techniques and idioms
- **Software Engineering:** Iterative development and testing methodologies
- **Team Collaboration:** Parallel development workflows and code integration

---

## Game Features
- Classic Snake gameplay with smooth controls
- Real-time score display and game state feedback
- Randomized food generation with collision avoidance
- Game over detection with custom exit messages
- Extensible architecture supporting bonus features

