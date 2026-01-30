<p align="center">
<svg width="100%" height="240" viewBox="0 0 1200 240" xmlns="http://www.w3.org/2000/svg">

  <defs>
    <!-- Blood gradient -->
    <linearGradient id="blood" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#5a0000"/>
      <stop offset="50%" stop-color="#b30000"/>
      <stop offset="100%" stop-color="#5a0000"/>
    </linearGradient>

    <!-- Soft glow -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Floating animation -->
    <animateTransform id="float"
      attributeName="transform"
      type="translate"
      from="0 0"
      to="0 -6"
      dur="3s"
      repeatCount="indefinite"
      direction="alternate"/>
  </defs>

  <!-- Background -->
  <rect width="100%" height="100%" fill="#0b0b0f"/>

  <!-- Moon -->
  <circle cx="180" cy="120" r="48" fill="#1c1c26">
    <animate attributeName="opacity" values="0.6;0.9;0.6" dur="6s" repeatCount="indefinite"/>
  </circle>

  <!-- Bats -->
  <g fill="#2b2b35">
    <path d="M980 80 q10 -10 20 0 q-10 10 -20 0">
      <animateTransform type="translate" from="0 0" to="12 -6" dur="4s" repeatCount="indefinite"/>
    </path>
    <path d="M1030 140 q8 -8 16 0 q-8 8 -16 0">
      <animateTransform type="translate" from="0 0" to="-10 6" dur="5s" repeatCount="indefinite"/>
    </path>
  </g>

  <!-- Name -->
  <text x="50%" y="52%"
        text-anchor="middle"
        font-size="42"
        font-family="Georgia, serif"
        fill="url(#blood)"
        filter="url(#glow)">
    Anna Chebotarova
    <animate attributeName="opacity"
             values="0.4;1;0.4"
             dur="4s"
             repeatCount="indefinite"/>
  </text>

  <!-- Subtitle -->
  <text x="50%" y="70%"
        text-anchor="middle"
        font-size="18"
        font-family="monospace"
        fill="#cfcfd6">
    Machine Learning Engineer
    <animateTransform
      attributeName="transform"
      type="translate"
      from="-3 0"
      to="3 0"
      dur="2.5s"
      repeatCount="indefinite"
      direction="alternate"/>
  </text>

</svg>
</p>


# 🦇 Welcome, traveler

I’m **Anna Chebotarova** —  
a **Machine Learning Engineer** who builds models that are  
**precise, resilient, and slightly dangerous**.

> _Soft mind. Sharp models. Dark aesthetics._

---

## 🖤 About Me

- 🎓 **BSc in Computer Science** — Dnipro National University  
- 🧠 **ML Engineer (2023–present)** — freelance & contract work  
- 🩸 Domains: **CV · NLP · Forecasting · GenAI**
- 🌍 Languages: Ukrainian (native), English (B2)

I work at the intersection of **mathematics, research, and production ML**,  
turning raw data into systems that *survive real-world chaos*.

---

## ⚙️ Tech Arsenal

**Machine Learning**
- TensorFlow / TFX · PyTorch · Keras
- Model evaluation, error analysis, metrics design
- Transfer learning · Overfitting control · Optimization

**Data & Engineering**
- Feature engineering · EDA · Imbalanced data
- NumPy · Pandas · OpenCV · Scikit-learn

**Deployment**
- Docker · Kubernetes · CI/CD
- Google Cloud Platform

**Languages**
- Python · C++ · C# · SQL · HTML/CSS

---

## 🩶 What I Do Best

- Build **classification, generation & forecasting models**
- Design **end-to-end ML pipelines**
- Improve model accuracy by **10–20%** with task-based metrics
- Reduce training time by **up to 50%** through smart data prep
- Deploy models that **don’t panic in production**

---

## 🦴 Projects & Writing

- 🧪 **Kaggle** — research, experiments, new ML approaches  
- ✍️ **Article Writer** —  
  [@mlfromjun / Neurolace](https://drukarnia.com.ua/mlfromjun)  
  Writing about **ML · MLOps · Math**

---

## 🕸 Certifications

- Machine Learning Specialization  
- Deep Learning Specialization  
- Machine Learning in Production (MLOps)  
- TensorFlow Developer Specialization  

---

## 🦇 Find Me in the Dark

- 🕷 GitHub: https://github.com/AnnacKK  
- 🩸 Kaggle: https://www.kaggle.com/annack  
- 🕯 LinkedIn: https://www.linkedin.com/in/anna-chebotarova-8814b7209  

---

<p align="center">
  <i>“Strong systems are born in the dark.”</i>
</p>

