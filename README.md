<p align="center">

  <h2 align="center">SplatSearch: SplatSearch: Instance Image Goal Navigation for Mobile Robots using 3D Gaussian Splatting and Diffusion Models</h2>
  <p align="center">
    <a href="https://quest2gm.github.io/"><strong>Siddarth Narasimhan</strong></a>
    ·
    <a href="https://mattlisondra.com/"><strong>Matthew Lisondra</strong></a>
    ·
    <a href="https://scholar.google.com/citations?user=LA6TYrgAAAAJ&hl=en"><strong>Haitong Wang</strong></a>
    ·
    <a href="https://scholar.google.com/citations?user=1pCgjH0AAAAJ&hl=en"><strong>Goldie Nejat</strong> </p>
  <p align="center">
    <a href="https://robotics.utoronto.ca/"><strong>University of Toronto</strong></a>
  </p>

<h3 align="center">
    <a href="https://arxiv.org/abs/2511.12972" target="_blank">
    <img src="https://img.shields.io/badge/arXiv-2511.12972-blue?logo=arxiv&color=%23B31B1B" alt="Paper arXiv"></a>
    <a href="https://splat-search.github.io/" target="_blank">
    <img src="https://img.shields.io/badge/Project-Page-a" alt="Project Page"></a>
    <a href="https://opensource.org/licenses/MIT" target="_blank">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT"></a>
</h3>
<div align="center"></div>

<div align="center">
  <video width="850" controls>
    <source src="https://raw.githubusercontent.com/Quest2GM/SplatSearch/main/assets/v5_video.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

<span class="dperact">The Instance Image Goal Navigation (IIN) problem requires mobile robots deployed in unknown environments to search for specific objects or people of interest using only a single reference goal image of the target. This problem can be especially challenging when: 1) the reference image is captured from an arbitrary viewpoint, and 2) the robot must operate with sparse-view scene reconstructions. In this paper, we address the IIN problem, by introducing SplatSearch, a novel architecture that leverages sparse-view 3D Gaussian Splatting (3DGS) reconstructions. SplatSearch renders multiple viewpoints around candidate objects using a sparse online 3DGS map, and uses a multi-view diffusion model to complete missing regions of the rendered images, enabling robust feature matching against the goal image. A novel frontier exploration policy is introduced which uses visual context from the synthesized viewpoints with semantic context from the goal image to evaluate frontier locations, allowing the robot to prioritize frontiers that are semantically and visually relevant to the goal image.</span>

## 💡 News
* **[17 Nov 2025]** Released **SplatSearch** on arxiv.
* **[8 Nov 2025]** Submitted **SplatSearch** to Robotics and Automation Letters (RA-L).

## 🛠️ Code

We plan to release our code upon acceptance to RA-L. Stay tuned!
