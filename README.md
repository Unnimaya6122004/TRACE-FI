<a href="#">
  <img align="left" 
       alt="TraceFi Banner" 
       width="100%" 
       style="padding-right:10px;" 
       src="https://capsule-render.vercel.app/api?type=waving&height=250&color=0:111111,50:222222,100:333333&text=Welcome%20to%20TraceFi&fontAlignY=45&fontSize=40&textBg=false&animation=twinkling&fontColor=00FF99" />
</a>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?color=33FF99&size=30&width=900&height=80&lines=🛡️+TraceFi:+AI-Powered+Threat+Detection+%26+DDoS+Forecasting">
</p>
<div align="center">
  <img src="https://www.nimbusddos.com/img/animations/cloud-based-ddos-simulation-platform.gif" width="48%" height="300px" style="object-fit: cover; margin: 5px;">
  <img src="https://i0.wp.com/secure.wphackedhelp.com/blog/wp-content/uploads/2019/04/ddos_attack_works.gif?resize=762%2C561&ssl=1" width="48%" height="300px" style="object-fit: cover; margin: 5px;">
</div>


## 🌐 Introduction

**TraceFi** is an advanced AI-based dual-layer network security system designed to defend against modern cyber threats. Unlike traditional systems, TraceFi not only detects threats like DoS, DDoS, port scans, and brute-force attacks in real-time — it also **predicts potential DDoS attacks** before they happen using time-series analysis.

> 🌍 Built for the modern web. ⚡ Driven by AI. 🔐 Ready for real-world deployment.

---

## 🚀 Features

* 🔍 Real-time Threat Detection (DoS, PortScan, Brute Force)
* 📊 DDoS Attack Prediction using LSTM/GRU
* 🖥️ Flask Dashboard with live alerts & graphs
* 📂 Upload interface to test historical network data
* 📈 Visual analytics (Plotly, Chart.js)
* ✅ Trained on CICDDoS2019 dataset

---

## ⚠️ Threats Detected

| Threat           | Description                                      |
| ---------------- | ------------------------------------------------ |
| 🧨 DoS           | Overloading a server to crash it                 |
| 🌊 DDoS          | Multi-source attacks to block legitimate traffic |
| 🕵️‍♂️ Port Scan | Searching for network vulnerabilities            |
| 🔑 Brute Force   | Repeated password guessing                       |

---

## 🎯 Objectives

* 🧠 Combine supervised detection + time-series prediction
* 🚀 Deploy a lightweight but powerful Flask dashboard
* 📡 Alert-based reporting for live monitoring
* 📈 Build explainable and scalable ML/DL pipelines
  

---

## 🛠️ Tech Stack

| Component        | Tech Used                        |
| ---------------- | -------------------------------- |
| ML/DL Models     | Scikit-learn, Keras, TensorFlow  |
| Prediction Layer | LSTM, GRU                        |
| Backend          | Python, Flask                    |
| Frontend         | HTML5, CSS3, Bootstrap, Chart.js |
| Deployment       | Localhost, Heroku (opt.)         |
| Data Processing  | Pandas, Numpy                    |

<div align="center">
  <!-- Python -->
  <img src="https://techstack-generator.vercel.app/python-icon.svg" alt="Python" width="60" height="60" />
  <img width="12" />

  <!-- TensorFlow -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" alt="TensorFlow" width="55" height="55"/>
  <img width="12" />

  <!-- Keras -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/keras/keras-original.svg" alt="Keras" width="55" height="55"/>
  <img width="12" />

  <!-- Scikit-learn (custom PNG alternative) -->
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="Scikit-learn" width="65" height="55"/>


  <!-- Pandas -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" alt="Pandas" width="55" height="55"/>
  <img width="12" />

  <!-- Numpy -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" alt="Numpy" width="55" height="55"/>
  <img width="12" />

  <!-- HTML5 -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" width="55" height="55"/>
  <img width="12" />

  <!-- CSS3 -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" width="55" height="55"/>
  <img width="12" />

  <!-- Bootstrap -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" alt="Bootstrap" width="55" height="55"/>
  <img width="12" />

  <!-- Chart.js -->
  <img src="https://www.chartjs.org/img/chartjs-logo.svg" alt="Chart.js" width="55" height="55"/>
  <img width="12" />

  <!-- Heroku -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/heroku/heroku-original.svg" alt="Heroku" width="55" height="55"/>
  
  <!-- Flask -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" alt="Flask" width="55" height="55"/>
  <img width="12" />

</div>
<br><br>


---

## 📂 Dataset

**CICDDoS2019** (Canadian Institute for Cybersecurity)

* 🧾 80+ features with timestamped attack metadata
* 🧠 Supports both anomaly and supervised learning
* 🔄 Includes: BENIGN, DoS-Slowloris, DDoS-UDP/SYN

---

## 📊 Features Used

* Flow Duration
* Packet Length Stats
* Forward/Backward Inter-arrival Times
* Average Packet Sizes
* Protocol & Flag Distribution

---

## 🎥 How It Works

<div align="center">
    <img src="https://www.timusnetworks.com/wp-content/uploads/2024/05/ddos-attack.png" width="45%">
  <img src="https://www.h-x.technology/wp-content/uploads/2021/02/DDoS-Image.gif" width="45%">
</div>

---

## ⚙️ Installation & Setup

### 🔁 Clone the Repository

```bash
git clone https://github.com/yourusername/tracefi.git
cd tracefi
```

### 🧠 Backend Setup (Flask)

```bash
cd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

### 🌐 Frontend Access

* Open browser → `http://localhost:5000`
* Explore the dashboard with simulated or uploaded data

---

## 🌍 Future Roadmap

* 📱 Mobile app for admin alerts
* 🌐 Cloud API with scalable endpoints
* 🛰️ Heatmaps of attack geography
* 🔐 Role-based access control
* 🧠 Online training with live packet streams

---

## 📚 Research Support

* [DDoS Detection via DL - ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/S0167404822001432)
* [Time-Series LSTM-AE - arXiv](https://arxiv.org/abs/2305.09475)
* [Hybrid AI Threat Models - MDPI](https://www.mdpi.com/1999-5903/15/8/278)

---

## Thanks to all Contributors 💪

Thanks a lot for spending your time helping the project grow. Thanks a lot! Keep rocking 🍻
	 
<p>
  <img src="https://api.vaunt.dev/v1/github/entities/Unnimaya6122004/repositories/TRACE-FI/contributors?format=svg&limit=54" width="600" height"250" />
</p>

![Contributors](https://contrib.rocks/image?repo=Unnimaya6122004/TRACE-FI)
---

---

## 📜 License

This project is licensed under the **Apache License 2.0**. See [`LICENSE`](LICENSE) for more info.

---
###  Show some ❤️ by starring this  repository! <img src="https://imgur.com/o7ncZFp.jpg" height=35px width=35px>


<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:1a1a1a,50:222222,100:111111&section=footer&text=⚙️+Thanks+for+exploring+TraceFi!&fontAlignY=60&fontSize=30&fontColor=00FF99" />
</p>
