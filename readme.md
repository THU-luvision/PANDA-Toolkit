## PANDA Dataset Toolkit

[**PANDA**](http://www.panda-dataset.com/) is the first Gigapixel-level human-centric video dataset, for large-scale, long-term, and multi-object visual analysis, which is published on CVPR 2020. 

![](PANDA-teaser.gif)



This toolkit provide the following function:

- Load and image, and show the bounding box on it.
- Evaluate the object detection result.
- Split and merge the picture and label.



**If you use our dataset or toolkit, please cite the following paper:** [PDF](http://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_PANDA_A_Gigapixel-Level_Human-Centric_Video_Dataset_CVPR_2020_paper.pdf) 

@inproceedings{wang2020panda, title={PANDA: A Gigapixel-level Human-centric Video Dataset}, author={Wang, Xueyang and Zhang, Xiya and Zhu, Yinheng and Guo, Yuchen and Yuan, Xiaoyun and Xiang, Liuyu and Wang, Zerun and Ding, Guiguang and Brady, David J and Dai, Qionghai and Fang, Lu}, booktitle={Computer Vision and Pattern Recognition (CVPR), 2020 IEEE International Conference on}, year={2020}, organization={IEEE} }




### Installation
1. Environment: **Python 3**
2. Get PANDA from [download page](http://www.panda-dataset.com/Download.html).
3. Install dependencies
```
    pip install -r requirements.txt
```


### Usage

1. Please see tool kit function demonstration in "demo.py"
2. Reading and visualizing data, you can use "PANDA.py"
3. Evaluating the result, you can refer to the "DetEval.py" and "MOTEval.py" 
4. Split the large image, you can refer to the "ImgSplit.py"
5. Merging the results detected on the patches, you can refer to the "ResultMerge.py"

