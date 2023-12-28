## Selected Projects

<!-- <h4 style="margin:0 0px 0;">2D Lane Detection with Human Pose Estimation </h4>

<ul style="margin:0; padding:0;">
<text>       
    As a final project for the course <a href="https://edu.epfl.ch/coursebook/fr/deep-learning-for-autonomous-vehicles-CIVIL-459" target="_blank">Deep Learning for Autonomous Vehicles</a> @ EPFL, we adjusted a deep neural network used for human pose estimation, <a href="https://github.com/openpifpaf/openpifpaf" target="_blank"> OpenPifPaf</a>, to achieve keypoint-based lane marker detection, which benefits the real-time application for the sparse representation. Specifically, we created new dataloader and plugin necessities to enable this network to be trained on <a href="https://github.com/The-OpenROAD-Project/OpenLane" target="_blank">OpenLane</a> dataset
    <br><br>
    <img src="../assets/img/project1.png" alt="2D Lane Detection" style="width: 100%; max-width: 660px; height: auto;">
</text>
   
</ul>
<br><br> -->

<h4 style="margin:0 0px 0;">Pose Estimation Based Monocular 3D Lane Detection </h4>

<ul style="margin:0; padding:0;">
<text>       
    We adjusted a deep neural network used for human pose estimation, <a href="https://github.com/openpifpaf/openpifpaf" target="_blank"> OpenPifPaf</a>, to achieve keypoint-based lane marker detection, which benefits the real-time application with the sparse representation. New dataloader and plugin necessities to enable this network originally trained on human poses to be trained on <a href="https://github.com/The-OpenROAD-Project/OpenLane" target="_blank">OpenLane</a> dataset. The keypoint downsampling strategy was investigated to facilitate the lane pose learning. This 2D task achieved on-par performance with state-of-the-art 2D methods on <a href="https://github.com/The-OpenROAD-Project/OpenLane" target="_blank">OpenLane</a>, as reported by <a href="https://arxiv.org/abs/2203.11089" target="_blank">PersFormer</a>. 
    <br><br> 
    Further, we extended this task into 3D domain. A monocular dense depth estimation method was incorporated, for which we finetuned with limited sparse depth annotations, to enable prediction beyond 80 meters cap, improving the model’s performance on outdoor autonomous driving scenario.
    <br><br>
    <div style="display: flex; justify-content: center; align-items: center;">
        <video width="400" height="240" controls>
            <source src="../assets/img/lane_no_watermark.mp4" type="video/mp4" >
            Your browser does not support the video tag.
        </video>
    </div>
</text>
   
</ul>
<br><br>


<h4 style="margin:0 0px 0;">Improving Neural Networks Performance with Zeroth-order and First-order Hybrid Optimization Methods </h4>
<ul style="margin:0; padding:0;">
<text>
   This project delves into the limitations of first-order (FO) gradient-based optimization in neural networks, exploring  their gradient-free zeroth-order (ZO) alternatives like ZO-SGD and ZO-signSGD. Using a PyTorch-based framework, we implemented and compared ZO and FO methods across various network configurations and hyperparameters, assessing time efficiency, convergence rate, stability and overall performance. The study reveals ZO methods' increased stability and lower hyperparameter sensitivity, attributed to the regularizing effect of perturbation techniques in gradient estimation. However, ZO methods were found to be more reliant on model architecture and scaling. A hybrid FO-ZO approach emerged as a balanced solution, optimizing both gradient computation costs and efficiency.
</text>
   
</ul>
<br><br>

<h4 style="margin:0 0px 0;">Crafting a Personalized Beer Landscape: Analyzing User Preferences and Naming Impact for Guiding Targeted Recommendation </h4>
<ul style="margin:0; padding:0;">
<text>
    This project takes a deep dive into beer popularity and user taste preferences using review datasets from <a href="https://www.beeradvocate.com/" target="_blank">BeerAdvocate</a> and <a href="https://www.ratebeer.com/" target="_blank">RateBeer</a>, consisting of both categorical ratings and textual reviews. Merging statistical methods with natural language processing techniques like sentiment analysis and word2vec, we uncovered a multi-faceted view of the beer domain, including the popularity of beer and the influence of naming on ratings, and the similarities between styles. Our findings provide tailored recommendations for users, considering not just popularity but also qualitative attributes and regional taste variations. An interactive webpage was also deployed, I invite you to click on the image and take a look at our data story. 
    <br><br>
    <div style="display: flex; justify-content: center; align-items: center;">
        <a href="https://epfl-ada.github.io/ada-2023-project-badanalysist/" target="_blank">
        <img src="../assets/img/beer.png" alt="Beer review data story" style="width: 100%; max-width: 420px; height: auto;">
        </a>
    </div>
