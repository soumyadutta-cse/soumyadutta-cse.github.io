---
layout: archive
title: ""
permalink: /insightlab/
author_profile: true
---

<!-- Some help were taken from: https://www.w3schools.com/ -->

<style>
.collab-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    column-gap: 30px;
    row-gap: 4px;
    margin-top: 5px;
}

.collab-item {
    line-height: 1.2;
    font-size: 0.95em;
}

details {
    margin-top: 10px;
}

details summary {
    color: #0066cc;
    font-weight: bold;
    cursor: pointer;
}

details summary:hover {
    text-decoration: underline;
}

img {
  border-radius: 70%;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}

html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

.column {
  float: left;
  width: 30%;
  margin-bottom: 16px;
  padding: 0 8px;
}

/*.card {
  box-shadow: 1px 1px 1px 1px rgba(0, 0, 0, 0.1);
}*/

.about-section {
  padding: 10px;
  text-align: center;
  background-color: #474e5d;
  color: white;
}

.container {
  padding: 0 12px;
}

.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: grey;
}

.rectangle-image {
    border-radius: 0;
    width: 100%;
    height: auto;
}

@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}

grid-template-columns: repeat(auto-fit, minmax(130px, 1fr));

.person img {
    width: 90px;
    height: 90px;
    object-fit: cover;
    border-radius: 50%;
}

.person-name {
    font-weight: bold;
    margin-top: 6px;
}

.person-role {
    font-size: 0.9em;
    color: #555;
}

.people-grid {
    display: grid;
    grid-template-columns: repeat(6, 150px);
    justify-content: center;
    gap: 30px 20px;
    margin-top: 20px;
}

.person {
    text-align: center;
}

.person img {
    width: 100px;
    height: 100px;
    object-fit: cover;
    border-radius: 50%;
}

.person-name {
    font-weight: bold;
    margin-top: 8px;
}

.person-role {
    font-size: 0.9em;
    color: #555;
}

.search-showcase {
    width: 800px;      /* choose your width */
    height: 450px;     /* choose your height */
    margin: 0 auto;
    overflow: hidden;
}

.search-showcase img {
    width: 100%;
    height: 100%;
    object-fit: contain;   /* keeps entire image visible */
    transition: opacity 0.1s ease-in-out;
    border-radius: 0 !important;
}

}

</style>

<h1 style="text-align:center; text-decoration: underline;">
  INSIGHT: Intelligent Scientific and Visual Computing of Big Data Research Group
</h1>


<!-- This gives one single collage -->
<!-- <div class="box"><p>
    <img class="map rectangle-image"
     src="/images/collage.png"
     width="100%">
</p></div> -->


<!-- This gives animated images -->
<div class="search-showcase">
    <img id="showcase-image" src="/images/tvcg_dl_uncert_image_synthesis.png" alt="Search Demo">
</div>
<script>
const images = [
    "/images/vis24_dl_vector_uncert.png",
    "/images/xai_deep_fake_ICPR_26.png",
    "/images/revinr_pvis26.png",
    "/images/ICPR_26_difflatent.png",
    "/images/UQ_DL_Vis_Workshop.png",
    "/images/tvcg_sampling.png",
    "/images/mvnet.png",
    "/images/tvcg_sampling.png",
    "/images/jiayi_tvcg.png",
    "/images/PMI_sampling_entropy.png",
    "/images/pvis2018_fuzzy_insitu.png",
    "/images/isav_sampling_18.png",
    "/images/isav_21.png",
    "/images/insitu_dist_book_chapter.png",
    "/images/ieeebigdata_I1_summarization.png",
    "/images/mfix_jocs.png",
    "/images/Humayra_cise.png",
    "/images/fg2025.png",
    "/images/eurovis_shoprt_2019.png",
    "/images/cinema_chapter.png",
    "/images/buildsec_2025.png",
    "/images/ascr_workshop.png",
    "/images/fg2025.png",
    "/images/fuzzy_tracking.png",
    "/images/Greg_stall_2017.png",
    "/images/hazarika_pvis_16.png",
    "/images/tzu_sampling_pvis_18.png",
    "/images/vis13_tvcg.png",
    "/images/vis15_stall.png",
    "/images/slic_pvis.png"
];
let current = 0;
const img = document.getElementById("showcase-image");
setInterval(() => {
    img.style.opacity = 0;

    setTimeout(() => {
        current = (current + 1) % images.length;
        img.src = images[current];
        img.style.opacity = 1;
    }, 500);
}, 3000);
</script>




