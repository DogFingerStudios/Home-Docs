Let’s evaluate whether your horror game—set in the 1940s Qusqui-Paris, with a 20-story Torre-Casa de Runa under siege by the Sombra-Qhari Guerrillas—is too much for you to program solo. As a professional programmer with 25 years of experience in C++ and C#, specializing in backend high-performance systems, you bring a strong skill set to the table. I’ll break this down by scope, technical demands, your expertise, and realistic timelines, while considering the game’s features: survival horror mechanics, permadeath, multiple endings (rooftop rescue or kill-all), a 20-floor tower, and cultural elements.

---

### Game Scope Overview
- **Core Features**:
  - 20-floor tower with distinct floors (e.g., Ground Floor with sandbags, Floor 15 with the Tumi-Lumière, Roof signal point).
  - Survival mechanics: stealth, combat, escape routes (stairs, vents, fire escape).
  - Permadeath: player can die at any time, triggering game over.
  - Two victory conditions: signal helicopter on the roof or kill 15-20 Sombra-Qhari guards.
  - Family dynamics: 5 members (player, Qori, Pachacuti, Kusi-Rose, Túpac) with roles (e.g., Pachacuti’s pututu horn for signaling).
  - Multiple endings (5 outlined: Rooftop Liberation, Rooftop Trap, Last Stand Victory, Heroic Sacrifice, Total Defeat).
- **Cultural Elements**:
  - Quechua-French naming and lore (e.g., Inti-Raymi Rébellion, Inti-Tahuantinsuyo ideology).
  - WWII-inspired aesthetics: sandbags, old radios, rationed food.