</text>
   
</ul>

<br><br>
<h4 style="margin:0 0px 0;">Training a Chatbot for Commonsense Persona-grounded Dialogue Generation </h4>
<ul style="margin:0; padding:0;">
<text>
    We participated in the <a href="https://www.aicrowd.com/challenges/commonsense-persona-grounded-dialogue-challenge-2023/problems/task-1-commonsense-dialogue-response-generation" target="_blank">Commonsense Persona-grounded Dialogue Challenge</a> organized by Sony and EPFL, which aims to generate dialogue responses that possess both persona consistency and contextual coherence. We enhanced a BART-based model by incorporating a knowledge-graph-based data augmentation technique and evaluated model performance given different set of augmentation settings and persona constraints. Our best-performing model achieved a word F1 score of 17.27, surpassing the baseline score of 17.001 set by GPT-3.5 Turbo using a simple prompt.
    <br><br>
    <div style="display: flex; justify-content: center; align-items: center;">
        <img src="../assets/img/chatbot.png" alt="Chatbot Responses" style="width: 100%; max-width: 420px; height: auto;">
    </div>
</text>
   
</ul>
<br><br>

<h4 style="margin:0 0px 0;">Deep Learning Specialization Projects </h4>
<ul style="margin:0; padding:0;">
<text>
    After starting hands-on projects directly from <a href="https://edu.epfl.ch/coursebook/fr/deep-learning-for-autonomous-vehicles-CIVIL-459" target="_blank">Deep Learning for Autonomous Vehicles</a> @ EPFL, I decided to take a systematic approach to learn and comprehend deep learning for computer vision with <a href="https://www.coursera.org/specializations/deep-learning?utm_medium=sem&utm_source=gg&utm_campaign=B2C_EMEA_deep-learning_deeplearning-ai_FTCOF_specializations_country-multi&campaignid=20858198821&adgroupid=156245837229&device=c&keyword=deep%20learning%20certification&matchtype=b&network=g&devicemodel=&adposition=&creativeid=684249171979&hide_mobile_promo&gclid=Cj0KCQiA1rSsBhDHARIsANB4EJaT7BJYAGY5QAvCqjYBwP2bEqx7x7OFU89sH_UGh3XmmCNCpZxaYrMaAsaQEALw_wcB" target="_blank">Deep Learning Specialization</a> @ Coursera. There I both gained theoratical knowledge about and had the chance to implement from scratch efficient network architectures, including ResNet, LSTM, Transformers, etc, and also applied them to various computer vision tasks including car detection based on YOLO and image segmentation with U-Net.         
    <br><br>
    <div style="display: flex; justify-content: center; align-items: center;">
        <img src="../assets/img/coursera.jpg" alt="Deep Learning Specialization Projects" style="width: 100%; max-width: 620px; height: auto;">
    </div>
</text>
   
</ul>
<br><br>

## Publications

<h4 style="margin:0 0px 0;">Tracing the origin of large respiratory droplets by their deposition characteristics inside the respiratory tract during speech </h4>
<ul style="margin:0; padding:0;">
<text>
   <strong>Yihan Wang</strong>, Jianjian Wei,  Caroline X. Gao, Li Liu, <a href="https://pubmed.ncbi.nlm.nih.gov/37101943/" target="_blank">Building Simulation, 16, 781 – 794 (2023)</a>, orally presented in IEHB (2021).
    <br><br>
    During Covid-19 year, the prevailance of asymptomatic or pre-symptomatic transmissions were constantly threatening public health, and the relative importance of airborne transmission and droplet-spray transmission were at controverisal. To provide insights for non-pharmaceutical infection control, we conducted a numerical investigation based on computational fluid dynamics into the escaping threshold of differently-sized droplets generating from major SARS-CoV-2 replication sites during speech activaty, with a real human airway model. Combined with published medical data, we highlighted the high risk of small droplets and underestimated importance of airborne transmission route.
    <div style="display: flex; justify-content: center; align-items: center;">
        <img src="../assets/img/pub.png" alt="Chatbot Responses" style="width: 100%; max-width: 620px; height: auto;">
    </div>
</text>
   
</ul>