<h1 style="text-align: center;">---- Intelligent - Interactive - Interpretable ----</h1>

<p>
Welcome to the Intelligent Scientific and Visual Computing of Big Data Research Group at the <a href="https://www.iitk.ac.in">Indian Institute of Technology, Kanpur (IITK)</a>. We are part of the <a href="https://www.cse.iitk.ac.in/">Department of Computer Science and Engineering</a>. Our research lies at the unique intersection of <b>machine learning, visual computing, visualization, big data, and high-performance computing</b>. We develop state-of-the-art data analytics, machine learning, and visualization and computer vision techniques to accelerate data-driven discoveries in diverse application domains. Summarizing, extracting, and comprehending the crux from the vast seas of data and representing them visually and interactively in an interpretable and scalable manner is the broad-scale focus of our research.</p>

<p>To achieve our goal, we build machine (deep) learning and data science-based solutions to analyze large-scale multifaceted data in a scalable way, enabling interactive and interpretable analytics of complex data. We are also focused on developing techniques that make complex machine learning models more interpretable and explainable so that they can be trusted and effectively adopted in real-life applications. Our research addresses various big data characteristics, including its fundamental 5 Vs: <b>Volume, Velocity, Variety, Veracity, and Value</b>. We study extreme-scale data from scientific domains using machine learning and modern high-performance computing capabilities to advance research in various domains. We are also actively focused on building scalable and novel interactive visual analytics systems to analyze diverse data generated via social media, IoT, various sensors, engineering design, healthcare, and many other industry applications.</p>


<h2 style="color:Chocolate;">Current PhD Students</h2>

<div class="people-grid">

<div class="person">
    <img src="/images/anubhav.jpg" alt="Anubhav Dixit">
    <div class="person-name">Anubhav Dixit</div>
    <div class="person-role">Ph.D. Candidate</div>
</div>

<div class="person">
    <img src="/images/shanu.png" alt="Shanu Saklani">
    <div class="person-name">Shanu Saklani</div>
    <div class="person-role">Ph.D. Candidate</div>
</div>

<div class="person">
    <img src="/images/sankhadeep.jpg" alt="Sankhadeep Bhowmick">
    <div class="person-name">Sankhadeep Bhowmick</div>
    <div class="person-role">Ph.D. Candidate</div>
</div>

<div class="person">
    <img src="/images/ananya.jpg" alt="Ananya Chaturvedi">
    <div class="person-name">Ananya Chaturvedi</div>
    <div class="person-role">Ph.D. Candidate</div>
</div>

<div class="person">
    <img src="/images/arpita.jpg" alt="Arpita Santra">
    <div class="person-name">Arpita Santra</div>
    <div class="person-role">Ph.D. Candidate</div>
</div>

<div class="person">
    <img src="/images/robin.jpg" alt="Robin Shah">
    <div class="person-name">Robin Shah</div>
    <div class="person-role">Ph.D. Student</div>
</div>

</div>



<h2 style="color:Chocolate;">Current MTech/MS Students</h2>

