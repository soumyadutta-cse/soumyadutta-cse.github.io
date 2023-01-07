---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

<!-- Table style with CSS -->
<style type="text/css">
table {
    border: none;
    border-collapse: collapse;
}
td {
    border: none;
    background-color: #F2F2F2;
}
</style>


<!-- Publications -->
## Book Chapters

<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/topology_chapter.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[4]</strong> Roxana Bujack, <b>Soumya Dutta</b>, Duan Zhang, Tobias Gunther, <em>Objective Finite-Time Flow Topology from Flowmap Expansion and Contraction, Topological Methods in Data Analysis and Visualization VI, Springer</em>, 2021. [<a href="https://link.springer.com/chapter/10.1007/978-3-030-83500-2_7">Link</a>] [<a href="/papers/Roxana_TopoInVis_2019.pdf">Pdf</a>] [<a href="/bibtex/topology_chapter.bib">BibTex</a>] 
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        We extend the definition of the classic instantaneous vector field saddles, sinks, and sources to the finite-time setting by categorizing the domain based on the behavior of the flow map w.r.t. contraction or expansion. Since the intuitive Lagrangian approach turns out to be unusable in practice because it requires advection in unstable regions, we provide an alternative, sufficient criterion that can be computed in a robust way. We show that both definitions are objective, relate them to existing approaches, and show how the generalized critical points and their separatrices can be visualized.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/insitu_dist_book_chapter.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[3]</strong> <b>Soumya Dutta</b>, Subhashis Hazarika, and Han-Wei Shen, In Situ Statistical Distribution-based Data Summarization and Visual Analysis, <em>In Situ Visualization for Computational Science, Springer International Publishing</em>, 2022. [<a href="https://link.springer.com/chapter/10.1007/978-3-030-81627-8_4">Link</a>] [<a href="/papers/In_situ_distribution_chapter_preprint.pdf">Pdf</a>] [<a href="/bibtex/dist_chapter.bib">BibTex</a>] 
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        As we move towards the exascale computing era, the necessity of effective, scalable, and flexible data reduction techniques is becoming more and more prominent. This is primarily due to the bottleneck stemming from output data size and I/O speed compared to the ever-increasing computing speed as discussed. Therefore, data summarization techniques are needed that can work in the in situ environment, while the data is getting produced, and preserve the important information from the data compactly which will minimize information loss and enable a variety of post hoc analyses. The motivation for developing novel and effective data reduction techniques is discussed in the introductory chapter in detail. In this chapter, statistical distribution-based in situ data summaries are shown to be a pragmatic solution in this respect and is able to preserve important statistical data features. Using only the in situ generated statistical data summaries, which is significantly smaller in size compared to the original raw data, a wide range of data analysis and visualization tasks can be performed such as feature detection, extraction, tracking, query-driven analysis, etc. Besides these, when necessary, the full-resolution data reconstruction is also possible to visualize the data in its entirety with the added advantage of uncertainty quantification. In this part of the chapter, several distribution-based data modeling algorithms are presented along with their in situ performances and demonstrate the usefulness of the distribution data summaries through several application studies.
        </p>
      </details></td>
   </tr>
</table>

