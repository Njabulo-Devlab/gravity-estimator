# gravity-estimator
Altitude-aware multi-planet gravity and weight estimation software
# Altitude-Aware Multi-Planet Gravity Estimator

Overview
This project is a Java-based software system that calculates gravitational acceleration
and object weight as a function of altitude above a planetary surface.

Unlike basic gravity calculators, this system:
- accounts for altitude-dependent gravity
- supports multiple planets (Earth, Moon, Mars)
- allows custom user-defined planets
- validates inputs for physical correctness

The project is designed to be beginner-friendly while remaining physically accurate
and extensible for aerospace and space-related applications.

---

 Physics Model
Gravity at altitude is computed using:

g(h) = g₀ ( R / (R + h) )²

Where:
- g₀ is surface gravity
- R is planet radius
- h is altitude above the surface

Weight is computed as:
W = m × g(h)

---

Project Structure 
GravityEstimator/
├── Planet.java
├── GravityCalculator.java
├── UserInput.java
└── Main.java


---

 ▶️ How to Run
1. Clone the repository
2. Compile all `.java` files
3. Run `Main.java`
4. Follow the console prompts

---

 🌍 Applications
- Physics and engineering education
- High-altitude analysis
- Space science simulations
- Early-stage aerospace mission planning
- Foundation for air-launch trajectory software

---

## 🔮 Future Improvements
- JavaFX graphical interface
- File export and logging
- Integration with aircraft altitude scenarios
- Extension to launch and detachment physics

---

## 👤 Author
Njabulo – BSc Physics & Computer Science student