<ul>
    <li>
        <b>Harsh Sanjay Pandey | M.Tech. CSE | Batch'25</b><br>
        Thesis: TBD
    </li>

    <li>
        <b>Shrey Sharma | M.Tech. CSE | Batch'25</b><br>
        Thesis: TBD
    </li>

    <li>
        <b>Siddharth Banerjee | M.Tech. CSE | Batch'25</b><br>
        Thesis: TBD
    </li>

    <li>
        <b>Darshana Baruah | M.Tech. CSE | Batch'25</b><br>
        Thesis: TBD
    </li>
</ul>

<details>
    <summary style="cursor:pointer; color:#0066cc; font-weight:bold;">
        See Past Students
    </summary>

    <ul>
        <li>
            <b>Kaushik Raj V. Nadar | B.Tech. (BSBE) - MS (SDS) | Batch'20 (Co-supervisor: Prof. Satya Prakash Singh)</b><br>
            Project: Efficient Large-Scale Multivariate Data Analytics and Visualization using Statistical Approaches
        </li>

        <li>
            <b>Voora Nagendrabhaskaraswamy | M.Tech. CSE | Batch'24</b><br>
            Thesis: Multi-Level Compressive Neural Representation Learning for Multivariate Time-Varying Data via Knowledge Distillation<br>
            <span style="color:red; font-weight:bold;">*** Academic Excellence Award ***</span>
        </li>

        <li>
            <b>Yashwanth Tippireddy | M.Tech. CSE | Batch'24</b><br>
            Thesis: DAVi: A Slim, Secure and Scalable Framework for Developing Data Analytics and Visualization Platforms - III
        </li>

        <li>
            <b>Amit Bhasita | M.Tech. CSE | Batch'24</b><br>
            Thesis: DAVi: A Slim, Secure and Scalable Framework for Developing Data Analytics and Visualization Platforms - II
        </li>

        <li>
            <b>Khushwant Kaswan | M.Tech. CSE | Batch'24</b><br>
            Thesis: DAVi: A Slim, Secure and Scalable Framework for Developing Data Analytics and Visualization Platforms - I
        </li>

        <li>
            <b>Telugu Sudhakar | M.Tech. CSE | Batch'24</b><br>
            Thesis: Learning Parameterized Probability Distributions in Volumetric Data Using Compact Neural Representations
        </li>

        <li>
            <b>Divyanshu Jha | M.Tech. CSE | Batch'24</b><br>
            Thesis: Modeling and Quantifying the Impact of Data Uncertainty in Deep Neural Networks for Scientific Applications
        </li>

        <li>
            <b>Devang Agrawal | M.Tech. CSE | Batch'24</b><br>
            Thesis: Learning Compressed Local Latent Representations for Interactive Analytics and Visualization of Large Scientific Data
        </li>

        <li>
            <b>Kartik Jain | M.Tech. CSE | Batch'23</b><br>
            Thesis: Learning Compressive Implicit Neural Representations of 3D Scalar Data: A Comparative Study Between Bottleneck and Low Rank Matrix Factorization-based Representations
        </li>

        <li>
            <b>Komala Yaramareddy | M.Tech. CSE | Batch'23</b><br>
            Thesis: Efficient Compression of Implicit Neural Networks for 3D Scalar Field Learning via Pruning with User-Guided Quality Control
        </li>

        <li>
            <b>Shaurya Agarwal | M.Tech. CSE | Batch'23</b><br>
            Thesis: A Multi-Modal Smart Search Framework for Person Identification via Facial Recognition and Textual Retrieval
        </li>

        <li>
            <b>Shubham Srivastava | M.Tech. CSE | Batch'23</b><br>
            Thesis: Understanding Adversarial Attacks on Deep Neural Networks via Interactive Visual Analytics
        </li>

        <li>
            <b>Prashik Ganer | M.Tech. CSE | Batch'23 (Co-supervisor: Prof. Purushottam Kar)</b><br>
            Thesis: DAVi II - Design and Development of a Data Analytics and Visualization Platform
        </li>

        <li>
            <b>Manish Agrawal | M.Tech. CSE | Batch'23 (Co-supervisor: Prof. Purushottam Kar)</b><br>
            Thesis: DAVi I - Design and Development of a Data Analytics and Visualization Platform
        </li>

        <li>
            <b>Vishal Kumar | M.Tech. CyS | Batch'23</b><br>
            Thesis: Combating DeepFakes with GAN-Based Watermarking and Adversarial Robustness Evaluation
        </li>

        <li>
            <b>Atul Kumar | M.Tech. CSE | Batch'22</b><br>
            Thesis: Uncertainty-Aware Implicit Neural Networks for Visual Analytics of Complex Vector Fields
        </li>

        <li>
            <b>Abhay Kumar Dwivedi | M.Tech. CSE | Batch'22</b><br>
            Thesis: Implicit Neural Networks for Visual Analytics of Large Multivariate Data
        </li>

        <li>
            <b>Komal Yadav | M.Tech. CSE | Batch'22</b><br>
            Thesis: Impact of Adaptive Sampling for Building Comprerssive Neural Representations of Large Scientific Data
        </li>

        <li>
            <b>Vivek Kumar Gautam | M.Tech. CSE | Batch'22</b><br>
            Thesis: Efficient View Synthesis of Scientific Data via Deep Image Regression
        </li>

        <li>
            <b>Drashtant Singh Rathod | M.Tech. CSE | Batch'22</b><br>
            Project: Understanding Adversarial Attacks using Techniques of Explainability and Interactive Visual Analytics
        </li>
    </ul>
