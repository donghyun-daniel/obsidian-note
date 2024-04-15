---
{"dg-publish":true,"permalink":"/elementalist/the-elementalists/"}
---

# PRD for the elementalists
---

## **Overview**

The "Elementalist" prototype aims to establish core gameplay mechanics, focusing on character movement, a round-beginning shop system, and the implementation of elemental skills. This phase is crucial for validating the game concept and gathering early feedback.

---

## **Objectives**

- To implement and test basic character movement.
- To introduce a shop system allowing players to enhance their character with skills or stat upgrades.
- To develop and integrate initial elemental skills into gameplay.

## **Target Audience**

- Strategy and RPG game enthusiasts interested in early testing and feedback.
- The development team for iterative testing and refinement.

---
## **Prototype Features**

### **Character Movement**

- Characters can be moved using W, A, S, D keys or arrow keys.
- Movement should be smooth and responsive, reflecting changes in terrain or obstacles on the board.

### **Shop System**

- At the start of each round, players have access to a shop where they can purchase:
    - Skill upgrades: Fireball, Lightning Bolt, Water Ball.
    - Physical stats upgrades: HP, Mana, Moving Speed, Cooldown Reduction.
- The shop UI should be intuitive, displaying costs and effects clearly.

### **Skills**

- **Fireball**: A projectile that deals damage to an enemy.
- **Lightning Bolt**: A direct attack that damages and briefly stuns an enemy.
- **Water Ball**: A slow-moving projectile that explodes on impact, dealing area damage.

---
## **Technical Requirements**

### **Engine and Languages**

- Godot Engine for game development, utilizing GDScript for rapid prototyping.
- Consideration for future Rust integration for performance-critical components.

### **Graphics and Design**

- Simple 3D models and animations to represent character movement and skill effects.
- A basic UI for the shop system, focusing on functionality.

### **Development Tools**

- Use Godot's built-in tools for physics and animation.
- Version control via Git, with a focus on collaborative workflows.