<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/cinema_chapter.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[2]</strong> David Rogers, <b>Soumya Dutta</b>, Divya Banesh, Terece L. Turton, Ethan Stam, and James Ahrens, In situ Solutions with CinemaScience, <em>In Situ Visualization for Computational Science, Springer International Publishing</em>, 2022. [<a href="https://link.springer.com/chapter/10.1007/978-3-030-81627-8_14">Link</a>] [<a href="/papers/cinema_chapter.pdf">Pdf</a>] [<a href="/bibtex/cinema_chapter.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
         As simulations move to exascale computing, the dominant data analysis and visualization paradigm will shift from primarily post hoc processing to in situ approaches in order to meet I/O bandwidth constraints. One such approach is Cinema, a flexible in situ visualization ecosystem. Cinema combines data extracts with viewers and analysis capabilities to support in situ, post hoc and hybrid approaches for data processing. With data extracts that include metadata, images, meshes, and other data types, Cinema databases generated in situ are a central component of post hoc analysis workflows. These workflows support visualization and exploration of the data, verification and validation tasks, and leverage computer vision and statistical techniques for post hoc analysis. This chapter describes the Cinema approach, the database specification, and demonstrates its use through example workflows.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/sampling_chapter.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[1]</strong> Ayan Biswas, <b>Soumya Dutta</b>, Terece Turton, and James Paul Ahrens, Sampling for Scientific Data Analysis and Reduction, <em>In Situ Visualization for Computational Science, Springer International Publishing</em>, 2022. [<a href="https://link.springer.com/chapter/10.1007/978-3-030-81627-8_2">Link</a>] [<a href="/papers/Sampling_Chapter.pdf">Pdf</a>] [<a href="/bibtex/sampling_chapter.bib">BibTex</a>]  
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
         With exascale supercomputers on the horizon, data-driven in situ data reduction is a very important topic that potentially enables post hoc data visualization, reconstruction, and exploration with the goal of minimal information loss. Sophisticated sampling methods provide a fast approximation to the data that can be used as a preview to the simulation output without the need for full data reconstruction. More detailed analysis can then be performed by reconstructing the sampled data set as necessary. Other data reduction methods such as compression techniques can still be used with the sampled outputs to achieve further data reduction. Sampling can be achieved in the spatial domain (which data locations are to be stored?) and/or temporal domain (which time steps to be stored?). Given a spatial location, data-driven sampling approaches take into account its local properties (such as scalar value, local smoothness etc.) and multivariate association among scalar values to determine the importance of a location. For temporal sampling, changes in the local and global properties across time steps are taken into account as importance criteria. In this chapter, spatial sampling approaches are discussed for univariate and multivariate data sets and their use for effective in situ data reduction is demontrated.
        </p>
      </details></td>
   </tr>
</table>



## Journal Publications


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/juliacon.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[15]</strong> Li Tang, <b>Soumya Dutta</b>, Natalie Klein, Wayne Yu Wang, Jonathan David Wolfe, Luke Van Roekel, Nathan Urban, Ayan Biswas, and Earl Lawrence, Julia for HPC: In Situ Data Analysis with Julia for Climate Simulations at Large Scale, <em>Proceedings of JuliaCon</em>.
      <b>[Under review]</b>
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        Fast-evolving data science techniques have enabled scientific dis- coveries in part by providing the ability to analyze large amounts of scientific data and extract relevant patterns. Scientific simulations offer a unique opportunity to study large-scale, complex systems, such as the Earth’s climate, under varying conditions and modeling assumptions. However, one major obstacle to improved utilization of large scientific simulations is the ever-increasing gap between computing speed, which continues to increase, and data I/O band- width, which remains relatively constant. This mismatch often pre- vents full utilization of the data; we are likely unable to save all of the generated data for analysis, and simple solutions such as saving compressed versions of the data for later analysis may be insuffi- cient to answer questions of interest.
        </p>
        <p>
        In situ data analysis techniques seek to address this issue by com- pleting analysis and pattern extraction from generated scientific data while the application is running, and the in situ data anal- ysis only involves compute and in-memory data I/O, which im- proves performance. However, one major challenge of employing in situ data analysis to legacy scientific applications is that mod- ern advanced data science techniques are usually not implemented in the same way as the scientific codes (typically, using the For- tran programming language with parallel programming models). To address this challenge, we develop an infrastructure for cou- pling a popular high-level data science programming language, Ju- lia, with the large-scale production-level climate code Energy Ex- ascale Earth System Model (E3SM) on high performance comput- ing (HPC) systems. To demonstrate the infrastructure, we develop two in situ data analysis methods in Julia and evaluate their per- formance and the infrastructure overhead. Our results show that our in situ Julia data analysis methods are able to detect extreme weather events and characterize climate patterns with insignifi- cant infrastructure overhead. Furthermore, our infrastructure allows user-friendly development and deployment of new Julia data anal- ysis modules without the need to recompile the simulation code, giving data analysts a simple new tool for in situ analysis.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/mfix_jocs.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[14]</strong> <b>Soumya Dutta</b>, Terece L. Turton, David Rogers, Jordan M. Musser, James Ahrens, and Ann S. Almgren, In Situ Feature Analysis for Large-scale Multiphase Flow Simulations, <em>Journal of Computational Science (Elsivier)</em>, Volume: 63, 2022.
      [<a href="https://doi.org/10.1016/j.jocs.2022.101773">Link</a>] [<a href="/papers/mfix_jour_comp_sc.pdf">Pdf</a>] [<a href="/bibtex/JCS_mfix.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        The study of multiphase flow is essential for designing chemical reactors such as fluidized bed reactors (FBR), as a detailed understanding of hydrodynamics is critical for optimizing reactor performance and stability. During complex chemical processes in an FBR, the formation of void regions in the reactor, generally termed as bubbles, is an important phenomenon. The study of these bubbles has a deep implication in predicting the reactor's overall efficiency. But physical experiments needed to understand bubble dynamics are costly and non-trivial due to the technical difficulties involved and harsh working conditions of the reactors. Therefore, to study such chemical processes and bubble dynamics, a state-of-the-art computational simulation MFIX-Exa is being developed. Despite the proven accuracy of MFIX-Exa in modeling bubbling phenomena, the large-scale output data prohibits the use of traditional post hoc analysis capabilities in both storage and I/O time. To address these issues and allow the application scientists to explore the bubble dynamics in an efficient and timely manner, we have developed an end-to-end analytics pipeline that enables in situ detection of bubbles, followed by a flexible post hoc visual exploration methodology of bubble dynamics. The proposed method enables interactive analysis of bubbles, along with quantification of several bubble characteristics, enabling experts to understand the bubble interactions in detail. Positive feedback from the experts has indicated the efficacy of the proposed approach for exploring bubble dynamics in very-large-scale multiphase flow simulations.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/Humayra_cise.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[13]</strong> Humayra Tasnim, <b>Soumya Dutta</b>, Terece L. Turton, David Rogers, and Melanie E. Moses, Information-theoretic Exploration of Multivariate Time-Varying Image Databases, <em>IEEE Computing in Science & Engineering (IEEE CiSE)</em>, 2022, Volume: 24, Issue 3, pp. 61 - 70. [<a href="https://ieeexplore.ieee.org/document/9826433">Link</a>] [<a href="/papers/multivar_humayra_cise.pdf">Pdf</a>] [[<a href="/bibtex/CiSE_info_theory.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        Modern scientific simulations produce very large datasets, making interactive exploration of such data computationally prohibitive. An increasingly common data reduction technique is to store visualizations and other data extracts in a database. The Cinema project is one such approach, storing visualizations in an image database for post hoc exploration and interactive image-based analysis. This work focuses on developing efficient algorithms that can quantify various types of multivariate dependencies existing within multi-variable datasets. It applies specific mutual information measures for the quantification of salient regions from multivariate image data. Using such information measures, the opacity of the images is modulated so that the salient regions are automatically highlighted and the domain scientists can interactively explore the most relevant regions for scientific discovery.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/jiayi_tvcg.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[12]</strong> Jiayi Xu, <b>Soumya Dutta</b>, Wenbin He, Joachim Moortgat, and Han-Wei Shen, Geometry-Driven Detection, Tracking and Visual Analysis of Viscous and Gravitational Fingers, <em>IEEE Transactions on Visualization and Computer Graphics (TVCG)</em>, 2022, Volume: 28, Issue 3, pp. 1514 - 1528. [<a href="https://ieeexplore.ieee.org/document/9170853">Link</a>] [<a href="/papers/Tvcg_Gravitational_Fingers.pdf">Pdf</a>] [<a href="/bibtex/TVCG_finger.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        Viscous and gravitational flow instabilities cause a displacement front to break up into finger-like fluids. The detection and evolutionary analysis of these fingering instabilities are critical in multiple scientific disciplines such as fluid mechanics and hydrogeology. However, previous detection methods of the viscous and gravitational fingers are based on density thresholding, which provides limited geometric information of the fingers. The geometric structures of fingers and their evolution are important yet little studied in the literature. In this work, we explore the geometric detection and evolution of the fingers in detail to elucidate the dynamics of the instability. We propose a ridge voxel detection method to guide the extraction of finger cores from three-dimensional (3D) scalar fields. After skeletonizing finger cores into skeletons, we design a spanning tree based approach to capture how fingers branch spatially from the finger skeletons. Finally, we devise a novel geometric-glyph augmented tracking graph to study how the fingers and their branches grow, merge, and split over time. Feedback from earth scientists demonstrates the usefulness of our approach to performing spatio-temporal geometric analyses of fingers.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:90px" src="/images/fuzzy_tracking.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[11]</strong> <b>Soumya Dutta</b>, Terece L. Turton, and James Ahrens, A Confidence-guided Technique for Tracking Time-varying Features, <em>IEEE Computing in Science & Engineering (IEEE CiSE)</em>, 2021, Volume 23, Issue 2, pp. 84-92. [<a href="https://ieeexplore.ieee.org/document/9311214">Link</a>] [<a href="/papers/CiSE_fuzzy_tracking.pdf">Pdf</a>] [[<a href="/bibtex/CiSE_tracking.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        Application scientists often employ feature tracking algorithms to capture the temporal evolution of various features in their simulation data. However, as the complexity of the scientific features is increasing with the advanced simulation modeling techniques, quantification of reliability of the feature tracking algorithms is becoming important. One of the desired requirements for any robust feature tracking algorithm is to estimate its confidence during each tracking step so that the results obtained can be interpreted without any ambiguity. To address this, we develop a confidence-guided feature tracking algorithm that allows reliable tracking of user-selected features and presents the tracking dynamics using a graph-based visualization along with the spatial visualization of the tracked feature. The efficacy of the proposed method is demonstrated by applying it to two scientific data sets containing different types of time-varying features.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/tvcg_sampling.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[10]</strong> Ayan Biswas, <b>Soumya Dutta</b>, Earl Lawrence, John M. Patchett, Jon C. Calhoun, and James Ahrens, Probabilistic Data-Driven Sampling via Multi-Criteria Importance Analysis, <em>IEEE Transactions on Visualization and Computer Graphics (TVCG)</em>, 2021, Volume 27, Issue 12, pp. 4439-4454. [<a href="https://ieeexplore.ieee.org/document/9130956">Link</a>] [<a href="/papers/TVCG_2019_Sampling.pdf">Pdf</a>]  [<a href="/bibtex/TVCG_sampling.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        Although supercomputers are becoming increasingly powerful, their components have thus far not scaled proportionately. Compute power is growing enormously and is enabling finely resolved simulations that produce never-before-seen features. However, I/O capabilities lag by orders of magnitude, which means only a fraction of the simulation data can be stored for post hoc analysis. Prespecified plans for saving features and quantities of interest do not work for features that have not been seen before. Data-driven intelligent sampling schemes are needed to detect and save important parts of the simulation while it is running. Here, we propose a novel sampling scheme that reduces the size of the data by orders-of-magnitude while still preserving important regions. The approach we develop selects points with unusual data values and high gradients. We demonstrate that our approach outperforms traditional sampling schemes on a number of tasks. 
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/mfix_cise.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[9]</strong> Ayan Biswas, James Ahrens, <b>Soumya Dutta</b>, Jordan Musser, Ann Almgren, and Terece Turton, Feature Analysis, Tracking, and Data Reduction: An Application to Multiphase Reactor Simulation MFiX-Exa for In-Situ Use Case, <em>IEEE Computing in Science & Engineering (IEEE CiSE)</em>, 2021, Volume 23, Issue 1, pp. 75-82. [<a href="https://ieeexplore.ieee.org/document/9167432">Link</a>] [<a href="/papers/cise_mfix.pdf">Pdf</a>] [<a href="/bibtex/CiSE_mfix.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        As we enter the exascale computing regime, powerful supercomputers continue to produce much higher amounts of data than what can be stored for offline data processing. To utilize such high compute capabilities on these machines, much of the data processing needs to happen in situ, when the full high-resolution data is available at the supercomputer memory. In this article, we discuss our MFiX-Exa simulation, which models multiphase flow by tracking a very large number of particles through the simulation domain. In one of the use cases, the carbon particles interact with air to produce carbon dioxide bubbles from the reactor. These bubbles are of primary interest to the domain experts for these simulations. For this particle-based simulation, we propose a streaming technique that can be deployed in situ to efficiently identify the bubbles, track them over time, and use them to down-sample the data with minimal loss in these features.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/childs_insitu_terminology.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[8]</strong> Hank Childs, Sean D. Ahern, James Ahrens, Andrew C. Bauer, Janine Bennett, E. Wes Bethel, Peer-Timo Bremer, Eric Brugger, Joseph Cottam, Matthieu Dorier, <b>Soumya Dutta</b>, Jean M. Favre, Thomas Fogal, Steffen Frey, Christoph Garth, Berk Geveci, William F. Godoy, Charles D. Hansen, Cyrus Harrison, Bernd Hentschel, Joseph Insley, Chris R. Johnson, Scott Klasky, Aaron Knoll, James Kress, Matthew Larsen, Jay Lofstead, Kwan-Liu Ma, Preeti Malakar, Jeremy Meredith, Kenneth Moreland, Paul Navrátil, Patrick O’Leary, Manish Parashar, Valerio Pascucci, John Patchett, Tom Peterka, Steve Petruzza, Norbert Podhorszki, David Pugmire, Michel Rasquin, Silvio Rizzi, David H. Rogers, Sudhanshu Sane, Franz Sauer, Robert Sisneros, Han-Wei Shen, Will Usher, Rhonda Vickery, Venkatram Vishwanath, Ingo Wald, Ruonan Wang, Gunther H. Weber, Brad Whitlock, Matthew Wolf, Hongfeng Yu, Sean B. Ziegeler, A Terminology for In Situ Visualization and Analysis Systems, <em>International Journal of High Performance Computing Applications (IJHPCA)</em>, 2020, Volume 34, Issue 6, pp. 676-691. [<a href="https://doi.org/10.1177/1094342020935991">Link</a>] [<a href="/papers/Hank_IJHPCA_2020.pdf">Pdf</a>] [<a href="/bibtex/IJHPCA_insitu.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        The term “in situ processing” has evolved over the last decade to mean both a specific strategy for visualizing and analyzing data and an umbrella term for a processing paradigm. The resulting confusion makes it difficult for visualization and analysis scientists to communicate with each other and with their stakeholders. To address this problem, a group of over fifty experts convened with the goal of standardizing terminology. This paper summarizes their findings and proposes a new terminology for describing in situ systems. An important finding from this group was that in situ systems are best described via multiple, distinct axes: integration type, proximity, access, division of execution, operation controls, and output type. This paper discusses these axes, evaluates existing systems within the axes, and explores how currently used terms relate to the axes.
        </p>
      </details></td>
   </tr>
</table>

<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/PMI_sampling_entropy.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[7]</strong> <b>Soumya Dutta</b>, Ayan Biswas, and James Ahrens, Multivariate Pointwise Information-driven Data Sampling and Visualization, <em>MDPI Entropy (Special issue in Information Theory Application in Visualization)</em>, 2019, Volume 21, Issue 7. [<a href="https://www.mdpi.com/1099-4300/21/7/699">Link</a>] [<a href="/papers/multivarsampling_entropy_2019.pdf">Pdf</a>] [<a href="/bibtex/ENTROPY_sampling.bib">BibTex</a>] 
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        With increasing computing capabilities of modern supercomputers, the size of the data generated from the scientific simulations is growing rapidly. As a result, application scientists need effective data summarization techniques that can reduce large-scale multivariate spatiotemporal data sets while preserving the important data properties so that the reduced data can answer domain-specific queries involving multiple variables with sufficient accuracy. While analyzing complex scientific events, domain experts often analyze and visualize two or more variables together to obtain a better understanding of the characteristics of the data features. Therefore, data summarization techniques are required to analyze multi-variable relationships in detail and then perform data reduction such that the important features involving multiple variables are preserved in the reduced data. To achieve this, in this work, we propose a data sub-sampling algorithm for performing statistical data summarization that leverages pointwise information theoretic measures to quantify the statistical association of data points considering multiple variables and generates a sub-sampled data that preserves the statistical association among multi-variables. Using such reduced sampled data, we show that multivariate feature query and analysis can be done effectively. The efficacy of the proposed multivariate association driven sampling algorithm is presented by applying it on several scientific data sets.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/codda_tvcg.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[6]</strong> Subhashis Hazarika, <b>Soumya Dutta</b>, Han-Wei Shen, and Jen-Ping Chen, CoDDA: A Flexible Copula-based Distribution Driven Analysis Framework for Large-Scale Multivariate Data, <em>IEEE Transactions on Visualization and Computer Graphics (TVCG)</em>, 2019, Volume 25, Issue 1, pp. 1214-1224. [<a href="https://ieeexplore.ieee.org/document/8440043">Link</a>] [<a href="/papers/tvcg_hazarika_vis18_copula.pdf">Pdf</a>] [<a href="/bibtex/TVCG_codda.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        CoDDA (Copula-based Distribution Driven Analysis) is a flexible framework for large-scale multivariate datasets. A common strategy to deal with large-scale scientific simulation data is to partition the simulation domain and create statistical data summaries. Instead of storing the high-resolution raw data from the simulation, storing the compact statistical data summaries results in reduced storage overhead and alleviated I/O bottleneck. Such summaries, often represented in the form of statistical probability distributions, can serve various post-hoc analysis and visualization tasks. However, for multivariate simulation data using standard multivariate distributions for creating data summaries is not feasible. They are either storage inefficient or are computationally expensive to be estimated in simulation time (in situ) for large number of variables. In this work, using copula functions, we propose a flexible multivariate distribution-based data modeling and analysis framework that offers significant data reduction and can be used in an in situ environment. The framework also facilitates in storing the associated spatial information along with the multivariate distributions in an efficient representation. Using the proposed multivariate data summaries, we perform various multivariate post-hoc analyses like query-driven visualization and sampling-based visualization. We evaluate our proposed method on multiple real-world multivariate scientific datasets. To demonstrate the efficacy of our framework in an in situ environment, we apply it on a large-scale flow simulation.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/hazarika_entropy_2018.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[5]</strong> Subhashis Hazarika, Ayan Biswas, <b>Soumya Dutta</b>, and Han-Wei Shen, Information Guided Exploration of Scalar Values and Isocontours in Ensemble Datasets, <em>MDPI Entropy (Special issue in Information Theory Application in Visualization)</em>, 2018, Volume 20, Issue 7. [<a href="https://www.mdpi.com/1099-4300/20/7/540">Link</a>] [<a href="/papers/hazarika_entropy_info_theory.pdf">Pdf</a>] [<a href="/bibtex/ENTROPY_info_theory.bib">BibTex</a>] 
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        Uncertainty of scalar values in an ensemble dataset is often represented by the collection of their corresponding isocontours. Various techniques such as contour-boxplot, contour variability plot, glyphs, and probabilistic marching-cubes assume that a scalar value of interest is already known to the user. Not much work has been done in guiding users to select the scalar values for such analysis. We propose a new information-theoretic approach by using specific information measures to evaluate the overall uncertainty associated with all the scalar values in an ensemble system. This helps the scientist to understand the effects of uncertainty on different data features. To understand in finer details the contribution of individual members towards the uncertainty of the ensemble isocontours of a selected scalar value, we propose a conditional entropy based algorithm to quantify the individual contributions. This can help simplify analysis and visualization for systems with more members by identifying the members contributing the most towards overall uncertainty.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/stall_vis16.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[4]</strong> <b>Soumya Dutta</b>, Chun-Ming Chen, Gregory Heinlein, Han-Wei Shen, and Jen-Ping Chen, In Situ Distribution Guided Analysis and Visualization of Transonic Jet Engine Simulations, <em>IEEE Transactions on Visualization and Computer Graphics (TVCG)</em>, 2017, Volume 23, Issue 1, pp. 811-820. [<a href="https://ieeexplore.ieee.org/document/7539561">Link</a>] [<a href="/papers/Vis16_insitu.pdf">Pdf</a>] [<a href="/bibtex/TVCG_turbine_insitu.bib">BibTex</a>] <b><span style="color: red">[Best Paper Honorable Mention Award]</span></b>
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        Study of flow instability in turbine engine compressors is crucial to understand the inception and evolution of engine stall. A state-of-the-art Navier-Stokes based, time-accurate computational fluid dynamics simulator, TURBO, has been developed in NASA to enhance the understanding of flow phenomena undergoing rotating stall. Despite the proven high modeling accuracy of TURBO, the excessive simulation data prohibits post-hoc analysis in both storage and I/O time. To address these issues and allow the expert to perform scalable stall analysis, we have designed an in situ distribution guided stall analysis technique. Our method summarizes statistics of important properties of the simulation data in situ using a probabilistic data modeling scheme. This data summarization enables statistical anomaly detection for flow instability in post analysis, which reveals the spatio-temporal trends of rotating stall for the expert to conceive new hypotheses.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/vis15_tracking.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[3]</strong> <b>Soumya Dutta</b> and Han-Wei Shen, Distribution Driven Extraction and Tracking of Features for Time-varying Data Analysis, <em>IEEE Transactions on Visualization and Computer Graphics (TVCG)</em>, 2016, Volume 22, Issue 1, pp. 837-846. [<a href="https://ieeexplore.ieee.org/document/7192664">Link</a>] [<a href="/papers/Vis_15.pdf">Pdf</a>] [<a href="/bibtex/TVCG_tracking.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        Effective analysis of features in time-varying data is essential in numerous scientific applications. Feature extraction and tracking are two important tasks scientists rely upon to get insights about the dynamic nature of the large scale time-varying data. However, often the complexity of the scientific phenomena only allows scientists to vaguely define their feature of interest. Furthermore, such features can have varying motion patterns and dynamic evolution over time. In this work, we investigate these issues and propose a distribution driven approach which allows us to construct novel algorithms for reliable feature extraction and tracking with high confidence. We exploit two key properties of an object, motion and similarity to the target feature, and fuse the information gained from them to generate a robust feature-aware classification field at every time step. Tracking of features is done using such classified fields which enhances the accuracy and robustness of the proposed algorithm.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/vis15_stall.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[2]</strong> Chun-Ming Chen, <b>Soumya Dutta</b>, Xiaotong Liu, Gregory Heinlein, Han-Wei Shen, and Jen-Ping Chen, Visualization and Analysis of Rotating Stall for Transonic Jet Engine Simulation, <em>IEEE Transactions on Visualization and Computer Graphics (TVCG)</em>, 2016, Volume 22, Issue 1, pp. 847-856. [<a href="https://ieeexplore.ieee.org/document/7192672">Link</a>] [<a href="/papers/Vis_15_stall.pdf">Pdf</a>] [<a href="/bibtex/TVCG_turbine.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        Identification of early signs of rotating stall is essential for the study of turbine engine stability. With recent advancements of high performance computing, high-resolution unsteady flow fields allow in depth exploration of rotating stall and its possible causes. Performing stall analysis, however, involves significant effort to process large amounts of simulation data, especially when investigating abnormalities across many time steps. In order to assist scientists during the exploration process, we present a visual analytics framework to identify suspected spatiotemporal regions through a comparative visualization so that scientists are able to focus on relevant data in more detail. To achieve this, we propose efficient stall analysis algorithms derived from domain knowledge and convey the analysis results through juxtaposed interactive plots. Using our integrated visualization system, scientists can visually investigate the detected regions for potential stall initiation and further explore these regions to enhance the understanding of this phenomenon. Positive feedback from scientists demonstrate the efficacy of our system in analyzing rotating stall.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/vis13_tvcg.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[1]</strong> Ayan Biswas, <b>Soumya Dutta</b>, Han-Wei Shen, and Jonathan Woodring, An Information-Aware Framework for Exploring Multivariate Data Sets, <em>IEEE Transactions on Visualization and Computer Graphics (TVCG)</em>, 2013, Volume 19, Issue 12, pp. 2683-2692. [<a href="https://ieeexplore.ieee.org/document/6634187">Link</a>] [<a href="/papers/Vis13_Info_theory.pdf">Pdf</a>] [<a href="/bibtex/TVCG_info_theory.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        Information theory provides a theoretical framework for measuring information content for an observed variable, and has attracted much attention from visualization researchers for its ability to quantify saliency and similarity among variables. In this paper, we present a new approach towards building an exploration framework based on information theory to guide the users through the multivariate data exploration process. In our framework, we compute the total entropy of the multivariate data set and identify the contribution of individual variables to the total entropy. The variables are classified into groups based on a novel graph model. The variables inside the groups are analyzed for their representativeness and an information based importance is assigned. We exploit specific information metrics to analyze the relationship between the variables and use the metrics to choose isocontours of selected variables. Experiments with different data sets reveal the effectiveness of our proposed framework in depicting the interesting regions of the data sets taking into account the interaction among the variables.
        </p>
      </details></td>
   </tr>
</table>






## Conference/Workshop Publications

<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/mfix_woiv.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[19]</strong> <b>Soumya Dutta</b>, Dan Lipsa, Terece L. Turton, Berk Geveci, and James Ahrens, In Situ Analysis and Visualization of Extreme-Scale Particle Simulations, <em>WOIV: 6th International Workshop on In Situ Visualization</em>, 2022 (co-located with ISC High Performance Conference). [<a href="https://link.springer.com/chapter/10.1007/978-3-031-23220-6_19">Link</a>] [<a href="/papers/WOIV_MFIX_insitu_catalyst.pdf">Pdf</a>] [BibTex]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        In situ analysis has emerged as a dominant paradigm for performing scalable visual analysis of extreme-scale computational simulation data. Compared to the traditional post hoc analysis pipeline where data is first stored into disks and then analyzed offline, in situ analysis processes data at the time its generation in the supercomputers so that the slow and expensive disk I/O is minimized. In this work, we present a new in situ visual analysis pipeline for the extreme-scale multiphase flow simulation MFiX-Exa and demonstrate how the pipeline can be used to process large particle fields in situ and produce informative visualizations of the data features. We deploy our analysis pipeline on Oak Ridge's Summit supercomputer to study its in situ applicability and usefulness.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/mfix_sc_video.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[18]</strong> Alexandra R. Stewart, Terece L. Turton, David H. Rogers, James P. Ahrens, and <b>Soumya Dutta</b>, <em>Visualization of MFIX-Exa Simulation Data for Chemical Looping Combustion</em>, SC22 Scientific Visualization and Data Analytics Showcase, 2022. [Link] [<a href="/papers/mfix_sc_video_paper.pdf">Pdf</a>] [BibTex]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        In the United States, fossil-fuel related industrial processes account for approximately half of all greenhouse gas emissions in the United States. Wide-scale implementation of Carbon-Capture Technologies such as Chemical Looping Reactors (CLRs) provide a promising path to reducing carbon emissions. However, scale-up and testing of these systems is expensive and time-consuming. In recent years, scientists have developed computational tools to simulate multiphase reactors to reduce scaling and testing costs by harnessing the power of HPC. In particular, understanding bubble dynamics in fluidized beds is important to scientists studying multiphase flows in order to design efficient, cost-effective chemical looping reactors. In our video, we highlight scientific use cases of the MFiX-Exa simulation for a general science audience and outline the importance of Los Alamos National Laboratory’s (LANL) in situ statistical feature detection algorithm in identifying the features of interest in the MFiX-Exa data; and the use of LANL’s Cinema visualization tool to create a novel post hoc workflow. In particular, we highlight MFiX-Exa, which provides new computing capabilities needed to combine CFD-DEM simulation with computing at the Exascale via an adaptive mesh refinement (AMReX) framework. Visualizations were run in ParaView and the rendering in our model visualizes bubble features as well as fluid velocity of fluid in the fluidized bed. Average rise velocities from the particle data were estimated and saved for comparison and overlayed in the background of the visualized bubbles to study fluid features. We discuss the influence of exascale computing in the future of CLR and Carbon capture technologies.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/ieeebigdata_I1_summarization.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[17]</strong> <b>Soumya Dutta</b>, Humayra Tasnim, Terece L. Turton, and James Ahrens, In Situ Adaptive Spatio-Temporal Data Summarization, <em>IEEE International Conference on Big Data (IEEE Bigdata)</em>, 2021, pp. 315-321. [<a href="https://ieeexplore.ieee.org/document/9671581">Link</a>] [<a href="/papers/IEEEBigData_I1_based_summarization.pdf">Pdf</a>] [<a href="/bibtex/Bigdata_fusion.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        Scientists nowadays use data sets generated from large-scale scientific computational simulations to understand the intricate details of various physical phenomena. These simulations produce large volumes of data at a rapid pace, containing thousands of time steps so that the spatio-temporal dynamics of the modeled phenomenon and its associated features can be captured with sufficient detail. Storing all the time steps into disks to perform traditional offline analysis will soon become prohibitive as the gap between the data generation speed and disk I/O speed continues to increase. In this work, we present an information-theoretic approach for in situ reduction of large-scale time-varying data sets via a combination of key and fused time steps. We show that this approach can greatly minimize the output data storage while preserving the temporal evolution of data. A detailed in situ application study is carried out to demonstrate the in situ viability of our technique for efficiently summarizing thousands of time steps generated from a large-scale real-life computational simulation code. 
        </p>
      </details></td>
   </tr>
</table>

<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/isav_21.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[16]</strong> <b>Soumya Dutta</b>, Natalie Klein, Li Tang, Jonathan Wolfe, Luke Van Roekel, James Benedict, Ayan Biswas, Earl Lawrence, and Nathan Urban, In Situ Climate Modeling for Analyzing Extreme Weather Events, <em>In Situ Infrastructures for Enabling Extreme-scale Analysis and Visualization (ISAV 2021)</em>, pp. 18-23, co-located with SC 2021. [<a href="https://dl.acm.org/doi/10.1145/3490138.3490142">Link</a>] [<a href="/papers/SSW_GEV_ISAV21.pdf">Pdf</a>]  [<a href="/bibtex/ISAV_climate_modeling.bib">BibTex</a>] <b><span style="color: red">[Best Paper Award]</span></b>
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        The study of many extreme weather events requires simulations with high spatiotemporal data that can grow in size quickly. Storing all the raw data from such a large-scale simulation for traditional post hoc analyses is soon going to be prohibitive as the data generation speed is outpacing the data storage capability in supercomputers. In situ analysis has emerged as a solution to this problem; data is analyzed when it is being produced, bypassing the slower disk input/output (I/O). In this work, we develop an in situ analysis pathway for Energy Exascale Earth System Model (E3SM) and propose an algorithm for analyzing the impacts of sudden stratospheric warmings (SSWs), which can cause extreme cold temperature outbreaks at the surface, resulting in hazardous weather and disrupting many socioeconomic sectors. We detect SSWs and model the surface temperature data distributions in situ and show that post hoc analysis using the distribution models can predict the impact of SSWs in the continental United States.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/envirvis_2019.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[15]</strong> <b>Soumya Dutta</b>, Riley X. Brady, Mathew E. Maltrud, Philip Wolfram, and Roxana Bujack, <em>Leveraging Lagrangian Analysis for Discriminating Nutrient Origins, Visualization in Environmental Sciences (EnvirVis)</em>, 2019, pp. 17-24. [<a href="https://doi.org/10.2312/envirvis.20191100">Link</a>] [<a href="/papers/envirvis_2019.pdf">Pdf</a>] [<a href="/bibtex/Envirvis_lagrange.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        Understanding the origins of nutrients, e.g., nitrate, in ocean water is essential to develop an effective mariculture technique for free-floating macroalgae, which presents a potential solution to provide an alternative source of domestic renewable fuels to help reduce carbon emissions from automobiles. To study this problem, scientists simulate large-scale computational simulations with coupled flow and nutrient information. Since running the simulation multiple times is expensive, the scientists want to have efficient visual-analytic techniques that can analyze and visualize the simulation output quickly to investigate the reasons behind the existence of nitrate in different areas of ocean water. To address these needs, a mixed Lagrangian and Eulerian-based analysis technique is developed that leverages traditional Lagrangian analysis methods and fuses Eulerian information with it to comprehend the origins of nutrients in the water. The proposed method yielded promising results for the application scientists and positive feedback from them demonstrates the efficacy of the technique.
        </p>
      </details></td>
   </tr>
</table>

<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/topoinvis_2019.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[14]</strong> Roxana Bujack, <b>Soumya Dutta</b>, Duan Zhang, Tobias Gunther, <em>Objective Finite-Time Flow Topology from Flowmap Expansion and Contraction, Workshop on  Topological Methods in Data Analysis and Visualization (TopoInVis)</em>, 2019. [<a href="https://cgl.ethz.ch/publications/papers/paperBuj19b.php">Link</a>] [<a href="/papers/Roxana_TopoInVis_2019.pdf">Pdf</a>] [<a href="/bibtex/Topoinvis_topology.bib">BibTex</a>] <b><span style="color: red">[Best Paper Award]</span></b>
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        We extend the definition of the classic instantaneous vector field saddles, sinks, and sources to the finite-time setting by categorizing the domain based on the behavior of the flow map w.r.t. contraction or expansion. Since the intuitive Lagrangian approach turns out to be unusable in practice because it requires advection in unstable regions, we provide an alternative, sufficient criterion that can be computed in a robust way. We show that both definitions are objective, relate them to existing approaches, and show how the generalized critical points and their separatrices can be visualized.
        </p>
      </details></td>
   </tr>
</table>



<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/eurovis_shoprt_2019.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[13]</strong> Roxana Bujack, <b>Soumya Dutta</b>, Irene Baeza Rojo, Duan Zhang, Tobias Gunther, <em>Objective Finite-Time Saddles and their Connection to FTLE, EG/VGTC Conference on Visualization (EuroVis Short Paper)</em>, 2019, pp. 49-53. [<a href="https://doi.org/10.2312/evs.20191169">Link</a>] [<a href="/papers/Roxana_Evis_2019.pdf">Pdf</a>] [<a href="/bibtex/Evis_topology.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        Based on an intuitive physical definition of what a finite-time saddle-like behavior is, we derive a mathematical definition. We show that this definition builds the link between two FTLE-based saddle generalizations, which is not only of theoretical interest but also provides a more robust extraction of finite-time saddles.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/pvis2018_fuzzy_insitu.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[12]</strong> <b>Soumya Dutta</b>, Han-Wei Shen, and Jen-Ping Chen, In Situ Prediction Driven Feature Analysis in Jet Engine Simulations, <em>IEEE Pacific Visualization Symposium (IEEE PacificVis)</em>, 2018, pp. 66-75. [<a href="https://ieeexplore.ieee.org/document/8365977">Link</a>] [<a href="/papers/pvis_18_fuzzy_insitu.pdf">Pdf</a>] [<a href="/bibtex/Pvis_fuzzy_stall.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        Efficient feature exploration in large-scale data sets using traditional post-hoc analysis approaches is becoming prohibitive due to the bottleneck stemming from I/O and output data sizes. This problem becomes more challenging when an ensemble of simulations are required to run for studying the influence of input parameters on the model output. As a result, scientists are inclining more towards analyzing the data in situ while it resides in the memory. In this work, we study the evolution of rotating stall in jet engines using data generated from a large-scale flow simulation under various input conditions. Since the features of interest lack a precise descriptor, we adopt a fuzzy rule based machine learning algorithm for efficient and robust extraction of such features. For scalable exploration, we advocate for an off-line learning and in situ prediction driven strategy that facilitates in-depth study of the stall. We verify and validate our method through comprehensive expert evaluation demonstrating the efficacy of our approach. 
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/tzu_sampling_pvis_18.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[11]</strong> Tzu-Hsuan Wei, <b>Soumya Dutta</b>, and Han-Wei Shen, Information Guided Data Sampling and Recovery using Bitmap Indexing, <em>IEEE Pacific Visualization Symposium (IEEE PacificVis)</em>, 2018, pp. 56-65. [<a href="https://ieeexplore.ieee.org/document/8365976">Link</a>] [<a href="/papers/pvis18_tzu_sampling.pdf">Pdf</a>] [<a href="/bibtex/Pvis_sampling.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        Creating a data representation is a common approach for efficient and effective data management and exploration. The compressed bitmap indexing is one of the emerging data representation used for large-scale data exploration. Performing sampling on the bitmap-indexing based data representation allows further reduction of storage overhead and be more flexible to meet the requirements of different applications. In this paper, we propose two approaches to solve two potential limitations when exploring and visualizing the data using sampling-based bitmap indexing data representation. First, we propose an adaptive sampling approach called information guided stratified sampling (IGStS) for creating compact sampled datasets that preserves the important characteristics of the raw data. Furthermore, we propose a novel data recovery approach to reconstruct the irregular subsampled dataset into a volume dataset with regular grid structure for qualitative post-hoc data exploration and visualization. The quantitative and visual efficacy of our proposed data sampling and recovery approaches are demonstrated through multiple experiments and applications.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/isav_sampling_18.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[10]</strong> Ayan Biswas, <b>Soumya Dutta</b>, Jesus Pulido, and James Ahrens, In Situ Data-Driven Adaptive Sampling for Large-scale Simulation Data Summarization, <em>In Situ Infrastructures for Enabling Extreme-scale Analysis and Visualization (ISAV)</em>, pp. 13-18, co-located with SC 2018. [<a href="https://dl.acm.org/doi/10.1145/3281464.3281467">Link</a>] [<a href="/papers/isav_sampling.pdf">Pdf</a>] [<a href="/bibtex/ISAV_sampling.bib">BibTex</a>] 
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        Recent advancements in high-performance computing have enabled scientists to model various scientific phenomena in great detail. However, the analysis and visualization of the output data from such large-scale simulations are posing significant challenges due to their excessive size and disk I/O bottlenecks. In this work,we propose an information-driven data sampling technique and compare it with two well-known sampling methods to demonstrate the superiority of the proposed method. The in situ performance of the proposed method is evaluated by applying it to the Nyx Cosmology simulation. We compare and contrast the performance of these various sampling algorithms and provide a holistic view of all the methods so that the scientists can choose appropriate sampling schemes based on their analysis requirements.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/isav_trigger_18.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[9]</strong> Matthew Larsen, Amy Woods, Nicole Marsaglia, Ayan Biswas, <b>Soumya Dutta</b>, Cyrus Harrison, and Hank Childs, A Flexible System For In Situ Triggers, <em>In Situ Infrastructures for Enabling Extreme-scale Analysis and Visualization (ISAV 2018)</em>, pp. 1-6, co-located with SC 2018. [<a href="https://dl.acm.org/doi/10.1145/3281464.3281468">Link</a>] [<a href="/papers/isav_trigger.pdf">Pdf</a>] [<a href="/bibtex/ISAV_trigger.bib">BibTex</a>] <b><span style="color: red">[Best Paper Award]</span></b>
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        Triggers are an important mechanism for adapting visualization, analysis, and storage actions. With this work, we describe the Ascent in situ infrastructure’s system for triggers. This system splits triggers into two components: when to per- form an action and what actions to perform. The decision for when to perform an action can be based on different types of factors, such as mesh topology, scalar fields, or performance data. The actions to perform are also varied, ranging from the traditional action of saving simulation state to disk to performing arbitrary visualizations and analyses. We also include details on the implementation and short examples demonstrating how the system can be used.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/slic_pvis.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[8]</strong> <b>Soumya Dutta</b>, Jonathan Woodring, Han-Wei Shen, Jen-Ping Chen, and James Ahrens, Homogeneity Guided Probabilistic Data Summaries for Analysis and Visualization of Large-Scale Data Sets, <em>IEEE Pacific Visualization Symposium (IEEE PacificVis)</em>, 2017, 111-120. [<a href="https://ieeexplore.ieee.org/document/8031585">Link</a>] [<a href="/papers/PVis17.pdf">Pdf</a>] [<a href="/bibtex/Pvis_dist_summary.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        High-resolution simulation data sets provide plethora of information, which needs to be explored by application scientists to gain enhanced understanding about various phenomena. Visual-analytics techniques using raw data sets are often expensive due to the data sets' extreme sizes. But, interactive analysis and visualization is crucial for big data analytics, because scientists can then focus on the important data and make critical decisions quickly. To assist efficient exploration and visualization, we propose a new region-based statistical data summarization scheme. Our method is superior in quality, as compared to the existing statistical summarization techniques, with a more compact representation, reducing the overall storage cost. The quantitative and visual efficacy of our proposed method is demonstrated using several data sets along with an in situ application study for an extreme-scale flow simulation.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/PMI_SA17.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[7]</strong> <b>Soumya Dutta</b>, Xiaotong Liu, Ayan Biswas, Han-Wei Shen, and Jen-Ping Chen, Pointwise Information Guided Visual Analysis of Time-varying Multi-fields, <em>SA'17, SIGGRAPH Asia Symposium on Visualization</em>, 2017. [<a href="https://dl.acm.org/doi/10.1145/3139295.3139298">Link</a>] [<a href="/papers/siggraph_vis17.pdf">Pdf</a>] [<a href="/bibtex/SIGASIA_pmi.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        Identification of salient features from a time-varying multivariate system plays an important role in scientific data understanding. In this work, we present a unified analysis framework based on mutual information and two of its decomposition to quantify the amount of information content between different value combinations from multiple variables over time. The pointwise mutual information (PMI), computed for each value combination, is used to construct informative scalar fields, which allow close examination of combined and complementary information possessed by multiple variables. Since PMI gives us a way of quantifying information shared among all combinations of scalar values for multiple variables, it is used to identify salient isovalue tuples. Simultaneous visualization of isosurfaces on those selected tuples depicts combined or complementary relationships in the data. For intuitive interaction with the data, an interactive interface is designed based on the proposed information-theoretic measures. Finally, successful application of the proposed method on two time-varying data sets demonstrates the efficacy of the system. 
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/Greg_stall_2017.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[6]</strong> Gregory Heinlein, Jen-Ping Chen, Chun-Ming Chen, <b>Soumya Dutta</b>, and Han-Wei Shen, Statistical Anomaly Based Study of Rotating Stall in a Transonic Axial Compressor Stage, <em>Turbomachinery Technical Conference & Exposition (ASME Turbo Expo, GT 2017)</em>. [<a href="https://doi.org/10.1115/GT2017-64685">Link</a>] [<a href="/papers/Greg_GT_paper.pdf">Pdf</a>] [<a href="/bibtex/Turbo_turbine.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        Tip clearance flow in transonic rotors is known to have a significant effect on compressor performance and stability. The purpose of this study is to employ a novel statistical analysis method as a stall precursor detector and investigate the flow physics underlying stall inception. To allow for natural stall evolution, a full annulus simulation of a transonic axial compressor stage (NASA Stage 35) was performed. Due to the size of the data set, a novel statistical analysis method was employed to rapidly analyze the entire spatial and temporal simulation domain. The analysis method involved utilizing a Grubb’s test pointwise on the domain’s grid for Entropy to reveal regions, times, and trends that are statistically anomalous and could be of interest for future evaluation. Through use of the anomaly detecting Grubb’s test rotating stall, which developed in the stage, could be tracked back in time to immediately after the computed mass flow stabilization of a particular operating condition. It was determined that an 18th order modal behavior dominated the pre-stall regime of NASA stage 35 operating in a near stall condition. The modal behavior was a result of a spiral-type vortex breakdown of the tip clearance vortex after interacting with the passage shock. A rotating disturbance region, moving faster than the rotor speed, amplified an instability within the spiral-type vortex breakdown. The growth of the instability caused the amplitude of the spiral-type vortex breakdown to increase in the radial and circumferential directions. Eventually, the disturbance region broke down into rotating stall due to decreased mass flow rate and high loading. The statistical Grubbs’ test of Entropy showed the efficacy of the method at detecting the earliest signs of rotating stall.
        </p>
      </details></td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/hazarika_pvis_16.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[5]</strong> Subhashis Hazarika, <b>Soumya Dutta</b>, Han-Wei Shen, Visualizing the Variations of Ensemble of Isosurfaces, <em>IEEE Pacific Visualization Symposium (IEEE PacificVis Notes)</em>, 2016, 209-213. [<a href="https://ieeexplore.ieee.org/document/7465272">Link</a>] [<a href="/papers/ensemble_pvis_notes2016.pdf">Pdf</a>] [<a href="/bibtex/Pvis_ensemble_isosurface.bib">BibTex</a>]
      <details>
        <summary><b><span style="color:blue">Abstract</span></b></summary>
        <p>
        Visualizing the similarities and differences among an ensemble of isosurfaces is a challenging problem mainly because the isosurfaces cannot be displayed together at the same time. For ensemble of isosurfaces, visualizing these spatial differences among the surfaces is essential to get useful insights as to how the individual ensemble simulations affect different isosurfaces. We propose a scheme to visualize the spatial variations of isosurfaces with respect to statistically significant isosurfaces within the ensemble. Understanding such variations among ensemble of isosurfaces at different spatial regions is helpful in analyzing the influence of different ensemble runs over the spatial domain. In this regard, we propose an isosurface-entropy based clustering scheme to divide the spatial domain into regions of high and low isosurface variation. We demonstrate the efficacy of our method by successfully applying it on real-world ensemble data sets from ocean simulation experiments and weather forecasts.
        </p>
      </details></td>
   </tr>
</table>


<!-- ## Undergraduate Publications: -->

<table>
   <tr width="100%;">
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[4]</strong> <b>Soumya Dutta</b> and Madhurima Chattopadhyay, A change detection algorithm for medical cell images, <em>International Conference on Scientific Paradigm Shift in Information Technology and Management (SPSITM 2011)</em>, 2011, 524-527. [Link] [<a href="/bibtex/SPSITM_change_det.bib">BibTex</a>] </td>
   </tr>
</table>



<table>
   <tr width="100%;">
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[3]</strong> <b>Soumya Dutta</b> and Bidyut B. Chaudhuri, A Color Edge Detection Algorithm in RGB Color Space, <em>Advances in Recent Technologies in Communication and Computing (ARTCOM 2009)</em>, 2009, 337-340. [<a href="https://ieeexplore.ieee.org/document/5329404">Link</a>] [<a href="/bibtex/ARTCOM_edge1.bib">BibTex</a>]  </td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[2]</strong>  <b>Soumya Dutta</b> and Bidyut B. Chaudhuri, Homogeneous region based color image segmentation, <em>The World Congress on Engineering and Computer Science (WCECS 2009)</em>, 2009, vol 2, 1301-1305. [<a href="http://www.iaeng.org/publication/WCECS2009/WCECS2009_pp1301-1305.pdf">Link</a>]  [<a href="/bibtex/WC_segmentation.bib">BibTex</a>] </td>
   </tr>
</table>



<table>
   <tr width="100%;">
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top" border="none"> <strong>[1]</strong>   <b>Soumya Dutta</b> and Bidyut B. Chaudhuri, A Statistics and Local Homogeneity Based Color Edge Detection Algorithm, <em>Advances in Recent Technologies in Communication and Computing (ARTCOM 2009)</em>, 2009, 546-548. [<a href="https://ieeexplore.ieee.org/document/5329170">Link</a>]  [<a href="/bibtex/ARTCOM_edge2.bib">BibTex</a>] </td>
   </tr>
</table>


## White Papers

<table>
   <tr width="100%;">
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top" border="none"> <strong>[3]</strong> <b>Soumya Dutta</b>, Divya Banesh, Li-Ta Lo, Roxana Bujack, and David Rogers, Model-based Visual Analytics of Big Data: Challenges and Opportunities, <em>DOE ASCR Workshop on Visualization for Scientific Discovery, Decision-Making, & Communication</em>, January 18-20, 2022. </td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top" border="none"> <strong>[2]</strong> Roxana Bujack, Divya Banesh, <b>Soumya Dutta</b>, and Li-Ta Lo, Vector Field Segmentation for Data Analysis, <em>DOE ASCR Workshop on Visualization for Scientific Discovery, Decision-Making, & Communication</em>, January 18-20, 2022. </td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top" border="none"> <strong>[1]</strong> Li-Ta Lo, Roxana Bujack, <b>Soumya Dutta</b>, and Divya Banesh, Sparsity for Extreme Scale Visualization and Data Analysis, <em>DOE ASCR Workshop on Visualization for Scientific Discovery, Decision-Making, & Communication</em>, January 18-20, 2022.</td>
   </tr>
</table>


## Posters/Technical Reports

<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/jiayi_poster_2021.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[5]</strong> Jiayi Xu, <b>Soumya Dutta</b>, Wenbin He, Joachim Moortgat, and Han-Wei Shen, Geometry-Driven Detection, Tracking and Visual Analysis of Viscous and Gravitational Fingers, <em>15th Annual CSE Student Research Poster Exhibition, The Ohio State University</em>, 2021.
      </td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/poster_18.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[4]</strong> <b>Soumya Dutta</b>, Han-Wei Shen, and Jen-Ping Chen, In Situ Prediction Driven Feature Analysis in Jet Engine Simulations, <em>12th Annual CSE Student Research Poster Exhibition, The Ohio State University</em>, 2018. <b><span style="color: red">[Best Poster Award]</span></b> </td> 
   </tr>
</table>

<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/insitu_stall_poster_16.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[3]</strong> <b>Soumya Dutta</b>, Chun-Ming Chen, Gregory Heinlein, Han-Wei Shen, and Jen-Ping Chen, In Situ Distribution Guided Analysis and Visualization of Transonic Jet Engine Simulations, <em>11th Annual CSE Student Research Poster Exhibition, The Ohio State University</em>, 2017. <b><span style="color: red">[Best Poster Award]</span></b>
      </td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/openMC.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[2]</strong> Garrett A. Aldrich, <b>Soumya Dutta</b>, and Jonathan Woodring, OpenMC In Situ Source Convergence Detection, <em>Los Alamos National Laboratory (LA-UR-16-23217)</em>, 2016.
      </td>
   </tr>
</table>


<table>
   <tr width="100%;">
      <td width="23%;" valign="top">
      <img style="height:100px" src="/images/pmi_Techreport.png"/> </td>
      <td width="100%;" style="font-size:11pt;" align="justify" valign="top"> <strong>[1]</strong> <b>Soumya Dutta</b>, Xiaotong Liu, Ayan Biswas, Han-Wei Shen, Yifan Hu, James Giuliani, and Jen-Ping Chen, Pointwise Information Analysis for Multivariate Time-varying Feature Identification, <em>OSU-CISRC-6/14-TR13</em>, 2013.
      </td>
   </tr>
</table>






