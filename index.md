---
layout: default
---
<style> 
.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 75%;
}
.program>.entry{
  display: flex;
  padding-bottom: 2pt;
  padding-top: 2pt;
}
.program>.entry.start,.program>.entry.end{
  display: block;
  width: 100%;
  text-align: center;
}
.program>.entry.start{
  border-bottom: 1px solid rgb(127, 127, 127);
}
.program>.entry.end{
  border-top: 1px solid rgb(127, 127, 127);
}
.program>.entry.poster{
    border: 1px solid rgb(220, 220, 220);
    border-radius: 15px;
    background-color: rgb(220, 220, 220);
    margin-top: 8pt;
    margin-bottom: 8pt;
}
.program>.entry.poster .title{
  display: inline;
}
.program>.entry.poster .papers{
  list-style: decimal;
  margin-top: 5pt;
}
.program>.entry.poster .papers>li>.title{
  font-weight: bold;
}
.program>.entry.poster .papers>li>.authors{
  font-style: italic;
}
.program>.entry>.speaker{
  width:10%;
  margin-left: 2.5%;
  margin-right: 2.5%;
  float: left;
  text-align: center;
}
.program>.entry>.speaker img{
  border-radius: 50%;
  object-fit: cover;
  width: 100%;
  aspect-ratio: 1;
}
.program>.entry>.details{
  width:85%;
  font-size: 12pt;
}
.program>.entry .time{
  display: inline;
  font-weight: bold;
}
.program>.entry>.details>.title{
  font-size: 13pt;
  font-weight: bold;
}
.program>.entry>.details>.abstract {
  display: none;
  border-radius: 5px;
  background-color: rgb(229, 229, 229);
  padding: 8pt;
  font-size: 11pt;
}
</style>

# Overview
<div style="text-align: justify">
  In the context of the 2022 Deep Learning Indaba this hybrid workshop will focus on computer vision algorithms using less labels and/or less data. 
Classically, machine learning relies on abundant annotated data. This is prone to cultural biases, since datasets are commonly recorded in western countries,  as well as distribution biais due to rare events, such as adverse weather/lighting conditions which are rarely included in public datasets.<br>

Speakers will present alternative strategies to reduce the need of labels (e.g., domain adaptation, domain generalization) or the need of data (e.g., few-/zero-shot learning, continual learning). Other strategies that rely on accessible priors will be presented, like self-supervised, cross modal, or model-based learning. The applications will focus, but not be limited to, autonomous driving and robotics.
<br>
<br>


<b>The hybrid workshop will have a poster session for selected works. Relevant original and/or published articles are welcome. See details in <a href="#call-for-papers">call for paper</a>.<br> 
<span style="color: red;">
News (11/08): Poster selection is out !<br>
Submission website is open <a href="https://cmt3.research.microsoft.com/WSCV2022/" target="_blank">here</a></span></b><br>
<em>Remote access details will be added here close to the event.</em><br>
</div>

# Invited Speakers
<div style="display: flex">
  <div style="width:22.5%; text-align: center;">
    <a href="http://webia.lip6.fr/~cord/" target="_blank">
    <img alt="Matthieu Cord" src="pics/matthieu_cord.jpg" style ="border-radius: 50%; object-fit: cover; width = 100%; aspect-ratio: 1;">
    <br>
    Matthieu Cord</a><br>
    Sorbonne Uni / Valeo.ai
  </div>
  
  <div style="width:2.5%">
  </div>

  <div style="width:22.5%; text-align: center;">
    <a href="https://scholar.google.fr/citations?user=PXm1lPAAAAAJ" target="_blank">
    <img alt="Gabriela Csurka" src="pics/gabriela_csurka.jpg" style ="border-radius: 50%; object-fit: cover; width = 100%; aspect-ratio: 1;">
    <br>
    Gabriela Csurka</a><br>
    Naver Labs Europe
  </div>
  
  <div style="width:2.5%">
  </div>

  <div style="width:22.5%; text-align: center;">
    <a href="https://sites.google.com/site/sileyeoba/" target="_blank">
    <img alt="Sileye Ba" src="pics/sileye_ba.png" style ="border-radius: 50%; object-fit: cover; width = 100%; aspect-ratio: 1;">
    <br>
    Sileye Ba</a><br>
    L'Oréal
  </div>
  
  <div style="width:2.5%">
  </div>
  
  <div style="width:22.5%; text-align: center;">
    <a href="https://fcdl94.github.io/" target="_blank">
    <img alt="Fabio Cermelli" src="pics/fabio_cermelli.jpg" style ="border-radius: 50%; object-fit: cover; width = 100%; aspect-ratio: 1;">
    <br>
    Fabio Cermelli</a><br>
    Politecnico di Torino
  </div>
