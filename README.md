# Simon Memory Game on FPGA (Altera DE0, Quartus)

Designed and implemented an interactive Simon memory game on an Altera DE0 FPGA board using Quartus. The game includes multiple timed stages where players replicate LED light sequences by toggling switches. Features include state saving between rounds, pause functionality between stages, and real-time tracking of the highest score achieved. Built using finite state machines, counters, and real-time I/O control, demonstrating a solid grasp of digital logic, timing constraints, and embedded system design.

---

## 🧠 Game Features
- Multi-stage memory game with increasing difficulty
- LED sequence generation
- Switch-based player input
- Pause between stages
- Score memory with highest score tracking
- State saving between levels

---

## ⚙️ Tools & Platform
- **Quartus Prime**
- **Altera DE0 FPGA Board**
- Schematic/Block Design (no HDL code)

---

## 📁 Project Files
- `the_real_final_project.qar` – Quartus archive file  
  > Contains the full FPGA design, including logic blocks, timing constraints, and project configuration.  
  > Open using Quartus: `Project > Restore Archived Project (.qar)`

---

## 🚀 Getting Started
1. Open Quartus Prime
2. Go to `Project > Restore Archived Project`
3. Select `the_real_final_project.qar`
4. Compile the project and program the DE0 board using USB-Blaster

