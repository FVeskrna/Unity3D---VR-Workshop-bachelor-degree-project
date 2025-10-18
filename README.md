# VR-Workshop
VR Workshop – Virtual Reality Application

The VR Workshop is an interactive virtual reality simulation designed to recreate the environment and functionality of a home workshop. It was developed in Unity as part of the bachelor’s thesis “Design of a VR Workshop” at Brno University of Technology. The application serves as a comprehensive demonstration of user interaction, physics-based simulation, and virtual prototyping in an immersive 3D space.

Application Description

Upon launching the application and entering the VR environment, the user finds themselves standing in a realistically modeled workshop. The virtual space includes various static elements such as walls, tables, and storage, as well as interactive tools and materials placed throughout the room.

The user can freely move around the workshop using the Oculus Rift S controllers and interact with objects through natural hand movements. The system supports 6 degrees of freedom, allowing both translational and rotational motion tracking.

Objects can be picked up, moved, rotated, or dropped anywhere in the scene using the XR Interaction Toolkit’s grab system. Selected tools, such as a drill, hammer, or nail gun, feature realistic behavior and sound effects that closely mimic their real-world counterparts. For example, the nail gun can fire virtual nails into materials, while the drill allows screws to be driven into place.

One of the core interactive systems in the application is the material assembly mechanism. Users can connect wooden or metallic components together using nails or screws, which then behave as a single rigid structure through a custom parenting system. Each connection dynamically updates the physical properties of the assembled object, allowing it to respond naturally to gravity and collisions.

A notable feature is the integrated Blueprint System, which introduces guided construction tasks. When activated via the in-world user interface, it spawns semi-transparent outlines (blueprints) of predefined models such as a chair or a simple wheeled robot. The user’s task is to locate and attach the correct materials in the correct sockets, effectively “building” the object step by step. Once completed, the structure becomes a functional physical model within the scene—for example, the assembled robot can begin moving autonomously between defined points.

Additional interactive systems include:

A table saw capable of cutting virtual objects using the open-source EzySlice framework.

A vise for securing components.

A user interface panel projected within the VR environment, accessible through a laser pointer for navigating instructions and spawning materials.

Educational and Research Purpose

The application was created to explore user interaction design and object manipulation in virtual reality. It demonstrates the use of modern Unity XR tools and C# scripting for implementing realistic physical behavior, interactivity, and modular design patterns. Beyond academic purposes, the system can serve as a foundation for training simulations, assembly visualization, or interactive educational environments in engineering and manufacturing contexts.

Technical Summary

Engine: Unity 2019.4 (LTS)

Language: C#

Platform: Oculus Rift S (adaptable to other headsets supporting XR Interaction Toolkit)

Core Technologies: XR Interaction Toolkit, Oculus SDK, ProBuilder, ProGrids, EzySlice

Key Components: XR Rig, Offset Grab System, Object Spawner, Blueprint Assembly System, Interactive Tools


https://www.vut.cz/en/students/final-thesis/detail/132854

Demonstration videos:
Overall presentation:
https://www.youtube.com/watch?v=mCSK3DLpQEs

Blueprint system: https://www.youtube.com/watch?v=9GYik95y-_8

Table saw and interactables: https://www.youtube.com/watch?v=3f_6qNRiwsQ

Material assembly: https://www.youtube.com/watch?v=LREtUKK41Nk

Guided completion: https://www.youtube.com/watch?v=uxSaMIw7nYI