</div>
<div style="display: flex">
  <div style="width:22.5%; text-align: center;">
    <a href="https://umbertomichieli.github.io/" target="_blank">
    <img alt="Umberto Michieli" src="pics/umberto_michieli.jpg" style ="border-radius: 50%; object-fit: cover; width = 100%; aspect-ratio: 1;">
    <br>
    Umberto Michieli</a><br>
    Samsung Research
  </div>
  
  <div style="width:2.5%">
  </div>

  <div style="width:22.5%; text-align: center;">
    <a href="https://mysite.ku.edu.tr/fguney/" target="_blank">
    <img alt="Fatma G&uuml;ney" src="pics/fatma_guney.jpg" style ="border-radius: 50%; object-fit: cover; width = 100%; aspect-ratio: 1;">
    <br>
    Fatma G&uuml;ney</a><br>
    Koç University
  </div>
</div>

## Program
The hybrid workshop will be half-day on 25/08.<br>
<!-- The program will be published soon.<br><br> -->
<em>Remote access details will be added here close to the event.</em>

<div class="program">
<div class="entry start">
  <div class="time">2:00pm</div> - <b>Workshop start</b>
</div>
<div class="entry">
  <div class="speaker">
    <a href="http://webia.lip6.fr/~cord/" target="_blank">
    <img alt="Matthieu Cord" src="pics/matthieu_cord.jpg">
    <br>
    </a>
  </div>
  <div class="details">
    <div class="time">2:00pm</div> - <a href="http://webia.lip6.fr/~cord/" target="_blank">Matthieu Cord</a>, Sorbonne Uni / Valeo.ai<br>
    <div class="title">Vision Transformers</div>
    <a onclick="this.parentElement.getElementsByClassName('abstract')[0].style.display=this.parentElement.getElementsByClassName('abstract')[0].style.display!='block' ? 'block' : 'none';">[+] Abstract</a>
    <div class="abstract">Originally proposed in natural language processing, transformers are attracting growing interest in computer vision, providing state-of-the-art results for tasks such as image classification or object detection.
    In this talk, I present the underlying motivation and the basic architecture of Vision Transformers (ViT). I detail their difference with classical convolution -based architectures for classification, and more general framework for different tasks in computer vision. I also present ViT pre-training with large multimodal language and vision datasets, for downstream tasks with few or zero-shot supervision.
    </div>
  </div>
</div>
<div class="entry">
  <div class="speaker">
    <a href="https://umbertomichieli.github.io/" target="_blank">
    <img alt="Umberto Michieli" src="pics/umberto_michieli.jpg">
    <br>
    </a>
  </div>
  <div class="details">
    <div class="time">2:45pm</div> - <a href="https://umbertomichieli.github.io/" target="_blank">Umberto Michieli</a>, Samsung research<br>
    <div class="title">Learning to Segment Images with Limited Data across Devices, Domains and Tasks</div>
    <a onclick="this.parentElement.getElementsByClassName('abstract')[0].style.display=this.parentElement.getElementsByClassName('abstract')[0].style.display!='block' ? 'block' : 'none';">[+] Abstract</a>
    <div class="abstract">Dense prediction tasks, such as semantic segmentation, are nowadays tackled with data-hungry deep learning architectures. However, oftentimes only limited data is available. In this talk, we argue the need for versatility of deep neural architectures from various perspectives.<br>
    First, we discuss the federated learning (FL) paradigm to train deep architectures in a distributed setting with data available only at remote clients. We address non-i.i.d. distribution of samples among clients via 1) a naïve FL optimizer that is fair from the users' perspective, and 2) a prototype-guided FL optimizer that is evaluated also on FL segmentation benchmarks.<br>
    Second, we briefly overview model adaptation to unseen visual domains with no ground truth annotations available and we discuss a recent synthetic dataset (SELMA) to aid the segmentation task on such domains.<br>
    Finally, we empower deep models to recognize novel semantic concepts without forgetting previously learned ones. We investigate continual semantic segmentation via knowledge distillation, latent space regularization, and replay samples retrieved via weakly-supervised GANs or web-crawled images.
    </div>
  </div>
