<h1 align="left">👋 ¡Hola! Soy Victor Soto</h1>

<p align="left">
  <b>Estudiante de Ingeniería Electrónica (8vo ciclo) · UNI · Lima, Perú</b><br>
  📡 RF / SDR · 📶 Redes de Telecomunicaciones · 🧠 IA aplicada al espectro
</p>

<p align="left">
  <a href="https://www.linkedin.com/in/victor-manuel-soto-cortez-a8810a236/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:sotocortezvictormanuel@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <img src="https://img.shields.io/badge/English-C2_Proficient_(EF_SET)-2E7D32?style=for-the-badge" alt="English C2" />
</p>

---

### 🧑‍💻 Sobre mí

Soy estudiante de **8vo ciclo de Ingeniería Electrónica** en la **Universidad Nacional de Ingeniería (UNI)**, en el **tercio superior** de la FIEE.

Trabajo en la intersección entre **radiofrecuencia y la inteligencia artificial**: radios definidas por software (SDR), procesamiento digital de señales, diseño de enlaces inalámbricos y modelos de deep learning que corren en tiempo real sobre hardware real. Ahora mismo formo parte de un **proyecto de investigación financiado de radio cognitiva** para llevar conectividad a zonas rurales usando espectro de TV libre (TVWS).

Mi objetivo: especializarme en **AI-RAN / Spectrum Intelligence**, es decir, aplicar machine learning a redes de acceso radio y gestión dinámica del espectro.

- 🔭 Trabajando en: **Radio Cognitiva TVWS** (SDR + Deep Learning), proyecto VRI-UNI
- 🌱 Aprendiendo: **HCIA-5G**, **HCIA-Datacom**, **CCNA SRWE** y la **DSP Specialization (EPFL)**
- 🤝 Abierto a: **prácticas pre-profesionales** en telecomunicaciones, RF/wireless, IoT o IA aplicada
- 🤖 Desarrollo asistido por IA: **5 meses usando Claude Code** a diario en mis proyectos
- 🗣️ Idiomas: Español (nativo) · Inglés **C2 Proficient** (EF SET 75/100)

---

### 🚀 Proyectos destacados

#### 📡 Radio Cognitiva TVWS: SDR asimétrico + Deep Learning
*Proyecto de investigación financiado por el VRI-UNI (S/ 40,000) · Jul. 2026 – presente*

Prototipo de radio cognitiva para **acceso dinámico a TV White Spaces** en zonas rurales. Soy responsable de la **Fase 2**: integración del SDR con la capa MAC y el bloque cognitivo.

- Diseño de trama **OFDM** (512 subportadoras, pilotos y bandas de guarda) en **GNU Radio** sobre **bladeRF 2.0 micro xA4**
- Protocolo **TDD por software** con canal de control in-band verificado por **CRC-16**
- **Link budget** completo (EIRP, FSPL, figura de ruido, márgenes BPSK/QPSK/16-QAM) y dimensionamiento de la cadena RF: LNA, PA, antenas LPDA, protección GDT, cableado LMR-400/RG-316
- **CNN 1D de doble cabeza** para sensado espectral, exportada a **ONNX Runtime** e inferida en tiempo real (**AUC-ROC 0.88** en el baseline sintético)
- Ajuste de tiempo real en Linux (`isolcpus`, `taskset`) para reducir la latencia de la cadena GNU Radio

#### 🛰️ CubeSat 1U: Finalista Nacional CNSPS
*Competencia Nacional de Pequeños Satélites, PUCP · Feb. 2025*

Prototipo de CubeSat 1U controlado por una **Raspberry Pi Zero 2 W**, con payload de telemetría atmosférica y enlace a estación terrena mediante **LoRa**. Diseño, integración y validación del subsistema de comunicaciones RF.

#### 📝 Lector Óptico de Marcas (OMR) con IA
*2025*

Sistema hardware/software para calificar fichas ópticas automáticamente: detección de contornos, corrección de perspectiva y reconocimiento de marcas por umbralización adaptativa con **OpenCV**. Una máquina de estados en **Raspberry Pi** controla la interfaz y la cola de llamadas al modelo de IA.

| Proyecto | Área | Tecnologías |
| :--- | :--- | :--- |
| **Radio Cognitiva TVWS** | RF · DSP · Deep Learning | `GNU Radio` `bladeRF` `OFDM` `Python` `ONNX Runtime` `Linux` |
| **CubeSat 1U** | Aeroespacial · Telemetría | `Raspberry Pi Zero 2 W` `ESP32` `LoRa` `Linux` `Python` |
| **Lector OMR con IA** | Visión por computadora · Embebidos | `Raspberry Pi` `Python` `OpenCV` |

---

### 💼 Experiencia y liderazgo

- **Director de Proyectos | IEEE Computational Intelligence Society (CIS) UNI** · *Mar. 2026 – presente*
  - Gestión técnica de proyectos de machine learning: supervisión de la arquitectura de los modelos y de la viabilidad del hardware.
- **Investigador (Fase 2) | Proyecto Radio Cognitiva TVWS, VRI-UNI** · *Jul. 2026 – presente*
  - Integración SDR + capa MAC + bloque cognitivo de sensado espectral.
- **Finalista Nacional | Competencia Nacional de Pequeños Satélites (CNSPS), PUCP** · *Feb. 2025*
  - Fase final nacional de lanzamiento y operación con un equipo multidisciplinario: payload de telemetría y transmisión de datos RF.

---

### 🛠️ Habilidades técnicas

