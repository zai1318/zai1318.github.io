---
layout: single
title: "Projects"
permalink: /projects/
---

<style>
/* ====== Academic Style for Projects Page (Fixed for Minimal Mistakes) ====== */
.page__content {
  font-family: "Times New Roman", Times, serif !important;
  font-size: 1.05em;
  line-height: 1.8;
  color: #111;
  background-color: #fff;
  max-width: 780px;                /* keeps good readability */
  margin: 0 auto;
  padding: 10px 25px;
  text-align: justify;
  hyphens: auto;
  word-break: normal;
  overflow-wrap: break-word;
}

/* ====== Headings ====== */
.page__content h1,
.page__content h2,
.page__content h3,
.page__content h4 {
  font-family: "Times New Roman", Times, serif !important;
  font-weight: bold;
  color: #222;
  letter-spacing: 0.3px;
}

.page__content h2 {
  border-bottom: 1px solid #aaa;
  padding-bottom: 0.3em;
  margin-top: 1.8em;
}

.page__content h3 {
  margin-top: 1.4em;
  color: #333;
}

/* ====== Image & Video Styling ====== */
.page__content img {
  border-radius: 10px;
  margin: 8px 0 12px 15px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.15);
  max-width: 45%;                 /* keeps right-aligned images tidy */
  height: auto;
}

.page__content video {
  border-radius: 10px;
  margin-top: 10px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.2);
}

/* ====== Paragraphs and Lists ====== */
.page__content p,
.page__content li {
  font-size: 1.05em;
  margin-bottom: 0.8em;
  text-align: justify;
  word-break: normal;
  overflow-wrap: break-word;
}

/* ====== Keywords Styling ====== */
.page__content .keywords {
  font-style: italic;
  color: #333;
  background-color: #f8f8f8;
  border-left: 3px solid #888;
  padding: 6px 10px;
  margin-top: 8px;
  display: inline-block;
}

/* ====== Divider ====== */
.page__content hr {
  border: 0;
  height: 1px;
  background: #ccc;
  margin: 2em 0;
}

/* ====== Link Styling ====== */
.page__content a {
  color: #004080;
  text-decoration: none;
}
.page__content a:hover {
  text-decoration: underline;
}
</style>


---

### ⚙️ Research Projects

#### 🍇 1️⃣ Real-Time Detection of Unhealthy Grape Leaves using Improved YOLOv7
<img src="/assets/images/projects/grape_detection_robot.jpg" alt="Grape Leaf Detection" width="400" align="right">

This project presents an **enhanced YOLOv7-based detection model** for identifying **unhealthy grape leaves** in complex vineyard environments.  
The improved backbone integrates **multi-scale feature extraction** and **channel attention**, achieving robust performance across lighting variations.  
The system operates in real time and is suitable for **onboard embedded agricultural platforms**.

🎥 **Demonstration Video:**  
<video width="100%" controls>
  <source src="/assets/videos/grape_detection.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

<div class="keywords">
**Keywords:** Deep Learning · Object Detection · YOLOv7 · Precision Agriculture
</div>

---

#### 🌳 2️⃣ Instance Segmentation of Orchard Canopies using Improved YOLOv8
<img src="/assets/images/projects/orchard_segmentation_robot.jpg" alt="Orchard Canopy Segmentation" width="400" align="right">

This project introduces an **improved YOLOv8 instance segmentation network** for **real-time crown region extraction** in orchard environments.  
By combining **multi-branch attention** and **feature fusion**, the model precisely delineates canopy boundaries to support **variable-rate spraying** and **tree crown analysis**.  

🎥 **Demonstration Video:**  
<video width="100%" controls>
  <source src="/assets/videos/orchard_segmentation.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

<div class="keywords">
**Keywords:** Deep Learning · Instance Segmentation · YOLOv8 · Smart Spraying
</div>

---

<footer>
<em>Last updated January 2026</em>
</footer>