</div>
<div class="entry">
  <div class="speaker">
    <a href="https://sites.google.com/site/sileyeoba/" target="_blank">
    <img alt="Sileye Ba" src="pics/sileye_ba.png">
    <br>
    </a>
  </div>
  <div class="details">
    <div class="time">3:15pm</div> - <a href="https://sites.google.com/site/sileyeoba/" target="_blank">Sileye Ba</a>, L'Oréal<br>
    <div class="title">Real-time Make Up Virtual-Try-On Through Deep Inverse Graphics</div>
    <a onclick="this.parentElement.getElementsByClassName('abstract')[0].style.display=this.parentElement.getElementsByClassName('abstract')[0].style.display!='block' ? 'block' : 'none';">[+] Abstract</a>
    <div class="abstract">Augmented reality applications have rapidly spread across online retail platforms and social media, allowing consumers to virtually try-on a large variety of products, such as makeup, hair dying, or shoes. However, parametrizing a renderer to synthesize realistic images of a given product remains a challenging task that requires expert knowledge. While recent work has introduced neural rendering methods for virtual try-on from example images, current approaches are based on large generative models that cannot be used in real-time on mobile devices. This calls for a hybrid method that combines the advantages of computer graphics and neural rendering approaches. In this paper, we propose a novel framework based on deep learning to build a real-time inverse graphics encoder that learns to map a single example image into the parameter space of a given augmented reality rendering engine. Our method leverages self-supervised learning and does not require labeled training data, which makes it extendable to many virtual try-on applications. Furthermore, most augmented reality renderers are not differentiable in practice due to algorithmic choices or implementation constraints to reach real-time on portable devices. To relax the need for a graphics-based differentiable renderer in inverse graphics problems, we introduce a trainable imitator module. Our imitator is a generative network that learns to accurately reproduce the behavior of a given non-differentiable renderer. We propose a novel rendering sensitivity loss to train the imitator, which ensures that the network learns an accurate and continuous representation for each rendering parameter. Automatically learning a differentiable renderer, as proposed here, could be beneficial for various inverse graphics tasks. Our framework enables novel applications where consumers can virtually try-on a novel unknown product from an inspirational reference image on social media. It can also be used by computer graphics artists to automatically create realistic rendering from a reference product image.</div>
  </div>
</div>
<div class="entry poster">
  <div class="speaker">
  </div>
  <div class="details">
    <div class="time">3:45pm</div>
    <div class="title">- Poster session &amp; Coffee break</div><br>
    <ul class="papers">
      <li><span class="title">Deep Learning Architecture For Brain Vessel Segmentation</span>. <span class="authors">K. Iddrisu.</span></li>
      <li><span class="title">Single-modality and joint fusion deep learning for diabetic retinopathy diagnosis</span>. <span class="authors">K. El-ateif.</span></li>
      <li><span class="title">Co-attention Mechanism with Multi-Modal Factorized Bilinear Pooling for Medical Image Question Answering</span>. <span class="authors">V.-S. Mfogo, J. Fadugba, X. Chen, G. Gkioxari.</span></li>
      <li><span class="title">AFRIGAN: African Fashion Style Generator using Generative Adversarial Networks (GANs)</span>. <span class="authors">M.-M. Salami, W. Oyewusi, O. Adekanmbi.</span></li>
      <li><span class="title">Sign-to-Speech Model for Sign Language Understanding: A Case Study of Nigerian Sign Language</span>. <span class="authors">S. Kolawole.</span></li>
      <li><span class="title">ATLAS: Universal Function Approximator for Memory Retention</span>. <span class="authors">H. Van Deventer.</span></li>
      <li><span class="title">Application of Artificial Intelligence (AI) and Collective Intelligence (CI) for Diagnosis of Breast Cancer</span>. <span class="authors">A. Jimoh, A. Adeniran, M. Klein.</span></li>
    </ul>
  </div>
</div>
<div class="entry">
  <div class="speaker">
    <a href="https://scholar.google.fr/citations?user=PXm1lPAAAAAJ" target="_blank">
    <img alt="Gabriela Csurka" src="pics/gabriela_csurka.jpg">
    <br>
    </a>
  </div>
  <div class="details">
    <div class="time">4:30pm</div> - <a href="https://scholar.google.fr/citations?user=PXm1lPAAAAAJ" target="_blank">Gabriela Csurka</a>, Naver Labs Europe<br>
    <div class="title">TBA</div>
