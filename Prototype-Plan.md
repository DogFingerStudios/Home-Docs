## 🎯 **Prototype Goals**

- ✅ Establish basic player movement (FPS + 3rd person toggle).
- ✅ Build a small portion of the tower (Ground Floor + 9th Floor + Roof).
- ✅ Implement basic AI (patrol, chase, attack).
- ✅ Create initial stealth and combat mechanics.
- ✅ Set up family NPCs with basic interaction and survival dynamics.
- ✅ Establish basic ending conditions (reach the roof or kill all guards).

---

## 🏗️ **1. Foundation & Scene Setup**

1. **Create a New Unity Project**

   - Set up a 3D scene with default lighting.
   - Import basic player model, camera, and controller.

2. **Create Test Tower Layout**

   - Build 3 floors for testing:
     - **Ground Floor** – Sandbags, entry points, 1-2 guards.
     - **9th Floor** – Player apartment, family interaction.
     - **Roof** – Flare signal point.
   - Use Unity’s ProBuilder or place modular building assets for floors.

3. **Lighting and Atmosphere**

   - Use dim lighting for a tense, war-torn atmosphere.
   - Add ambient sounds (distant gunfire, footsteps).

---

## 🎮 **2. Player & Camera Setup**

1. **FPS and 3rd Person Controller**

   - Attach a `CharacterController` to the player model.
   - Implement basic movement (WASD) + mouse look.
   - Include jump and crouch.
   - Implement toggle for first-person ↔ third-person.

2. **Smooth Camera Transitions**

   - Use `Lerp` or `SmoothDamp` for smooth camera switching.
   - Handle field of view changes between POVs.

---

## 👹 **3. AI and Enemy Mechanics**

1. **Basic AI States**

   - **Patrol** → Set up NavMesh-based movement.
   - **Alert** → AI reacts to noise or sight.
   - **Chase** → AI moves toward player when alerted.
   - **Attack** → Simple attack animation or damage function.

2. **Stealth Mechanics**

   - Add raycast for AI vision detection.
   - Implement line-of-sight checks.
   - Create “detection meter” UI element.

---

## 🏃 **4. Survival and Combat**

1. **Weapons**

   - Add one weapon (knife or Molotov) for testing.
   - Implement hit detection with simple damage calculation.

2. **Noise Distraction**

   - Allow player to create noise (e.g., blow a whistle).
   - AI reacts to noise → shifts to “alert” state.

---

## 👨‍👩‍👧‍👦 **5. Family Dynamics**

1. **Family AI**

   - Set up Pachacuti (son) to follow player.
   - Allow him to blow a pututu to distract enemies.

2. **Unique Abilities**

   - Kusi-Rose (daughter) can crawl through vents.
   - Túpac (grandfather) can fight back or assist in combat.

3. **Permadeath System**

   - If a family member dies → permanent loss + consequences.

---

## 🏆 **6. Victory and Failure Conditions**

1. **Victory (Signal the Helicopter)**

   - Trigger success state when flare is fired on the roof.

2. **Victory (Kill All Guards)**

   - Track number of guards.
   - If all are dead → victory state.

3. **Failure (Permadeath)**

   - If player or key family members die → game over.

4. **Failure (Caught by AI)**

   - If the player is caught → game over.

---

## 🎯 **7. UI and Feedback**

1. **Health Bar**
   - Add a simple health bar for player and family.
2. **Detection Meter**
   - Show how close AI is to detecting the player.
3. **Ammo/Inventory UI**
   - Basic inventory UI for tracking supplies.

---

## 🔥 **8. Playtesting and Refinement**

1. Test the following:
   - Stealth effectiveness (vision, noise).
   - AI behavior (patrol, chase, attack).
   - Combat feedback (damage, hit detection).
2. Adjust AI difficulty and family behavior based on feedback.

---

## ⏳ **Estimated Time for Prototype**

| Phase            | Time Estimate |
| ---------------- | ------------- |
| Scene Setup      | 3–4 days      |
| Player & Camera  | 2–3 days      |
| AI & Stealth     | 4–5 days      |
| Combat           | 3–4 days      |
| Family AI        | 3–4 days      |
| Endgame Triggers | 2–3 days      |
| UI & Testing     | 3–4 days      |
| **Total**        | \~3–4 weeks   |

---

## ✅ **Why This Plan Works:**

✔️ Focuses on core mechanics first.\
✔️ Prioritizes functional AI and stealth over polish.\
✔️ Keeps family interaction and permadeath simple initially.\
✔️ Provides a testable “vertical slice” in \~3–4 weeks.

---

### 🚀 **Next Steps:**

1. Start with **player controller and AI** → Get basic movement and stealth working.
2. Add **family AI** and **combat** → Keep initial fights simple.
3. Layer in environmental elements and polish **after** the core loop works
