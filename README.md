<div align="center">

<img src="./assets/hero.svg" width="100%" />

<br><br>

<img src="https://komarev.com/ghpvc/?username=liliustwocout&label=PROFILE%20VIEWS&color=00F7FF&style=for-the-badge"/>

</div>

---

## System Status

```text
┌──────────────────────────────────────────────────────────────────────────────┐
│                         AI ENGINEER PROFILE                                  │
├──────────────────────────────────────────────────────────────────────────────┤
│                                                                              │
│  NAME        :: Lê Phạm Thành Đạt                                            │
│  ROLE        :: System Engineering Student / AI Engineer                     │
│  UNIVERSITY  :: Phenikaa University                                          │
│  LOCATION    :: Vietnam                                                      │
│                                                                              │
│  CORE        :: Artificial Intelligence · Edge AI · Full-Stack               │
│  RESEARCH    :: LLM Multi-Agent Systems · Information Diffusion              │
│  INTEREST    :: Intelligent Systems · Computer Vision · AIoT · DX            │
│                                                                              │
│  STATUS      :: BUILDING                                                     │
│  CURRENT     :: Python · Edge AI · LLM Agents · Next.js                      │
│                                                                              │
└──────────────────────────────────────────────────────────────────────────────┘
```

<div align="center">

`SYSTEM ENGINEERING` &nbsp;&nbsp; `AI ENGINEERING` &nbsp;&nbsp; `EDGE AI` &nbsp;&nbsp; `FULL-STACK`

</div>

---

## About

I am a **System Engineering student at Phenikaa University** focused on building intelligent software and hardware-integrated systems.

My current direction combines:

* **Edge AI & AIoT Systems** — Gas sensing, hardware signal processing, low-latency microcontrollers
* **LLM & Multi-Agent Research** — Complex network topology, information diffusion, semantic drift
* **Full-Stack Web Development** — High-performance dashboards, real-time monitoring, modern APIs
* **Machine Learning & Computer Vision** — Signal classification, pattern regression, embedded vision

I enjoy working across the entire pipeline — from **sensors and embedded devices**, through **data processing and AI inference**, to **APIs, dashboards, and user-facing systems**.

```text
INPUT
  │
  ├── Sensors
  ├── Images
  ├── Text
  └── User Data
       │
       ▼
PROCESSING
       │
       ├── Signal Processing
       ├── Machine Learning
       ├── Computer Vision
       └── LLM Agents
       │
       ▼
INTELLIGENCE
       │
       ├── Prediction
       ├── Classification
       ├── Simulation
       └── Decision Support
       │
       ▼
APPLICATION
       │
       ├── Web
       ├── Dashboard
       ├── Edge Device
       └── Cloud
```

---

## Technical Stack

<div align="center">

### Languages

<img src="https://skillicons.dev/icons?i=python,javascript,typescript,c,cpp,cs,java"/>

### Frontend

<img src="https://skillicons.dev/icons?i=react,nextjs,html,css,tailwind"/>

### Backend

<img src="https://skillicons.dev/icons?i=django,nodejs,fastapi"/>

### AI / Machine Learning

<img src="https://skillicons.dev/icons?i=tensorflow,pytorch"/>

<br>

<img src="https://img.shields.io/badge/Scikit--Learn-0D1117?style=for-the-badge&logo=scikit-learn&logoColor=00F7FF"/>
<img src="https://img.shields.io/badge/Pandas-0D1117?style=for-the-badge&logo=pandas&logoColor=00F7FF"/>
<img src="https://img.shields.io/badge/NumPy-0D1117?style=for-the-badge&logo=numpy&logoColor=00F7FF"/>
<img src="https://img.shields.io/badge/OpenCV-0D1117?style=for-the-badge&logo=opencv&logoColor=00F7FF"/>

### Tools / Infrastructure

<img src="https://skillicons.dev/icons?i=git,github,docker,linux,vscode,raspberrypi"/>

<br>

<img src="https://img.shields.io/badge/Ollama-0D1117?style=for-the-badge&logo=ollama&logoColor=00F7FF"/>
<img src="https://img.shields.io/badge/Firebase-0D1117?style=for-the-badge&logo=firebase&logoColor=00F7FF"/>
<img src="https://img.shields.io/badge/RS--485-0D1117?style=for-the-badge&logoColor=00F7FF"/>
<img src="https://img.shields.io/badge/Modbus%20RTU-0D1117?style=for-the-badge&logoColor=00F7FF"/>

</div>

---

## Featured Systems

<div align="center">

<a href="https://github.com/liliustwocout">
<img src="./assets/edge-ai.svg" width="49%"/>
</a>
<a href="https://github.com/liliustwocout">
<img src="./assets/mas-lab.svg" width="49%"/>
</a>

</div>

<br>

<details>
<summary><b>📂 Additional Systems &amp; Repositories</b></summary>
<br>

<div align="center">