</details>



<h2 style="color:Chocolate;">BTech Students</h2>

<ul>
    <li>
        <b>Divit Shah [CSE]</b><br>
        Project Title: Structured Pruning Workflow for Implicit Neural Representations of 3D volume data
    </li>

    <li>
        <b>Devansh Gupta [SDS]</b><br>
        Project Title: Structured Pruning of SIREN Using High-Frequency Activation Scoring
    </li>
</ul>

<details>
    <summary style="cursor:pointer; color:#0066cc; font-weight:bold;">
        See Past Students
    </summary>

    <ul>

        <li>
            <b>Hardik Jindal [EE]</b><br>
            Project Title: MRL for Multiresolution Image Synthesis
        </li>

        <li>
            <b>Chitwan Goel [CSE]</b><br>
            Project Title: Local Latent Space Modeling of Multivariate Data for Feature Analysis and Data Reduction<br>
        <span style="color:red;"><b>*** Best UGP Award 2025 ***</b></span>
        </li>

        <li>
            <b>Tamidala Venkata Sai Pawan Chanukya Reddy [CSE]</b><br>
            Project Title: Visual Analysis of Optimization and Generalization in Neural Networks
        </li>

        <li>
            <b>Raghav Manglik [CSE]</b><br>
            Project Title: Bidirectional Generative Modelling for Transfer Function-Aware Explorable View Synthesis of 3D Data
        </li>

        <li>
            <b>Shrilakshmi S K [CSE]</b><br>
            Project Title: Autoencoder-Based Local Latent Modeling for Ensemble Data Compression and Feature Analysis
        </li>

        <li>
            <b>Palak Mishra [SDS]</b><br>
            Project Title: Efficient 3D Data Summarization and Recovery via Void-and-Cluster Sampling and Neural Network-based Reconstruction
        </li>

        <li>
            <b>Manasvi Jain [CSE]</b><br>
            Project Title: Local Latent Representations for Compressed and Interpretable 3D Scalar Data Analysis
        </li>

        <li>
            <b>Depanshu Sahu [CSE]</b><br>
            Project Title: In-Situ Copula Modeling for Large-Scale Simulations
        </li>

        <li>
            <b>Aarish Muhammad Khan [CE]</b><br>
            Project Title: Distribution Parameter Compression with SIREN
        </li>

        <li>
            <b>Chitwan Goel [CSE]</b><br>
            Project Title: Representing Large 3D Volumetric Data using Uncertainty-Aware Deep Learning Models<br>
            <span style="color:red;"><b>*** Best UGP Award 2025 ***</b></span>
        </li>

        <li>
            <b>Shrey Bansal [CSE]</b><br>
            Project Title: Representing Large 3D Volumetric Data using Uncertainty-Aware Deep Learning Models
        </li>

        <li>
            <b>Aditya Bangar [CSE]</b><br>
            Project Title: Uncertainty Aware Affective Behavior Analysis: Baseline Setup
        </li>

        <li>
            <b>Ahmad Amaan [ME]</b><br>
            Project Title: Evaluating Generative Models for Volume Visualization
        </li>

        <li>
            <b>Yerusu Dharini Reddy [EE]</b><br>
            Project Title: Evaluating CoordNet for Diverse Visualization Generation Tasks
        </li>

        <li>
            <b>Navya [EE]</b><br>
            Project Title: Evaluating CoordNet for Diverse Visualization Generation Tasks
        </li>

        <li>
            <b>Rashmi G R [CSE]</b><br>
            Project Title: Frailty Data Analysis and Visualization
        </li>

        <li>
            <b>Ayush Kumar [EE]</b><br>
            Project Title: Visualizing Impact of Uncertainty and Adversarial Attack on Deep Classifier Models
        </li>

        <li>
            <b>Yashwant Mahajan [EE]</b><br>
            Project Title: Visualizing Impact of Uncertainty and Adversarial Attack on Deep Classifier Models
        </li>

        <li>
            <b>Faheem Nizar [EE]</b><br>
            Project Title: Exploring Uncertainty in Deep Learning Models using Interactive Visual Analytics
        </li>

        <li>
            <b>Ahmad Amaan [ME]</b><br>
            Project Title: Estimation and Visual Analytics of Uncertainty in Deep Image Synthesizing Models
        </li>

        <li>
        <b>Narendra Singh (CSE) [SURGE Summer 2023]</b><br>
        Project Title: Visualizing Convolutional Neural Networks for Explainability and Interpretability
        </li>

         <li>
        <b>Soham Sen (AE) [SURGE Summer 2023]</b><br>
        Project Title: Visualizing Convolutional Neural Networks: Explainability and Interpretability
        <ul>
            <li><span style="color:red;">Best Project in Engineering Award</span></li>
            <li><span style="color:red;">Dr. Elizabeth and Dr. Varkey Cherian Award for Best Project</span></li>
        </ul>
        </li>

    </ul>