**RF, Wireless y DSP**
<p align="left">
  <img src="https://img.shields.io/badge/GNU_Radio-000000?style=flat-square&logo=gnu&logoColor=white" alt="GNU Radio" />
  <img src="https://img.shields.io/badge/SDR-bladeRF_2.0-4B4B4B?style=flat-square" alt="SDR bladeRF" />
  <img src="https://img.shields.io/badge/OFDM-Link_Budget-1565C0?style=flat-square" alt="OFDM / Link Budget" />
  <img src="https://img.shields.io/badge/LoRa-1CA9E1?style=flat-square" alt="LoRa" />
  <img src="https://img.shields.io/badge/MATLAB-ED7B39?style=flat-square&logo=mathworks&logoColor=white" alt="MATLAB" />
  <img src="https://img.shields.io/badge/Multisim-0047BA?style=flat-square&logo=ni&logoColor=white" alt="Multisim" />
</p>

**Lenguajes**
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash" />
</p>

**Inteligencia Artificial y Datos**
<p align="left">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" alt="Scikit-Learn" />
  <img src="https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square&logo=onnx&logoColor=white" alt="ONNX Runtime" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" alt="Power BI" />
</p>

**Redes, Cloud y Sistemas**
<p align="left">
  <img src="https://img.shields.io/badge/Cisco-1BA0D7?style=flat-square&logo=cisco&logoColor=white" alt="Cisco" />
  <img src="https://img.shields.io/badge/Huawei-FF0000?style=flat-square&logo=huawei&logoColor=white" alt="Huawei" />
  <img src="https://img.shields.io/badge/GNS3-2C3E50?style=flat-square" alt="GNS3" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white" alt="Oracle Cloud" />
  <img src="https://img.shields.io/badge/Arch_Linux-1793D1?style=flat-square&logo=archlinux&logoColor=white" alt="Arch Linux" />
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white" alt="Ubuntu" />
  <img src="https://img.shields.io/badge/Virtual_Machines-607078?style=flat-square&logo=vmware&logoColor=white" alt="VMware/VirtualBox" />
</p>

**Embebidos e IoT**
<p align="left">
  <img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberry-pi&logoColor=white" alt="Raspberry Pi" />
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32" />
  <img src="https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white" alt="MQTT" />
  <img src="https://img.shields.io/badge/ROS-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS" />
</p>

**Herramientas**
<p align="left">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white" alt="LaTeX" />
  <img src="https://img.shields.io/badge/Claude_Code-5_meses-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude Code" />
</p>

**Desarrollo asistido por IA: Claude Code (~5 meses, desde may. 2026)**
- Uso diario de **Claude Code** como agente de desarrollo en la terminal: escritura y depuración de código Python, scripts Bash y flujos en Linux.
- Automatización de documentación técnica en **LaTeX** (CV, informes) y organización de proyectos de ingeniería.
- Apoyo en investigación técnica: análisis de link budget, revisión de arquitecturas SDR/GNU Radio y planificación de aprendizaje.

---

### 📜 Certificaciones

<details>
<summary><b>📡 RF, Redes y Sistemas Embebidos</b></summary>

| Certificación | Emisor | Fecha |
| :--- | :--- | :--- |
| CCNA: Introduction to Networks | Cisco | Dic. 2025 |
| Digital Signal Processing 1: Basic Concepts and Algorithms | EPFL (Coursera) | Ago. 2026 |
| Embedded Software and Hardware Architecture | University of Colorado Boulder | |
| Industrial IoT Markets and Security | University of Colorado Boulder | |
| Digital Systems: From Logic Gates to Processors | UAB (Coursera) | |
| Introduction to Internet of Things | Coursera | |
| CCNA: Switching, Routing and Wireless Essentials | Cisco | *En curso* |
| HCIA-5G V2.0 | Huawei | *En curso* |
| HCIA-Datacom | Huawei | *En curso* |

</details>

<details>
<summary><b>🧠 Inteligencia Artificial y Datos</b></summary>

| Certificación | Emisor | Fecha / Nota |
| :--- | :--- | :--- |
| OCI 2025 Certified AI Foundations Associate | Oracle | Set. 2025 |
| Cisco AI Technical Practitioner (AITECH) | Cisco | |
| Deep Learning & Modern AI Architectures | Packt (Coursera) | Feb. 2026 |
| Artificial Intelligence Fundamentals | IBM SkillsBuild | Set. 2025 |
| IA: Machine Learning con Python | UNI-OTI | 18/20 |
| Ciencia de Datos 1 | UNI-OTI | 17/20 |
| Python para Ingeniería | UNI-OTI | 20/20 |
| Extract, Transform and Load Data in Power BI | Microsoft (Coursera) | |

</details>

<details>
<summary><b>☁️ Cloud, Linux y Bases de Datos</b></summary>

| Certificación | Emisor | Fecha / Nota |
| :--- | :--- | :--- |
| AWS Academy Graduate: Cloud Foundations | AWS Academy | Ago. 2025 |
| Advanced Linux Administration and Shell Scripting | Packt (Coursera) | |
| Linux Foundations and Basic System Administration | Coursera | |
| Tools of the Trade: Linux and SQL | Google (Coursera) | |
| SQL Server: Base de Datos 1 | UNI-OTI | 18/20 |
| Programación de Robots con ROS | UNI-OTI | 19/20 |

</details>


---

### 📊 Estadísticas de GitHub

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=vsotoc666&show_icons=true&theme=radical&hide_border=true" alt="GitHub Stats" width="48%">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vsotoc666&layout=compact&theme=radical&hide_border=true" alt="Top Languages" width="48%">
</p>

---
