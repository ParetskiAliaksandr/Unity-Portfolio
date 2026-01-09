# Unity-Portfolio
Portfolio of Unity Developer Aliaksandr Paretsky: complete projects and modular systems

I'm a junior Unity developer focused on modular systems and clean architecture. Here you'll find my projects and technical work.

## Complete projects 
[ProjectName](link) | Description | [Video](link) 

### HeroicChessTactics 
###**Status:** In development  
###**Repository:** [https://github.com/ParetskiAliaksandr/HeroicChessTactics.git]
###**Genre:** Card-Based Tactics / Chess-like / Deckbuilding 
###**Tech:** Unity, C#, Zenject (Extenject), Addressables, Async/Await

### Description:
A modular and service-based scene and configuration management system designed for scalable Unity projects.
The system focuses on clean architecture, separation of concerns, and asynchronous initialization flow.

**Initialization Flow (Simplified)**
BootScene
 └─ Bootstrapper
     ├─ Load configs (Addressables)
     ├─ Load LoadScreen (Additive)
     ├─ Load MainMenu (Additive)
     └─ Unload BootScene

**Key points:**
Centralized config loading via Addressables and ScriptableObjects
Strongly-typed scene access using SceneKey enum
Bootstrap scene for async project initialization
Additive scene loading with loading screen abstraction
Thread-safe scene operations and cancellation support
Core logic implemented as plain C# services (no MonoBehaviour coupling)

**What I am learning from this project**
Through this project, I am continuously improving my understanding of Unity project architecture by building core systems as decoupled C# services using dependency injection (Zenject).
I am gaining hands-on experience with asynchronous workflows, additive scene loading, and configuration management via ScriptableObjects and Addressables. 
As the project evolves, I plan to extend these systems with more advanced scene flows, state management, and data persistence, further strengthening my skills in scalable and maintainable Unity architecture.

## Individual modules 
[ModuleName](link) — Description.

## Contacts
- GitHub: [https://github.com/ParetskiAliaksandr]
- LinkedIn: [(https://www.linkedin.com/in/aliaksandr-paretski-a22661326/)]
- Email: [paretskialiaksandr@gmail.com]
