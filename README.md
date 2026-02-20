# Rohin Gosling

🌍 **UAE - Dubai** | 🤖 **Progenitor of Adaptive Systems** | 👽 **Aficionado of trans-humanist philosophy** | 🛩️ **Extreme sports athlete**

![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white)
![Gemini CLI](https://img.shields.io/badge/Gemini_CLI-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![OpenSCAD](https://img.shields.io/badge/OpenSCAD-F5C400?style=flat-square&logo=openscad&logoColor=black)
![Commodore 64](https://img.shields.io/badge/Commodore_64-6C5EB5?style=flat-square&logo=commodore&logoColor=white)

## Production Projects

- 🏁 [HEX Grid Tessellator](https://github.com/rohingosling/hex-grid-tessellator) - Generate hexagonal grid images. Useful for transparency masks.
- 📡 [Pinger](https://github.com/rohingosling/pinger) - Like `ping`, ...but prettier, ...with CSV file exports.
- 📖 [Universal Year Planner](https://github.com/rohingosling/Year-Planner-Generator) - Universal PDF Year Planer generator. Download 2026 Year Planner PDF [here](https://github.com/rohingosling/Year-Planner-Generator/blob/main/output/year_planner.pdf).
- 🖨️ [3D Printing Models](https://github.com/rohingosling/OpenSCAD) - Parametric 3D Printing models. Including [Thingiverse - Parametric Hinge](https://www.thingiverse.com/thing:2187167)

## Research Projects

- 📐 [Parametric Function Solutions](https://github.com/rohingosling/parametric-functions) - Parametric function solutions for cubic polynomials and trigonometric functions.
- 🎲 [ECS Game Engine (Java Version)](https://github.com/rohingosling/ecs-game-engine-java) - ECS (Entity Component System) Game Engine - Java Version.
- 🤖 [OpenAI GPT Reference App (Procedural)](https://github.com/rohingosling/OpenAI-GPT-Reference-Application-1-Procedural) - Python template for writing procedural OpenAI GPT API applications.
- 🤖 [OpenAI GPT Reference App (OOP)](https://github.com/rohingosling/OpenAI-GPT-Reference-Application-2-OOP) - Python template for writing object-oriented OpenAI GPT API applications.
- 🧠 [Recurrent Neural Network (RNN)](https://github.com/rohingosling/RNN-Recurrent-Neural-Network) - RNN training algorithm experiments.
- 🧠 [Neural Network (ANN/MLP)](https://github.com/rohingosling/neural-network-cpp) - Multi-layer perceptron experiments.



## Legacy Projects

- 🐍 [Common Python Library](https://github.com/rohingosling/common-python) - Common Python library repository. Deprecated, but kept around for spare parts.
- 🍵 [Common Java Library](https://github.com/rohingosling/common-java) - Common Java library repository. Deprecated, but also kept around for spare parts.
- ⚙️ [Common C++ Library](https://github.com/rohingosling/common-cpp) - Common C++ library repository. Deprecated. More spare parts.
- 🔪 [Common C# Library](https://github.com/rohingosling/common-cs) - Common C# library repository. Deprecated. If only I could sell these spare parts.
- 📊 [Common MATLAB Library](https://github.com/rohingosling/common-matlab) - Common MATLAB library repository. Deprecated. Spare parts R us.


## Connect

- [LinkedIn](https://www.linkedin.com/in/rohingosling/)
- [X](https://x.com/rohingosling)
- [GitHub](https://github.com/rohingosling)

### Philosophy

- **Run time configurability**
  - Make everything in production configurable, through a user interface, in real time.
  - Everything should have a user interface, even if it's only a CLI, but everything should have some kind of GUI, TUI, or CLI that either the business users or customers can use to configure intuitively configurable features in production, in real time.
    - This includes backend and middleware applications.
    - **Everything**, must have a UI, so that obvious configurations can be performed through the UI, in real time, in production.
  - If configurable features have customer or reputational impact that requires four or more eyes, build an authorisation queue into your UI, so that business users can make the changes they need from the UI, and authorise from the UI, in real time.   
  - Only new features should require logging projects. Existing features with obvious variability should be variable from the front end, in real time.
  
- **Reporting is a main feature, not an afterthought**
  - Your UI should have some kind of dashboard that shows obvious stats the business users need.
    - *Even* if your UI is a CLI, then, `--stats`, or something, but make it happen.
  - Sure, you can build fancy PowerBI dashboards and other reporting solutions later, but the base application should ship with a minimal dashboard that the business users can access from the front end.
  - Aside from the value this offers your business users out of the box, it encourages one to design their application data structure in a way that can be reported on, with out system level entity names and abbreviations making their way up to the business users.
  - Application databases should be designed with reportability incorporated as a main design feature. 

- **UI-API Parity**
  - Anything a user can do through the UI, must also be possible to do programmatically via an API.
  - Anything that can be done programmatically via the API, should be possible to do through the UI.
    - System-level functions will be accessible through a "Settings" menu, for example.
  - When new UI features are added or changed, the API is updated as well, and regression testing always tests both.
  - When new API features are added or changed, the UI is updated as well, and regression testing always tests both.
 
- **Build Internal Productivity Tools**
  - A portion of teams design and development time and budget should be allocated to designing and building productivity tools for internal use.
  - For example, if you are going to adopt the "UI-API Parity" philosophy, then build a GUI tool that developers or even business analysts can use to set up the dual UI and API scaffolding for the new feature.
 
- **Build Simulators**
  - This is a special case of building productivity tools. But it's so special that it deserves its own shoutout.
  - If your system interacts with other systems, don't wait for integration testing to find out if your integration works. Instead, build a simulator that the dev team can use on their local machines while they are coding.
    - Your simulators don't need to simulate everything. But if you have a big complicated system that sends your system status updates, or something, then make a simulator that just implements the status update sending feature.
    - I remember once working on an ATM middleware product that interfaced ATMs with banking infrastructure. Someone in the team hacked together an phyiscal ATM simulator on a plank of wood. It even had a card reader that had been borrowed from NCR. This thing was ugly, but the development time it saved was invaluable.

<details>
<summary>Random Facts</summary>

- NAUI certified free diver
- Sky Diver
- Former Freestyle BMX Flatland show rider.
- Former Gymnast
- Former Trapeze artist

</details>