</details>


<h2 style="color:Chocolate;">Collaborators</h2>

<div class="collab-grid">

    <div class="collab-item">
        <a href="https://aacharya-cs.github.io/">Dr. Ayan Acharya</a> (Meta, USA)
    </div>

    <div class="collab-item">
        <a href="https://sites.google.com/view/cadak">Prof. Chandranath Adak</a> (IIT Patna, India)
    </div>

    <div class="collab-item">
        <a href="https://sites.google.com/site/zahidakhtarhome/home">Prof. Zahid Akhtar</a> (SUNY Poly., USA)
    </div>

    <div class="collab-item">
        <a href="https://tusharathawale.info/">Dr. Tushar Athawale</a> (Oak Ridge National Laboratory, USA)
    </div>

    <div class="collab-item">
        <a href="https://sites.google.com/site/soumi61/home">Prof. Soumi Chattopadhyay</a> (IIT Indore, India)
    </div>

    <div class="collab-item">
        <a href="https://users.cs.utah.edu/~crj/">Prof. Christopher R. Johnson</a> (University of Utah, USA)
    </div>

    <div class="collab-item">
        <a href="https://han-wei-shen.github.io/">Prof. Han-Wei Shen</a> (The Ohio State University, USA)
    </div>

    <div class="collab-item">
        <a href="https://sites.google.com/view/kochihwang">Prof. Ko-Chih Wang</a> (National Taiwan Normal University, Taiwan)
    </div>

</div>


