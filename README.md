## An Innovative Salient Object Detection Using Center-Dark Channel Prior

|  ![ICCV 2017 logo][logo-iccv] | Paper accepted at [2017 IEEE International Conference on Computer Vision (ICCV) Workshop](http://iccv2017.thecvf.com/)   |
|:-:|---|

[logo-iccv]: https://github.com/ChunbiaoZhu/ACVR2017/blob/master/logo/ICCVLogo.png "ICCV 2017 logo"


|  ![ACVR 2017 logo][logo-acvr] | Paper accepted at [2017 Fifth International Workshop on Assistive Computer Vision and Robotics in conjuction with ICCV'17](http://iplab.dmi.unict.it/acvr2017/)   |
|:-:|---|

[logo-acvr]: https://github.com/ChunbiaoZhu/ACVR2017/blob/master/logo/ACVRLogo.png "ACVR 2017 logo"

| ![Chunbiao Zhu][czhu-photo]  | ![Ge Li][geli-photo]  | ![Wenmin Wang][wangwm-photo]  | ![Ronggang Wang][wangrg-photo]  | 
|:-:|:-:|:-:|:-:|
| [Chunbiao Zhu][czhu-web]  | [Ge Li][gl-web]    |  [Wenmin Wang][wwm-web] | [Ronggang Wang][wrg-web]   | 



[czhu-web]: https://www.researchgate.net/profile/Chunbiao_Zhu
[gl-web]: http://www.ece.pku.edu.cn/index.php?m=content&c=index&a=show&catid=507&id=68
[wwm-web]: http://www.ece.pku.edu.cn/index.php?m=content&c=index&a=show&catid=507&id=42
[wrg-web]: http://www.ece.pku.edu.cn/index.php?m=content&c=index&a=show&catid=507&id=48


[czhu-photo]: https://github.com/ChunbiaoZhu/ACVR2017/blob/master/logo/czhu.png "Chunbiao Zhu"
[geli-photo]: https://github.com/ChunbiaoZhu/ACVR2017/blob/master/logo/gl.jpg "Ge Li"
[wangwm-photo]: https://github.com/ChunbiaoZhu/ACVR2017/blob/master/logo/wwm.jpg  "Wenmin Wang"
[wangrg-photo]: https://github.com/ChunbiaoZhu/ACVR2017/blob/master/logo/wrg.jpg "Ronggang Wang"

## Abstract

 	
Saliency detection aims to detect the most attractive objects in images, which has been widely used as a foundation for various multimedia applications. In this paper, we propose a novel salient object detection algorithm for RGB-D images using center-dark channel prior. First, we generate an initial saliency map based on color saliency map and depth saliency map of a given RGB-D image. Then, we generate a center-dark channel map based on centre saliency prior and dark channel prior. Finally, we fuse the initial saliency map with centre dark channel map to generate the final saliency map. The proposed algorithm is evaluated on two public RGB-D datasets, and the experimental results show that our method outperforms the state-of-the-art methods. 

## Publication

[Our paper](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Pan_Shallow_and_Deep_CVPR_2016_paper.pdf) is open published thanks to the Computer Science Foundation. An [arXiv pre-print](http://arxiv.org/abs/1603.00845) is also available. 

![Image of the paper](https://raw.githubusercontent.com/imatge-upc/saliency-2016-cvpr/master/figs/paper.jpg)

Please cite with the following Bibtex code:

````
@InProceedings{Pan_2016_CVPR,
author = {Pan, Junting and Sayrol, Elisa and Giro-i-Nieto, Xavier and McGuinness, Kevin and O'Connor, Noel E.},
title = {Shallow and Deep Convolutional Networks for Saliency Prediction},
booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
month = {June},
year = {2016}
}
````

You may also want to refer to our publication with the more human-friendly Chicago style:

*Junting Pan, Kevin McGuinness, Elisa Sayrol, Noel E. O'Connor, and Xavier Giro-i-Nieto. "Shallow and Deep Convolutional Networks for Saliency Prediction." In Proceedings of the IEEE International Conference on Computer Vision (CVPR). 2016.*

## Framework
![QFramework saliency detection](https://github.com/ChunbiaoZhu/ACVR2017/blob/master/images/fig1.png)


## Visual Results

![Visual Results saliency detection](https://github.com/ChunbiaoZhu/ACVR2017/blob/master/images/fig4.pngg)


## Website
https://chunbiaozhu.github.io/ACVR2017/

## Posterior work

If you were interested in this work, you may want to also check our posterior work, [CAIP2017](https://chunbiaozhu.github.io/CAIP2017/), which offers a better performance.

## Acknowledgements

This work was supported by the grant of National Natural Science Foundation of China (No.U1611461), Shenzhen Peacock Plan (20130408-183003656), and Science and Technology Planning Project of Guangdong Province, China (No. 2014B090910001).


## Contact

If you have any general doubt about our work or code which may be of interest for other researchers, please use the [public issues section](https://github.com/ChunbiaoZhu/ACVR2017/issues) on this github repo. Alternatively, drop us an e-mail at <mailto:zhuchunbiao@pku.edu.cn>.

<!---
Javascript code to enable Google Analytics
-->

<!---
<script>
-->
<!---
(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
})(window,document,'script','//www.google-analytics.com/analytics.js','ga');
-->
<!---
ga('create', 'UA-7678045-3', 'auto');
ga('send', 'pageview');
-->
<!---
</script>
-->
