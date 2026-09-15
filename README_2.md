<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,50:7C3AED,100:0891B2&height=200&section=header&text=Aditi%20Gupta&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Machine%20Learning%20%7C%20Deep%20Learning%20%7C%20Applied%20AI&descAlignY=55&descSize=18" width="100%" alt="Aditi Gupta — Machine Learning, Deep Learning, Applied AI" />

<a href="https://github.com/aditi532">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=7C3AED&center=true&vCenter=true&width=600&lines=Machine+Learning+%26+Deep+Learning+Engineer;Time+Series+%7C+Anomaly+Detection+%7C+Medical+AI;B.Tech+CSE+%40+VIT+Bhopal+%E2%80%A2+CGPA+8.84;I+build+models+that+ship%2C+not+just+notebooks" alt="Typing animation" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aditi-gupta-66b059285)
[![Email](https://img.shields.io/badge/Email-0891B2?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aditigupta160604@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-1a1b27?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aditi532)
[![Profile Views](https://komarev.com/ghpvc/?username=aditi532&style=for-the-badge&color=7C3AED&label=PROFILE+VIEWS)](https://github.com/aditi532)

</div>

---

## About

```python
class AditiGupta:
    def __init__(self):
        self.role      = "ML / Deep Learning Engineer"
        self.education = "B.Tech CSE @ VIT Bhopal University (2023 – 2027)"
        self.focus     = ["Time Series Anomaly Detection",
                          "Medical Signal Classification",
                          "Real-Time Computer Vision"]
        self.stack     = ["Python", "TensorFlow", "Keras", "Flask", "Flutter"]
        self.currently = "Turning research ideas into deployed systems"

    def philosophy(self):
        return "A model is only as good as the moment it actually helps someone."
```

- Deep learning across **medical diagnostics**, **driver safety**, and **streaming anomaly detection**
- Benchmarked **4 architectures** (MLP, 1D Conv AE, Variational AE, WaveNet) on the NAB benchmark dataset
- **~94% accuracy** on 5-class brain tumor signal classification using stacked ensembles
- **100+ LeetCode** problems solved · cleared the college round of **Smart India Hackathon**

---

## Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

**Machine Learning & Deep Learning**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

**Frameworks, Data & Tools**

![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### Brain Tumor Signal Classification
**EEG signal classification · 94.64% accuracy**

Detects brain tumors from EEG signals across **5 diagnostic categories**, over **11,500 samples** with 178 numerical features. PCA (50 components) and recursive feature selection handle dimensionality; a stacked CatBoost + LightGBM ensemble with a logistic-regression meta-learner is compared against deep models including Random Forest, XGBoost, and a standalone ANN — the ensemble wins across all 5 balanced classes.

`Python` `TensorFlow` `CatBoost` `LightGBM` `scikit-learn`

[**→ View repository**](https://github.com/aditi532/Brain-Tumor-Signal-Classification)

</td>
<td width="50%" valign="top">

### AnomalyNet
**Unsupervised online deep learning**

A framework for real-time anomaly detection in time series that handles concept drift, sparse labels, and class imbalance **without a single labeled anomaly**. Four architectures benchmarked in both online and seq2seq settings, validated on the NAB benchmark, with automated hyperparameter search and JSON-driven config management.

`Python` `TensorFlow/Keras` `NumPy` `Pandas`

[**→ View repository**](https://github.com/aditi532/AnomalyNet-)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Wake Drive — Cognitive Awareness Engine
**Real-time driver drowsiness detection**

A Flutter mobile app using Google ML Kit Face Detection to track eye behavior live, computing **Eye Aspect Ratio** to catch drowsiness and microsleep. A multi-stage alert pipeline escalates from a visual warning at 0.5s to an audio alarm at 1.0s to an automated emergency trigger at 5.0s — dispatching Telegram SOS alerts with GPS coordinates and nearby hospitals from the Overpass API.

`Flutter` `Google ML Kit` `Telegram Bot API` `OpenStreetMap`

[**→ View repository**](https://github.com/aditi532/Cognitive-Awareness-Engine-for-Safe-Driving)

</td>
<td width="50%" valign="top">

### Also building

**[gesture_volume_control](https://github.com/aditi532/gesture_volume_control)** — MediaPipe hand tracking that maps thumb-to-index distance onto system volume in real time, with a live on-screen volume bar. `OpenCV` `MediaPipe` `pycaw`

**[internpreperation](https://github.com/aditi532/internpreperation)** — DSA practice and interview prep, worked consistently rather than in bursts.

**[Resume](https://github.com/aditi532/Resume)** — the current version, always up to date.

<br/>

[![All repositories](https://img.shields.io/badge/Browse_all_repositories-7C3AED?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aditi532?tab=repositories)

</td>
</tr>
</table>

---

## GitHub Summary

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=aditi532&theme=tokyonight&animation=rgb-soft&duration=8" width="100%" alt="Profile details" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=aditi532&theme=tokyonight" width="49%" alt="Top languages by repository" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=aditi532&theme=tokyonight" width="49%" alt="Top languages by commit" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=aditi532&theme=tokyonight" width="49%" alt="GitHub stats" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=aditi532&theme=tokyonight&utcOffset=5.5" width="49%" alt="Productive time" />

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=aditi532&theme=tokyonight&hide_border=true&background=1A1B27&ring=7C3AED&fire=0891B2&currStreakLabel=7C3AED" width="70%" alt="Contribution streak" />

</div>

---

## Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=aditi532&theme=algolia&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" width="100%" alt="GitHub trophies" />

</div>

---

## Contribution Graph

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/aditi532/aditi532/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/aditi532/aditi532/output/github-contribution-grid-snake.svg" />
  <img src="https://raw.githubusercontent.com/aditi532/aditi532/output/github-contribution-grid-snake.svg" width="100%" alt="Snake animation eating the contribution graph" />
</picture>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=aditi532&theme=tokyo-night&bg_color=1A1B27&color=7C3AED&line=0891B2&point=FFFFFF&hide_border=true&area=true" width="100%" alt="Contribution activity graph" />

</div>

---

## Certifications & Beyond

<div align="center">

| | |
|:--|:--|
| **Applied Machine Learning in Python** — Coursera | Nov 2025 |
| **AWS Technical Essentials** — AWS Training & Certification | Sep 2025 |
| **Smart India Hackathon** — cleared college round, VIT Bhopal | Aug 2023 – present |
| **100+ LeetCode problems** — consistency over cramming | ongoing |

</div>

---

<div align="center">

### Let's build something

I'm looking for **ML / AI internships and research collaborations**. If you're working on time series, medical AI, or anything that has to run in real time — I'd like to hear about it.

[![Email](https://img.shields.io/badge/Say_hello-0891B2?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aditigupta160604@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aditi-gupta-66b059285)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0891B2,50:7C3AED,100:1a1b27&height=120&section=footer" width="100%" alt="" />

</div>