<!--     <a onclick="this.parentElement.getElementsByClassName('abstract')[0].style.display=this.parentElement.getElementsByClassName('abstract')[0].style.display!='block' ? 'block' : 'none';">[+] Abstract</a>
 -->    <div class="abstract"></div>
  </div>
</div>
<div class="entry">
  <div class="speaker">
    <a href="https://fcdl94.github.io/" target="_blank">
    <img alt="Fabio Cermelli" src="pics/fabio_cermelli.jpg">
    <br>
    </a>
  </div>
  <div class="details">
    <div class="time">5:15pm</div> - <a href="https://fcdl94.github.io/" target="_blank">Fabio Cermelli</a>, Politecnico di Torino<br>
    <div class="title">Semantic Segmentation from Weakly and Partial Annotations</div>
    <a onclick="this.parentElement.getElementsByClassName('abstract')[0].style.display=this.parentElement.getElementsByClassName('abstract')[0].style.display!='block' ? 'block' : 'none';">[+] Abstract</a>
    <div class="abstract">Due to the rise of deep learning and the accessibility of big human-annotated datasets, tremendous progress has been made in the fundamental computer vision task of semantic segmentation. However, because each pixel of the image needs to have a label, annotations are quite expensive. As a result, the annotation cost hinders the applications of semantic segmentation in the real world. In the presentation, we outline ways that significantly lower the cost by utilizing less expensive and more readily available annotations.<br>
We first look into the use of partial annotations, where labels are only given for specific areas of the image. We begin with an incremental learning application, where the objective is to expand a model to learn new classes without forgetting and without being given annotations for existing classes. We present a straightforward adjustment of the cross-entropy loss to deal with this situation. The proposed losses are then extended to the point-and-scribble supervised segmentation, where only a small portion of the image's pixels are annotated.<br>
Finally, we show the scenario of not having any pixel-level information. The goal is to learn a segmentation model using cheap and widely available image-level labels, that only indicate the presence of an object in the image without providing any localization cue. We review the current state-of-the-art and illustrate the current solutions based on Class-Activation Maps. Then, extending these techniques, we introduce a framework that learns to segment new classes over time from image-level labels.
</div>
  </div>
</div>
<div class="entry">
  <div class="speaker">
    <a href="https://mysite.ku.edu.tr/fguney/" target="_blank">
    <img alt="Fatma G&uuml;ney" src="pics/fatma_guney.jpg">
    <br>
    </a>
  </div>
  <div class="details">
    <div class="time">5:45pm</div> - <a href="https://mysite.ku.edu.tr/fguney/" target="_blank">Fatma G&uuml;ney</a>, Koç University<br>
    <div class="title">TBA</div>
<!--     <a onclick="this.parentElement.getElementsByClassName('abstract')[0].style.display=this.parentElement.getElementsByClassName('abstract')[0].style.display!='block' ? 'block' : 'none';">[+] Abstract</a>
 -->    <div class="abstract"></div>
  </div>
</div>
<div class="entry end">
  <div class="time">6:15pm</div> - <b>Workshop end</b>
</div>
</div>
<!--
:

| Time (CET) | Event |
| ----- | ----- |
| 14:00 | Opening remarks (10 min) |
| 14:10 | Invited talk 1 (50 min) |
| 15:00 | Invited talk 2 (30 min) |
| 15:30 | Invited talk 3 (30 min) |
| 16:00 | coffee break   (10 min) |
| 16:10 | Poster session (50 min) |
| 17:00 | Invited talk 4 (30 min) |
| 17:30 | Invited talk 5 (30 min) |
| 18:00 | End of the workshop |
//-->