| System | Description | Tech Stack | Link |
| :--- | :--- | :--- | :--- |
| **Sign Language Recognition** | Real-time AI-based sign language recognition system designed to support communication. | `TensorFlow.js` `CNN` `KNN` `Transfer Learning` | [View Repo →](https://github.com/liliustwocout/Sign-Language-Recognition) |
| **DevShare Lite** | Developer knowledge-sharing platform with authentication, posts, interactions and community features. | `Django` `React` `JWT` `SQLite` | [View Repo →](https://github.com/liliustwocout/DevShare-Lite) |

</div>

</details>

---

## System Architecture

<div align="center">

<img src="./assets/architecture.svg" width="100%"/>

</div>

```text
                    EDGE AI ELECTRONIC NOSE
                              │
                              ▼
┌──────────────────────────────────────────────────────────────────────┐
│                        PERCEPTION LAYER                              │
│                                                                      │
│       ZE03-H2S          MQ136             MQ135            DHT22     │
│          │                │                 │                │       │
└──────────┼────────────────┼─────────────────┼────────────────┼───────┘
           │                │                 │                │
           └────────────────┴─────────┬───────┴────────────────┘
                                      ▼
┌──────────────────────────────────────────────────────────────────────┐
│                         ESP32 NODE                                   │
│                                                                      │
│                     ADC / Sensor Acquisition                         │
└──────────────────────────────┬───────────────────────────────────────┘
                               │
                               │ RS-485 / Modbus RTU
                               ▼
┌──────────────────────────────────────────────────────────────────────┐
│                     RASPBERRY PI GATEWAY                             │
│                                                                      │
│  EMA Filter → Despike → Interpolation → Savitzky-Golay               │
│                         ↓                                            │
│               Temperature / Humidity Compensation                    │
│                         ↓                                            │
│                    Feature Extraction                                │
└──────────────────────────────┬───────────────────────────────────────┘
                               │
                               ▼
┌──────────────────────────────────────────────────────────────────────┐
│                         EDGE AI                                      │
│                                                                      │
│                  Random Forest Dual-Mode                             │
│                                                                      │
│       Pulse Classification          Concentration Regression         │
│                                                                      │
│       Accuracy: 94.18%              MAE: 3.93 ppm                    │
│                                      R²: 0.8534                      │
└──────────────────────────────┬───────────────────────────────────────┘
                               │
                               ▼
┌──────────────────────────────────────────────────────────────────────┐
│                     APPLICATION LAYER                                │
│                                                                      │
│              Dashboard / WaveCycle / Alerts / KPI                    │
└──────────────────────────────┬───────────────────────────────────────┘
                               │
                               ▼
                      FIREBASE / WISE-IoT
```

---

## Research Metrics

<div align="center">

<table>
<tr>

<td align="center" width="25%">

### 94.18%

Pulse Classification Accuracy

</td>

<td align="center" width="25%">

### 0.8534

H₂S Regression R²

</td>

<td align="center" width="25%">

### 2100+

Tokens/s

Qwen Prompt Processing

</td>

<td align="center" width="25%">

### 58–65

Tokens/s

Qwen Generation

</td>

</tr>
</table>

</div>

---

## Engineering Focus

```text
AI ENGINEERING
├── Machine Learning
├── Computer Vision
├── Edge AI
├── LLM Applications
└── Multi-Agent Systems

SOFTWARE ENGINEERING
├── Full-Stack Development
├── REST API
├── Real-Time Systems
├── Authentication
└── System Architecture

SYSTEM ENGINEERING
├── Embedded Systems
├── ESP32
├── Raspberry Pi
├── RS-485 / Modbus
└── AIoT

RESEARCH
├── Information Diffusion
├── Complex Networks
├── Semantic Drift
├── AI Safety
└── Computational Social Science
```

---

## GitHub Analytics

<div align="center">

<img height="175" src="https://github-readme-stats.vercel.app/api?username=liliustwocout&show_icons=true&hide_border=true&bg_color=050A0F&title_color=00F7FF&text_color=B8C7D9&icon_color=00F7FF&ring_color=00F7FF"/>

<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=liliustwocout&layout=compact&hide_border=true&bg_color=050A0F&title_color=00F7FF&text_color=B8C7D9"/>

<br><br>

<img src="https://streak-stats.demolab.com?user=liliustwocout&theme=dark&hide_border=true&background=050A0F&ring=00F7FF&fire=00F7FF&currStreakLabel=00F7FF&sideLabels=B8C7D9&dates=64748B"/>

</div>

---

## Contribution Activity

<div align="center">

<img src="https://github.com/liliustwocout/liliustwocout/blob/output/github-contribution-grid-snake-dark.svg"/>

</div>

---

## Connect

<div align="center">

<a href="mailto:datpltn205@gmail.com">
<img src="https://img.shields.io/badge/Gmail-050A0F?style=for-the-badge&logo=gmail&logoColor=00F7FF"/>
</a>

<a href="https://www.linkedin.com/in/th%C3%A0nh-%C4%91%E1%BA%A1t-0ba998369/">
<img src="https://img.shields.io/badge/LinkedIn-050A0F?style=for-the-badge&logo=linkedin&logoColor=00F7FF"/>
</a>

<a href="https://github.com/liliustwocout">
<img src="https://img.shields.io/badge/GitHub-050A0F?style=for-the-badge&logo=github&logoColor=00F7FF"/>
</a>

</div>

<br>

<div align="center">

```text
> BUILD SYSTEMS.
> TRAIN MODELS.
> SHIP INTELLIGENCE.
```

</div>
