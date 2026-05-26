# NutriSense – Digital Engineering Design Portfolio

## Project Overview
**NutriSense** is a conceptual healthcare and wellness hardware system designed to combat regional malnutrition through accessible, real-time biometric tracking. Developed as a collaborative engineering design project, the system focuses on a wearable wristband device that monitors critical electrolyte and mineral levels (Sodium, Potassium, Calcium) via sweat analysis. The captured data integrates with an advanced AI platform to deliver personalized, culturally adaptable dietary recommendations and preventative health insights.

---

## Team & Contributions
Developed by **Team B**, consisting of 4 engineering peers:
*   **Christoph Simms** – Document Controller, Gantt Chart Management, Brochure Design, Testing & Verification[cite: 1].
*   **Neev Lalith Jain** – Design Documentation, Document Formatting, Video Presentation[cite: 1].
*   **Beninayah Anderson** – Project Enforcer, Decision Matrix Analysis, Presentation Tweak[cite: 1].
*   **Sami Dawud** – Target/Financial Research, Idea Brainstorming, Testing & Verification[cite: 1].

---

## Engineering Design Process & Methodology

### 1. Population & Need Research
*   **Target Demographics:** Focused on addressing acute micronutrient deficiencies (stunting, wasting, and mineral loss) in highly vulnerable, resource-limited regions[cite: 1].
*   **Core Objective:** Bridging the gap between tracking and accessibility by providing an affordable ($<100) biometric solution localized with multilingual support[cite: 1].

### 2. Structured Ideation & AI Collaboration
*   Executed **Hybrid Brainstorming** methodologies to log independent concepts in a decentralized workspace before unifying ideas[cite: 1].
*   Leveraged **Generative AI (ChatGPT)** as a team optimization assistant to benchmark features, stress-test system constraints, map out consumer expectations, and refine concept variations like *BioBalance* and *SmartPlate*[cite: 1].
*   Utilized weighted **Decision Matrices** evaluating *Data Accuracy, User Engagement, Feasibility, Cost, and Innovation* to mathematically isolate and select the optimal design pathway[cite: 1].

### 3. Functional Decomposition & System Architecture
The device hardware architecture is segmented into clear functional subsystems[cite: 1]:
*   **Sensors & Inputs:** Non-invasive sweat bio-sensors (Na, K, Ca tracking), galvanic skin response, and environmental tracking[cite: 1].
*   **Processing & Memory:** Core microprocessing unit handling on-device data storage and local threshold analysis[cite: 1].
*   **Power Management:** Rechargeable battery cell architecture optimized for sustainability[cite: 1].
*   **Connectivity & Output:** Low-energy wireless sync to an AI Analytics platform alongside a direct user interface display[cite: 1].

---

## Technical Specifications & Test Data

| Function | Performance Criteria | Target Specification |
| :--- | :--- | :--- |
| **Mineral Detection** | Data Accuracy | Strict error margin of $\pm$ 0.1%[cite: 1] |
| **Accessibility** | Usability Range | Complete multilingual software localization[cite: 1] |
| **Economic Viability** | Affordability | Target manufacturing/retail cost under $100[cite: 1] |

### Simulated Prototyping Data
The project included mapping mathematical models to monitor cumulative electrolyte loss over time[cite: 1]. Sweating simulation tests validated the system's ability to calculate dynamic metrics[cite: 1]:
*   **Monitored Variables:** Rate of interval volume ($L$), cumulative milligrams lost ($\text{mg}$), and threshold triggers[cite: 1].
*   **System Response:** Automates contextual alerts, identifying fluid depletion stages ("Moderate Sodium Loss", "Mild Potassium Loss") and instantly mapping out targeted nutritional suggestions to correct the deficit[cite: 1].

---

## Repository Structure
```text
├── Documentation/
│   ├── NutriSense_Design_Book.pdf    # Comprehensive technical engineering notebook
│   └── Marketing_Brochure.pdf         # Product breakdown and regional deployment flyer
├── System_Architecture/
│   ├── Functional_Block_Diagram.png   # Hardware schematics and sensor inputs
│   └── Design_Sketches/               # Engineering sketches (Top, Front, Side orthographics)
└── Simulation_Data/
    └── Test_Session_Logs.csv          # 60-minute cumulative mineral loss data arrays
