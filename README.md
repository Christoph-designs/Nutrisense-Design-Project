# NutriSense – Digital Engineering Design Portfolio

## Project Overview
**NutriSense** is a conceptual healthcare and wellness hardware system designed to combat regional malnutrition through accessible, real-time biometric tracking. Developed as a collaborative engineering design project, the system focuses on a wearable wristband device that monitors critical electrolyte and mineral levels (Sodium, Potassium, Calcium) via sweat analysis. The captured data integrates with an advanced AI platform to deliver personalized, culturally adaptable dietary recommendations and preventative health insights.

---

## Team & Contributions
Developed by **Team B**, consisting of 4 engineering peers:
*   **Christoph Simms** – Document Controller, Gantt Chart Management, Brochure Design, Testing & Verification
*   **Neev Lalith Jain** – Design Documentation, Document Formatting, Video Presentation
*   **Beninayah Anderson** – Project Enforcer, Decision Matrix Analysis, Presentation Tweak
*   **Sami Dawud** – Target/Financial Research, Idea Brainstorming, Testing & Verification

---

## Engineering Design Process & Methodology

### 1. Population & Need Research
*   **Target Demographics:** Focused on addressing acute micronutrient deficiencies (stunting, wasting, and mineral loss) in highly vulnerable, resource-limited regions
*   **Core Objective:** Bridging the gap between tracking and accessibility by providing an affordable biometric solution localized with multilingual support

### 2. Structured Ideation & AI Collaboration
*   Executed **Hybrid Brainstorming** methodologies to log independent concepts in a decentralized workspace before unifying ideas.
*   Leveraged **Generative AI (ChatGPT)** as a team optimization assistant to benchmark features, stress-test system constraints, map out consumer expectations, and refine concept variations like *BioBalance* and *SmartPlate*.
*   Utilized weighted **Decision Matrices** evaluating *Data Accuracy, User Engagement, Feasibility, Cost, and Innovation* to mathematically isolate and select the optimal design pathway.

### 3. Functional Decomposition & System Architecture
The device hardware architecture is segmented into clear functional subsystems:
*   **Sensors & Inputs:** Non-invasive sweat bio-sensors (Na, K, Ca tracking), galvanic skin response, and environmental tracking.
*   **Processing & Memory:** Core microprocessing unit handling on-device data storage and local threshold analysis.
*   **Power Management:** Rechargeable battery cell architecture optimized for sustainability.
*   **Connectivity & Output:** Low-energy wireless sync to an AI Analytics platform alongside a direct user interface display.

---

## Technical Specifications & Test Data

| Function | Performance Criteria | Target Specification |
| :--- | :--- | :--- |
| **Mineral Detection** | Data Accuracy | Strict error margin of $\pm$ 0.1% |
| **Accessibility** | Usability Range | Complete multilingual software localization |
| **Economic Viability** | Affordability | Target manufacturing/retail cost under $100 |

### Simulated Prototyping Data
The project included mapping mathematical models to monitor cumulative electrolyte loss over time. Sweating simulation tests validated the system's ability to calculate dynamic metrics:
*   **Monitored Variables:** Rate of interval volume ($L$), cumulative milligrams lost ($\text{mg}$), and threshold triggers.
*   **System Response:** Automates contextual alerts, identifying fluid depletion stages ("Moderate Sodium Loss", "Mild Potassium Loss") and instantly mapping out targeted nutritional suggestions to correct the deficit.

---

## Repository Structure
```text
├── Documentation/
│   ├── Nutrisense Design notebook.pdf # Comprehensive technical engineering notebook
│   └── Marketing_Brochure.pdf         # Product breakdown and regional deployment flyer
├── System_Architecture/
│   ├── Functional_Block_Diagram.png   # Hardware schematics and sensor inputs
│   └── Design_Sketches/               # Engineering sketches (Top, Front, Side orthographics)
└── Simulation_Data/
    └── Test_Session_Logs.csv          # 60-minute cumulative mineral loss data arrays
