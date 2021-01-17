---
permalink: /projects/HumanModelLearning/
author_profile: true
---
<style>
h2 {text-align: center;}
</style>

<h2> Human model learning from RGB with depth assistance </h2>
<center>Balamurugan Thambiraja ;  <a href="http://www.niessnerlab.org/members/aljaz_bozic/profile.html" style="text-align:center">Aljaž Božič</a> </center>
<br>

![HML_Teaser](/balamuruganthambiraja.github.io/images/HML_teaser.png)

Model based human pose estimation from an RGB image is a long standing problem in computer vision. Current state-of-the-art methods rely on data-driven priors that are built from limited 3D data captured using complex multicamera setups. In contrast, we propose RGB-D based self supervised training of a deep network that (i) learns to predict the pose parameters of a human from an RGB image. (ii) learns to regress shape and person specific shape displacements which enables use of the method for scale-aware 3D reconstruction task. Specifically, at train time we overfit to shape and delta displacements using RGB-D video. At test time, we predict the pose parameters from a single RGB image. In addition, we also introduce a method to generate quality 3D supervision data by leveraging an existing human pose tracking method and the depth map. Through detailed experiments, we analyze how different components of our method impact performance, especially the proposed data generation pipeline, and present an efficiently trainable framework for 3D human shape and deformation from from RGB images.



[[paper]](/pdfs/HML.pdf) [[code]](will be uploaded soon)- will be updated soon
