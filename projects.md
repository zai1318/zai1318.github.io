---
layout: single
title: "Projects"
permalink: /projects/
---
<style>
.page__content {
  font-family: "Times New Roman", Times, serif !important;
}
</style>
### ⚙️ Research Projects

#### 🍇 1️⃣ Real-Time Detection of Unhealthy Grape Leaves using Improved YOLOv7  
<img src="/assets/images/projects/grape_detection_robot.jpg" alt="Grape Leaf Detection" width="400" align="right" style="margin-left:15px; border-radius:10px;">

This project presents an enhanced YOLOv7-based detection model for identifying unhealthy grape leaves in complex vineyard environments.  
The improved backbone integrates multi-scale feature extraction and channel attention, achieving robust performance across lighting variations.  
The system operates in real time and is suitable for onboard embedded agricultural platforms.

🎥 **Demonstration Video:**  
<video width="100%" controls style="border-radius:10px; margin-top:10px;">
  <source src="/assets/videos/grape_detection.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

**Keywords:** Deep Learning · Object Detection · YOLOv7 · Precision Agriculture  

<h4>🧪 Experimental Results: Effects of Spraying Methods on Coverage of Healthy and Unhealthy Spots</h4>

<table style="width:100%; border-collapse:collapse; font-family:'Times New Roman', Times, serif; font-size:1em; text-align:center; margin-top:10px;">
  <thead style="background-color:#f2f2f2; border-bottom:2px solid #444;">
    <tr>
      <th style="border:1px solid #444; padding:6px;">Experiment No.</th>
      <th style="border:1px solid #444; padding:6px;">Type of Experiment</th>
      <th style="border:1px solid #444; padding:6px;">No. of Spots</th>
      <th style="border:1px solid #444; padding:6px;">Healthy Spots/Sprayed</th>
      <th style="border:1px solid #444; padding:6px;">Unhealthy Spots/Sprayed</th>
      <th style="border:1px solid #444; padding:6px;">Mean Area Coverage&nbsp;%</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="border:1px solid #444; padding:6px;">1</td>
      <td style="border:1px solid #444; padding:6px;">Controlled Random Spray</td>
      <td style="border:1px solid #444; padding:6px;">10</td>
      <td style="border:1px solid #444; padding:6px;">5/0</td>
      <td style="border:1px solid #444; padding:6px;">5/5</td>
      <td style="border:1px solid #444; padding:6px;">33.17</td>
    </tr>
    <tr>
      <td style="border:1px solid #444; padding:6px;">2</td>
      <td style="border:1px solid #444; padding:6px;">Uncontrolled Random Spray</td>
      <td style="border:1px solid #444; padding:6px;">10</td>
      <td style="border:1px solid #444; padding:6px;">5/5</td>
      <td style="border:1px solid #444; padding:6px;">5/5</td>
      <td style="border:1px solid #444; padding:6px;">40.45</td>
    </tr>
    <tr>
      <td style="border:1px solid #444; padding:6px;">3</td>
      <td style="border:1px solid #444; padding:6px;">Controlled Unhealthy Leaves Spray</td>
      <td style="border:1px solid #444; padding:6px;">10</td>
      <td style="border:1px solid #444; padding:6px;">0</td>
      <td style="border:1px solid #444; padding:6px;">10/10</td>
      <td style="border:1px solid #444; padding:6px;">45.37</td>
    </tr>
    <tr>
      <td style="border:1px solid #444; padding:6px;">4</td>
      <td style="border:1px solid #444; padding:6px;">Uncontrolled Unhealthy Leaves Spray</td>
      <td style="border:1px solid #444; padding:6px;">10</td>
      <td style="border:1px solid #444; padding:6px;">0</td>
      <td style="border:1px solid #444; padding:6px;">10/7</td>
      <td style="border:1px solid #444; padding:6px;">27.34</td>
    </tr>
  </tbody>
</table>

<p style="font-family:'Times New Roman', Times, serif; font-size:0.95em; margin-top:6px;">
  <em>The results shows the impact of spraying control strategies on mean area coverage for healthy and unhealthy grapevine leaves. 
  Controlled spraying generally achieves more uniform and efficient coverage compared with uncontrolled methods.</em>
</p>

---

#### 🌳 2️⃣ Instance Segmentation of Orchard Canopies using Improved YOLOv8  
<img src="/assets/images/projects/orchard_segmentation_robot.jpg" alt="Orchard Canopy Segmentation" width="400" align="right" style="margin-left:15px; border-radius:10px;">

This project introduces an improved YOLOv8 instance segmentation network for real-time crown region extraction in orchard environments.  
By combining multi-branch attention and feature fusion, the model precisely delineates canopy boundaries to support variable-rate spraying and tree crown analysis.  

🎥 **Demonstration Video:**  
<video width="100%" controls style="border-radius:10px; margin-top:10px;">
  <source src="/assets/videos/orchard_segmentation.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

**Keywords:** Deep Learning · Instance Segmentation · YOLOv8 · Smart Spraying  

<h4>🧪 Experimental Observation: Spray Deposition Validation</h4>

<!-- Experimental Result Image -->
  <img src="/assets/images/projects/orchard-results.jpg" 
       alt="Results after spraying between trees" 
       style="display:block; margin:20px auto; border-radius:10px; 
              box-shadow:0 3px 8px rgba(0,0,0,0.25); max-width:90%;">


<p style="font-family:'Times New Roman', Times, serif; font-size:0.95em; text-align:center; margin-top:6px;">
  <em>Figure: Visual results after spraying — the water-sensitive paper was placed between trees to evaluate deposition coverage and spray precision.</em>
</p>

---