- **Technical Requirements**:
  - 3D environment (Unity or Unreal Engine, likely in C# or C++).
  - AI for Sombra-Qhari guards (patrol, chase, combat).
  - Physics for interactions (barricades, Molotovs, vent crawling).
  - Audio (pututu horn, enemy shouts, ambient sounds like air-raid sirens).
  - UI for inventory, family status, and choices.

---

### Your Expertise
- **Strengths**:
  - **25 Years in C++ and C#**: You’re fluent in the languages most game engines use (C# for Unity, C++ for Unreal). This is a huge advantage for coding gameplay mechanics, AI, and physics.
  - **Backend High-Performance Systems**: Your experience optimizing performance means you can handle the tower’s 20 floors, AI pathfinding (e.g., NavMesh for guards), and real-time systems (e.g., permadeath checks, timer for helicopter signal) without major bottlenecks.
  - **Professional Experience**: You likely have strong project management skills, debugging expertise, and the ability to architect a complex system (e.g., state machines for enemy behavior, event systems for family interactions).
- **Potential Gaps**:
  - **Game Development Specifics**: Backend systems differ from games—you may have less experience with 3D rendering, animation, or audio integration. However, your programming chops mean you can learn these quickly.
  - **Art and Assets**: You’ve already planned to buy a modeled apartment building and hire someone for tweaks, which offsets your lack of 3D modeling skills.
  - **Solo Workload**: Games require coding, design, testing, and polish across multiple domains (audio, visuals, gameplay). Your experience helps, but the sheer volume of tasks can be daunting.

---

### Technical Feasibility for One Person
- **Engine Choice**:
  - **Unity (C#)**: Your C# expertise makes Unity a natural fit. It’s beginner-friendly, has a massive asset store (e.g., free WWII props, audio packs), and handles 3D well for a small-scale project like this. X posts often recommend Unity for solo devs due to its community support and tutorials.
  - **Unreal (C++)**: Unreal’s also viable with your C++ background, offering better visuals out of the box (e.g., for gritty WWII lighting), but it has a steeper learning curve for solo devs and less free content.
  - **Verdict**: Unity’s likely your best bet for speed and ease, given your C# experience and the project’s scope.

- **Coding Complexity**:
  - **Tower Layout**: 20 floors, but most can be modular (e.g., reuse apartment layouts with variations like bloodstains or sandbags). You can script floor generation with randomization (e.g., spawn 2-3 guards per floor, scatter props), which your backend experience makes manageable.
  - **AI**: Sombra-Qhari guards need patrol routes, chase behavior, and combat. Unity’s NavMesh and state machines (e.g., patrol → alert → attack) are straightforward to implement. Your performance background ensures you can optimize pathfinding for 15-20 guards.
  - **Mechanics**: Stealth (line-of-sight checks), combat (basic melee/ranged), and permadeath (health system with instant game-over) are all within your wheelhouse. Backend experience helps with event systems (e.g., Pachacuti’s pututu triggering a distraction).
  - **Endings**: Multiple endings (5) require a state tracker (e.g., family survival, guards killed, timer for helicopter). This is similar to backend state management—easy for you to code.
  - **Family Dynamics**: Each member’s role (e.g., Kusi-Rose in vents, Túpac fighting) can be scripted as abilities with cooldowns or conditions. Your C# skills make this a breeze.

- **Assets and Art**:
  - You’re outsourcing the tower model and tweaks, which saves time. Unity Asset Store offers free/low-cost WWII props (e.g., sandbags, radios) and character models (e.g., for Sombra-Qhari). Audio like pututu sounds or air-raid sirens can be sourced from freesound.org.
  - Your backend focus means you might struggle with animation (e.g., guard walk cycles, family reactions), but pre-made animation packs (e.g., Mixamo) can fill the gap.

- **Challenges**:
  - **Scope Creep**: 20 floors, 15-20 guards, and 5 endings sound manageable, but polish (e.g., bug-free AI, balanced difficulty) takes time. Your experience helps, but solo testing is slow.
  - **Audio/Visual Integration**: Syncing sounds (e.g., pututu horn) or visuals (e.g., Molotov fire effects) might be new territory. Unity’s documentation and tutorials (e.g., Brackeys on YouTube) can bridge this gap.
  - **Time Sink**: Even with your skills, games require iteration—playtesting, tweaking, and debugging across 20 floors can balloon.

---

### Time Estimate for Solo Development
- **Prototype (1-2 Months)**:
  - Basic tower (5 floors, placeholder assets): 1-2 weeks.
  - Core mechanics (stealth, combat, permadeath): 2-3 weeks.
  - Simple AI (patrol, chase): 1-2 weeks.
  - One ending (rooftop signal): 1 week.
- **Full Game (6-12 Months)**:
  - Full 20 floors (modular, detailed): 1-2 months.
  - Advanced AI (combat, group tactics): 1 month.
  - Family mechanics (e.g., Pachacuti’s pututu, Kusi-Rose in vents): 1 month.
  - All endings (5 total): 1 month.
  - Polish (audio, visuals, UI, bug fixes): 2-3 months.
  - Playtesting and balancing: 1-2 months.
- **Total**: 6-12 months for a polished game, assuming 10-20 hours/week (part-time). Your experience might lean toward the lower end (6-8 months) if you scope tightly.

---

### Is It Too Much for One Person?
- **Yes, It’s Doable—With Your Skills**:
  - Your 25 years in C++ and C#, plus high-performance backend experience, make the coding side very achievable. You can handle the tower’s systems (e.g., floor generation, AI, state tracking) efficiently.
  - Outsourcing the tower model and tweaks offsets your lack of 3D art skills, and Unity’s ecosystem (free assets, tutorials) fills other gaps (e.g., animations, audio).
  - The scope (20 floors, 15-20 enemies, 5 endings) is reasonable for a solo dev if you use modular design (e.g., reuse floor layouts, enemy behaviors) and keep visuals simple (e.g., low-poly assets).

- **Challenges to Watch**:
  - **Burnout**: Solo dev work is grueling—coding, testing, and polishing alone can lead to fatigue. Your experience helps, but pace yourself (e.g., prototype first, then expand).
  - **Non-Coding Tasks**: Audio-visual integration, UI design, and playtesting might slow you down. Leverage pre-made assets and focus on gameplay over polish initially.
  - **Scope Management**: 20 floors and 5 endings risk ballooning. Start small (e.g., 5 floors, 2 endings), then scale up once the core loop (stealth, combat, permadeath) feels solid.

- **Community Insights**:
  - X posts and indie dev forums (e.g., Reddit’s r/gamedev) often cite solo projects like *Stardew Valley* (Eric Barone, 4 years) or *Papers, Please* (Lucas Pope, 9 months) as proof it’s possible—but those devs had art skills. Your coding expertise and outsourcing plan balance this out.
  - A common tip: focus on a Minimum Viable Product (MVP)—e.g., 5 floors, 1 ending, basic AI—then iterate. Your backend skills make the MVP phase faster.

---

### Recommendations
1. **Start with a Prototype**:
   - Build Floors 1, 5, 9, 15, and Roof.
   - Script basic AI (patrol, chase), stealth (line-of-sight), and 1 ending (Rooftop Liberation).
   - Use placeholder assets (e.g., Unity’s default cubes) until your tower model arrives.
   - Aim for 1-2 months to prove the concept.

2. **Leverage Your Strengths**:
   - Optimize early (e.g., efficient AI pathfinding, lightweight floor loading) to handle 20 floors smoothly.
   - Use C# in Unity to script mechanics quickly—your experience shines here.

3. **Outsource and Automate**:
   - Stick to your plan of buying the tower model and hiring for tweaks.
   - Use free tools like Mixamo for animations and freesound.org for audio (e.g., pututu horn, air-raid sirens).

4. **Scope Tightly**:
   - Cap initial enemy count at 10 (scale to 15-20 later).
   - Start with 3 endings (Rooftop Liberation, Last Stand Victory, Total Defeat), then add the others.
   - Reuse assets (e.g., same Sombra-Qhari model with color variations).

---

### Conclusion
With your 25 years of C++ and C# experience, specializing in high-performance systems, this game is **absolutely achievable** for you as a solo programmer. It’s not too much, but it’ll take discipline to manage scope and avoid burnout. A 6-12 month timeline for a polished game is realistic, especially since you’re outsourcing art. Your backend expertise ensures the technical side (e.g., AI, permadeath, state tracking) will be solid, and Unity’s ecosystem can handle the rest.

If you focus on an MVP first and iterate, you’ll have a playable game in 1-2 months, which you can then expand. Want to break down a specific mechanic (e.g., AI coding) or timeline further?