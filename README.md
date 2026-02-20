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
  - Everything should have a user interface, even if it's only a CLI, but everything should have some kind of GUI, TUI, or CLI that can be used to configure intuitively configurable features in production, in real time.
  - If configurable features have customer or reputational impact that requires four or more eyes, build an authorisation queue into your UI, so that business users can make the changes they need from the UI, and authorise from the UI, in real time.   
  - Only new features should require logging projects. Existing features with obvious variability should be variable from the front end, in real time.
  - 
  - **Example User Workflow Experience:**
    
    - 🟢 **Correct Workflow:**
      
      1. [09:00] Business Meeting:
         - We need to change the pricing on this or that product, and change the currency format shown to customers.
           
      2. [09:30] After the Meeting:
         - Product manager logs into the application.
         - Navigates to `products -> pricing`.
         - Changes the pricing as discussed in the meeting.
         - Presses the "Apply" button.
         - Shouts across the table to the product owner, to please log in and approve the pricing change that was just discussed in the meeting.
        
      3. [09:35]
         - Product owner quickly logs in, views their authorization queue, clicks on the change, and presses the "Approve" button.
        
      4. [09:36]
         - New pricing is reflected in production.
            
    - 🔴 **Incorrect Workflow**

      1. [Day-1 09:00] Business Meeting:
         - We need to change the pricing on this or that product, and change the currency format shown to customers.
           
      2. [Day-1 09:30] After the Meeting:
         - Product manager updates the "Product Pricing" Excel spreadsheet.
         - Sends the Excel spreadsheet to the project manager via e-mail, asking if the IT team can import the spreadsheet into production.

      3. [Day-1 10:00] After PM's Next Meeting:
         - Reads e-mail, and logs a request with the IT team to import the pricing spreadsheet.
         - Sends and e-mail to the business and IT team to let everyone know there is a new workrequest that has been logged to import the processing spreadsheet.
        
      4. [Day-2 10:00] IT Standup:
         - Tech Lead: "The business team has asked us to import the new pricing. Who can do it?.
         - Junior Dev: "I'll have capacity tomorrow after the bug fixes today."
        
      5. [Day-3 09:00]
         - Tries to import the Excel spreadsheet into their dev environment to test.
         - Import breaks.
         - Tries to fix it. But no luck.

      6. [Day-3 10:00] IT Standup:
         - Junior Dev: "The import didn't work".
         - Senior Dev: "I'll take a look. Send me the spreadsheet."
        
      7. [Day-3 14:00] After Lunch:
         - Senior dev tries the import on their local machine. Notices that the business team added a new column to the pricing spreadsheet, which breaks the import.
         - Fixes the import and promotes to integration testing.
        
      8. [Day-4 10:00] IT Standup
         - Test Lead: "We see there's a new pricing import. But we never got notified, and the test cut-off for this iteration was on Friday last week. We can add testing to the next iteration.
        
      9. [Week-2 (Sunday 04:00)] Iteration Release Day:
         - New pricing goes live, no issues.
        
      10. [Week-2 (Monday 09:00)] Business Meeting:
          - Product Owner: "Remember that pricing update we asked IT to do for us two weeks ago? Well, the marketing team are doign a campaign, and they asked if we can reduce the pricing by 50% from now to the end of the week."
         
    
 
- **Reporting is a main feature, not an afterthought**
  - Your UI should have some kind of dashboard that shows obvious stats the business users need. *Even* if your UI is a CLI, then, `--stats`. 
  - Sure, you can build fancy PowerBI dashboards and other reporting solutions later, but the base application should ship with a minimal dashboard that the business users can access from the front end.
  - Aside from the value this offers your business users out of the box, it encourages one to design their application data structure in a way that can be reported on, with out system level entity names and abbreviations making their way up to the business users. 
  

<details>
<summary>Random Facts</summary>

- NAUI certified free diver
- Sky Diver
- Former Freestyle BMX Flatland show rider.
- Former Gymnast
- Former Trapeze artist

</details>
