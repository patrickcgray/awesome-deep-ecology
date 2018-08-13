# Awesome Deep Ecology [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of deep learning resources for computer vision, inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision) and [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).

<!-- Maintainers - [Patrick Gray](https://github.com/patrickcgray) -->

We are looking for additional maintainers! Let me know (pcg19 at duke) if interested.

An introduction to [Deep Learning for Ecology](https://github.com/patrickcgray/deep_learning_ecology) with some neural networks you can run in the cloud to get a more intuitive understanding of deep learning, as well as suggestions for papers, videos, and quick resources, can be found [here](https://github.com/patrickcgray/deep_learning_ecology).

<!--
## Table of Contents
- [Papers](#papers)
  - [Detection](#detection)
  - [Tracking](#tracking)
  - [Semantic Segmentation](#semantic-segmentation)
  - [Pose Estimation](#pose-estimation)
  - [Other Topics](#other-topics)
- [Courses](#courses)
- [Books](#books)
- [Videos](#videos)
- [Software](#software)
- [Datasets](#datasets)
- [Tutorials](#tutorials)
- [Blogs](#blogs)

-->

## Papers

### Reviews
* Applications for deep learning in ecology
  * Sylvain Christin, Eric Hervet, Nicolas Lecomte
  * https://www.biorxiv.org/content/early/2018/05/30/334854
* A computer vision for animal ecology
  * Ben G. Weinstein
  * https://besjournals.onlinelibrary.wiley.com/doi/10.1111/1365-2656.12780

### Detection
![detection](https://cloud.githubusercontent.com/assets/5226447/8452063/f76ba500-2022-11e5-8db1-2cd5d490e3b3.PNG)

* Deep learning for benthic fauna identification. OCEANS 2016 MTS/IEEE Monterey, OCE 2016. 
  * Marburg, A., & Bigham, K. (2016). 
  * doi:10.1109/OCEANS.2016.7761146
* Right whale recognition using convolutional neural networks. 
  * Polzounov, A., Terpugova, I., Skiparis, D., & Mihai, A. (2016). 
  * http://arxiv.org/abs/1604.05605
#### Camera Traps
* Automatically identifying, counting, and describing wild animals in camera-trap images with deep learning
  * Mohammed Sadegh Norouzzadeh, Anh Nguyen, Margaret Kosmala, Ali Swanson, Meredith Palmer, Craig Packer, Jeff Clune
  * https://arxiv.org/abs/1703.05830 or http://www.pnas.org/content/115/25/E5716
* Recognition in Terra Incognita
  * Sara Beery, Grant Van Horn, and Pietro Perona
  * https://arxiv.org/pdf/1807.04975.pdf
  * Dataset: https://beerys.github.io/CaltechCameraTraps/
* Deep Learning Object Detection Methods for Ecological Camera Trap Data
  * Stefan Schneider, Graham W. Taylor, Stefan C. Kremer
  * https://arxiv.org/abs/1803.10842
* Scene‐specific convolutional neural networks for video‐based biodiversity detection
  * Ben G. Weinstein
  * https://besjournals.onlinelibrary.wiley.com/doi/abs/10.1111/2041-210X.13011
  
#### Aerial Imagery
* Multi-modal survey of Adélie penguin mega-colonies reveals the Danger Islands as a seabird hotspot
  * Alex Borowicz, Philip McDowall, Casey Youngflesh, Thomas Sayre-McCord, Gemma Clucas, Rachael Herman, Steven Forrest, Melissa Rider, Mathew Schwaller, Tom Hart, Stéphanie Jenouvrier, Michael J. Polito, Hanumant Singh & Heather J. Lynch
  * https://www.nature.com/articles/s41598-018-22313-w
* Detecting Wildlife in Unmanned Aerial Systems Imagery Using Convolutional Neural Networks Trained with an Automated Feedback Loop
  * Bowley, C., Mattingly, M., Barnas, A., Ellis-Felege, S., & Desell, T. (2018).  
  * doi:10.1007/978-3-319-93698-7_6
  
#### Other
* Fast accurate fish detection and recognition of underwater images with Fast R-CNN
  * Xiu Li, Min Shang, Hongwei Qin, Liansheng Chen
  * https://ieeexplore.ieee.org/document/7404464/
* Bat detective—Deep learning tools for bat acoustic signal detection
  * Oisin Mac Aodha, Rory Gibb, Kate E. Barlow, Ella Browning, Michael Firman, Robin Freeman, Briana Harder, Libby Kinsey, Gary R. Mead, Stuart E. Newson, Ivan Pandourski, Stuart Parsons, Jon Russ, Abigel Szodoray-Paradi, Farkas Szodoray-Paradi, Elena Tilova, Mark Girolami, Gabriel Brostow, Kate E. Jones
  * http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005995

### Tracking
* Automated Analysis of Marine Video With Limited Data
  * Deborah Levy, Yuval Belfer, Elad Osherov, Eyal Bigal, Aviad P. Scheinin, Hagai Nativ, Dan Tchernov, and Tali Treibitz
  * http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w28/Levy_Automated_Analysis_of_CVPR_2018_paper.pdf

### Semantic Segmentation

### Pose Estimation
* Fast animal pose estimation using deep neural networks
  * Talmo D. Pereira, Diego E. Aldarondo, Lindsay Willmore, Mikhail Kislin, Samuel S.-H. Wang, Mala Murthy, Joshua W. Shaevitz
  * https://www.biorxiv.org/content/early/2018/05/30/331181
  * Code: https://github.com/talmo/leap

### Other Topics

<!--
## Courses 
## Books 
## Videos
## Tutorials
## Blogs
-->

## Software
* Annotation Tools
  * VGG Image Annotator (VIA)
    * http://www.robots.ox.ac.uk/~vgg/software/via/ 
  * Visual Object Tagging Tool (VoTT)
    * https://github.com/Microsoft/VoTT
    
* Well maintained implementations of neural networks
  * Mask RCNN
    * https://github.com/matterport/Mask_RCNN
  * RetinaNet
    * https://github.com/fizyr/keras-retinanet
* Analysis tools
  * Indoor Tracking: Romero-Ferrero, F., Bergomi, M. G., Hinz, R., Heras, F. J. H., & De Polavieja, G. G. (2018). idtracker.ai: Tracking all individuals in large collectives of unmarked animals, (Protocol 1). 
  * doi:10.1101/280735
  * Motion Detection: http://benweinstein.weebly.com/deepmeerkat.html   
  
## Datasets

## Contributing
Please feel free to [pull requests](https://github.com/patrickcgray/awesome-deep-ecology/pulls) to add papers.

## Sharing
+ [Share on Twitter](http://twitter.com/home?status=https://github.com/patrickcgray/awesome-deep-ecology)
+ [Share on Facebook](http://www.facebook.com/sharer/sharer.php?u=https://github.com/patrickcgray/awesome-deep-ecology)
+ [Share on Google Plus](http://plus.google.com/share?url=https://github.com/patrickcgray/awesome-deep-ecology)
+ [Share on LinkedIn](http://www.linkedin.com/shareArticle?mini=true&url=https://github.com/patrickcgray/awesome-deep-ecology&title=Awesome%20Deep%20Ecology)

