Awosome Underwater Datasets
============================
Underwater Image Enhancement （UIE)
----------------------------
|Dataset|Data|Paper|More|
| --- | --- | --- | --- |
|EUVP dataset|[Data](http://irvlab.cs.umn.edu/resources/euvp-dataset)|[Paper](https://arxiv.org/abs/1903.09766)|paired and unpaired data; FUnIE-GAN|
|Underwater imagenet|[Data](http://irvlab.cs.umn.edu/resources/)|[Paper](https://ieeexplore.ieee.org/document/8460552)|paired data; UGAN|
|UIEBD dataset|[Data](https://li-chongyi.github.io/proj_benchmark.html)|[Paper](https://arxiv.org/abs/1901.05495)|890 paired, 60 unpaired data; Water-Net|
|SQUID dataset|[Data](http://csms.haifa.ac.il/profiles/tTreibitz/datasets/ambient_forwardlooking/index.html)|[Paper](https://arxiv.org/abs/1811.01343)|paired data|
|RUIE benchmark|[Data](https://github.com/dlut-dimt/Realworld-Underwater-Image-Enhancement-RUIE-Benchmark)|[Paper](https://arxiv.org/abs/1901.05320)|unpaired data; UCCS, UIQS, UTTS|
|[UMIE dataset](#UMIE-dataset)|[Data](https://github.com/Idea89560041/UMIE)|[Paper](https://ieeexplore.ieee.org/document/10275315)|unpaired data; UMRD|
|SeaThru dataset|[Data](https://www.kaggle.com/datasets/colorlabeilat/seathru-dataset?resource=download)|[Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Akkaynak_Sea-Thru_A_Method_for_Removing_Water_From_Underwater_Images_CVPR_2019_paper.pdf)|unpaired data; RGB-D|
|RQSD-UI dataset|[Data](https://justwj.github.io/CLUIE-Net.html/)|[Paper](https://justwj.github.io/CLUIE-Net.html/)|1635 raw from SUIM*12 enhance results, QSmaps; CLUIE|
||[Data]()|[Paper]()||

Underwater NeRF
----------------------------
|Dataset|Data|Paper|More|
| --- | --- | --- | --- |
|SeaThru-NeRF|[Data](https://sea-thru-nerf.github.io/)|[Paper](https://arxiv.org/pdf/2304.07743.pdf)||
||[Data]()|[Paper]()||

Other
---------------------------
|Dataset|Data|Paper|More|
| --- | --- | --- | --- |
|SSRanking|[Data](https://github.com/yzliangHIK2022/SSRanking-for-Object-BA)|[Paper](https://github.com/yzliangHIK2022/SSRanking-for-Object-BA)|图像模糊度评价数据集|
||[Data]()|[Paper]()||

#### UMIE dataset
3.7K高质量图像及其合成的噪声、模糊图像，4.2K色差图像
其文中所述11.1K (3.7K*3) paired and 7.9K (3.7K+4.2K) unpaired
#### RQSD-UI dataset
RQSD-UI dataset contains 5 folders: E_imgs, train-validation_pairs, test_pairs, train-validation-GT-QSmaps, test-GT-QSmaps.
(1)E_imgs: 12 kinds of enhancement methods' results corresponding to 1635 raw underwater images.
(2)train-validation_pairs: contains 4 txt files:train-Cons.txt, train-Cons-L1.txt, train-Cons-L2.txt, train-Cons-L3.txt.
(3)test_pairs: contains 4 txt files:test-Cons.txt, test-Cons-L1.txt, test-Cons-L2.txt, test-Cons-L3.txt.
(4)train-validation-GT-QSmaps: all the train-validation-GT-QSmaps for training.
(5)test-GT-QSmaps: all the test-GT-QSmaps.