## Organizers
<div style="display: flex">
  <div style="width:22.5%; text-align: center;">
    <a href="https://team.inria.fr/rits/membres/raoul-de-charette/">
    <img alt="Raoul de Charette" src="pics/raoul_de-charette.png" style ="border-radius: 50%; object-fit: cover; width = 100%; aspect-ratio: 1;">
    <br>
    Raoul de Charette</a><br>
    Inria
  </div>
  
  <div style="width:2.5%">
  </div>

  <div style="width:22.5%; text-align: center;">
    <a href="https://fabvio.github.io/">
    <img alt="Fabio Pizzati" src="pics/fabio_pizzati.png" style ="border-radius: 50%; object-fit: cover; width = 100%; aspect-ratio: 1;">
    <br>
    Fabio Pizzati</a><br>
    Inria and Unibo
  </div>
  
  <div style="width:2.5%">
  </div>

  <div style="width:22.5%; text-align: center;">
    <a href="https://ptrckprz.github.io/">
    <img alt="Patrick Pérez" src="pics/patrick_perez.jpg" style ="border-radius: 50%; object-fit: cover; width = 100%; aspect-ratio: 1;">
    <br>
    Patrick Pérez</a><br>
    Valeo.ai
  </div>
  
  <div style="width:2.5%">
  </div>

  <div style="width:22.5%; text-align: center;">
    <a href="https://tuanhungvu.github.io/">
    <img alt="Tuan-Hung Vu" src="pics/tuan-hung_vu.jpg" style ="border-radius: 50%; object-fit: cover; width = 100%; aspect-ratio: 1;">
    <br>
    Tuan-Hung Vu</a><br>
    Valeo.ai
  </div>
</div>
<div style="display: flex">  
  <div style="width:22.5%; text-align: center;">
    <a href="https://abursuc.github.io/">
    <img alt="Andrei Bursuc" src="pics/andrei_bursuc.jpg" style ="border-radius: 50%; object-fit: cover; width = 100%; aspect-ratio: 1;">
    <br>
    Andrei Bursuc</a><br>
    Valeo.ai
  </div>
  
  <div style="width:2.5%">
  </div>

  <div style="width:22.5%; text-align: center;">
    <a href="https://mancinimassimiliano.github.io/">
    <img alt="Massimiliano Mancini" src="pics/massimiliano_mancini.jpg" style ="border-radius: 50%; object-fit: cover; width = 100%; aspect-ratio: 1;">
    <br>
    Massimiliano Mancini</a><br>
    Uni. of Tübingen
  </div>
</div>



## Call for Papers



<div style="text-align: justify">
To foster interactions, attendees of the 2022 Deep Learning Indaba are invited to submit of any work related to computer vision (not limited to weakly supervised), for presentation at the poster session. 
Original articles as well as previously published ones can be submitted.<br>
<br>
<span style="color:  red;">Please submit pdf of your work on CMT: <a href="https://cmt3.research.microsoft.com/WSCV2022/" target="_blank">https://cmt3.research.microsoft.com/WSCV2022/</a><br>
<b>Deadline is extended to August 7<sup>th</sup> (11:59pm AOE).</b></span><br>

<br>
The selection of relevant papers (of at least 4 pages) will be done by the organization board, for presentation at the poster session.<br>
<br>
The topics of interest include, but are not limited to:

  <ol>
    <li>3D computer vision</li>
    <li>Adversarial learning, adversarial attack for vision algorithms</li>
    <li>Autonomous agents with vision (reinforcement/imitation learning)</li>
    <li>Biometrics, face, gesture, body pose</li>
    <li>Computational photography, image and video synthesis</li>   
    <li>Explainable, fair, accountable, privacy-preserving, ethical computer vision</li>
    <li>Image recognition and understanding (object detection, categorization, segmentation, scene modeling, visual reasoning)</li>
    <li>Low-level and physics-based vision</li>
    <li>Semi-/Self-/Un-supervised learning and Few-/Zero-shot algorithms</li>
    <li>Transfer learning (domain adaptation, etc.)</li>
    <li>Video understanding (tracking, action recognition, etc.)</li>
    <li>Multi-modal vision (image+text, image+sound, etc.)</li>
  </ol>
</div>
<a href="https://drive.google.com/file/d/1ktqInynvEBldBYn-bg9SfZXjU5EWb-L7/view?usp=sharing" target="_blank">PDF version</a>

## Important workshop dates
- Submission deadline: <span style="text-decoration: line-through; font-weight: normal;">July 10, 2022.</span> <strong>Last extension to August 7<sup>th</sup>, 2022 (11:59pm AOE).</strong>
- Decision notification: <strong><span style="text-decoration: line-through; font-weight: normal;">August 4th, 2022</span> August 11th, 2022.</strong>
- Workshop date: <strong>August 25, 2022.</strong><br>

Any questions ? Contact <a href="https://team.inria.fr/rits/membres/raoul-de-charette/">Raoul de Charette</a>.
