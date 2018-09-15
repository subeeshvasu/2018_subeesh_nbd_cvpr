# Handling Kernel Uncertainty with CNNs [paper](https://drive.google.com/file/d/1htYVSTXJ60ChPUWjsCHblS22IWlwMitX/view)

This repo provides the test code, pretrained models, and results on benchmark datasets of our CVPR 2018 paper ([Non-blind Deblurring: Handling Kernel Uncertainty with CNNs](https://drive.google.com/file/d/1htYVSTXJ60ChPUWjsCHblS22IWlwMitX/view)).


"Non-blind Deblurring: Handling Kernel Uncertainty with CNNs", [Subeesh Vasu](https://subeeshvasu.github.io), Venkatesh Maligireddy and [A. N. Rajagopalan](http://www.ee.iitm.ac.in/~raju/), IEEE Conference on Computer Vision and Pattern Recognition (CVPR 2018), Salt Lake City, USA, June 2018.

#### BibTeX

 
     @inproceedings{vasu2018non,
        author = {Vasu, Subeesh and Reddy Maligireddy, Venkatesh and Rajagopalan, AN},
        title = {Non-Blind Deblurring: Handling Kernel Uncertainty With CNNs},
        booktitle = {Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
        pages={3272--3281},
        year = {2018}}
## Results     
<p align="center">
<img src="images/nbd_syntheg_levin.png">
</p>

<p align="center">
<img src="images/nbd_syntheg_lai.png">
</p>

<p align="center">
<img src="images/nbd_realeg_lai.png">
</p>

Visual comparison for NBD from inaccurate kernel estimates on Levin [CVPR 2011](http://webee.technion.ac.il/people/anat.levin/papers/deconvLevinEtalCVPR11.pdf) and [Lai CVPR 2016](http://vllab.ucmerced.edu/wlai24/cvpr16_deblur_study/) datasets. [Levin TOG 2007](https://groups.csail.mit.edu/graphics/CodedAperture/), [Krishnan NIPS 2009](https://dilipkay.wordpress.com/fast-deconvolution/), [Zoran ICCV 2011](https://people.csail.mit.edu/danielzoran/EPLLICCVCameraReady.pdf), [Danielyan TIP 2012](https://www.cs.tut.fi/~foi/GCF-BM3D/BM3DframesDeblur-Danielyan.pdf), [Ji TIP 2012](http://www.math.nus.edu.sg/~matjh/download/robust_deblur/TIP_2012_deblur.pdf), [Kheradmand TIP 2014](https://ieeexplore.ieee.org/document/6918453/), and [Schmidt CVPR 2014](http://research.uweschmidt.org/pubs/cvpr14schmidt.pdf) are existing works on NBD.


