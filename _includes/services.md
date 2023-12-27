## Projects

<h4 style="margin:0 10px 0;">2D Lane Detection with Human Pose Estimation </h4>

<ul style="margin:0 0 5px;">
    <li>       
        As a final project for the course <a href="https://edu.epfl.ch/coursebook/fr/deep-learning-for-autonomous-vehicles-CIVIL-459" target="_blank">Deep Learning for Autonomous Vehicles</a> @ EPFL, we adjusted a deep neural network used for human pose estimation, <a href="https://github.com/openpifpaf/openpifpaf" target="_blank"> OpenPifPaf</a>, to achieve keypoint-based lane marker detection, which benefits the real-time application for the sparse representation. Specifically, we created new dataloader and plugin necessities to enable this network to be trained on <a href="https://github.com/The-OpenROAD-Project/OpenLane" target="_blank">OpenLane</a> dataset
        <br><br>
        <img src="../assets/img/project1.png" alt="2D Lane Detection" style="width: 100%; max-width: 660px; height: auto;">
    </li>
   
</ul>

<h4 style="margin:0 10px 0;">Pose Estimation Based Monocular 3D Lane Detection </h4>

<ul style="margin:0 0 5px;">
    <li>       
        The above course project is extended as a research project at <a href="https://www.epfl.ch/labs/vita/" target="_blank">VITA</a>, where we improved keypoint downsampling strategy to facilitate the lane pose learning. This 2D task achieved on-par performance with state-of-the-art 2D methods on <a href="https://github.com/The-OpenROAD-Project/OpenLane" target="_blank">OpenLane</a>, as reported by <a href="https://arxiv.org/abs/2203.11089" target="_blank">PersFormer</a> . For 3D detection, we combined this method with dense depth estimation, for which we finetuned with sparse depth annotations, achieving better performance in outdoor super-deep scenes.
        <br><br>
        <video width="400" height="240" controls>
            <source src="../assets/img/lane_no_watermark.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </li>
   
</ul>
<br><br>

<h4 style="margin:0 10px 0;">Comparative Analysis of ZO and FO Optimization Methods in Neural Networks </h4>
<ul style="margin:0 0 5px;">
    <li>
        In this project, we compared first-order (FO) optimization methods like SGD and signSGD with zeroth-order (ZO) alternatives, such as ZO-SGD and ZO-signSGD, which operate without gradient computations. This study focused on evaluating the convergence speed, stability, and performance of FO and ZO methods under various hyperparameters and neural network configurations. We found that while FO methods are more sensitive to learning rate adjustments, ZO methods are more dependent on model architecture and scaling. Generally, FO optimizers outperform ZO under ideal conditions. A hybrid FO-ZO strategy was found to offer a compromise, balancing gradient computation costs with optimization efficiency.
        <br><br>
        <img src="../assets/img/FO_ZO_lr.png" alt="ZO vs FO: lr" title="omparison of ZO and FO optimizers using same learning rates" style="width: 100%; max-width: 660px; height: auto;">
        <img src="../assets/img/ZO_FO_2.png" alt="ZO vs FO: model scaling and hybrid" style="width: 100%; max-width: 660px; height: auto;">
    </li>
   
</ul>
