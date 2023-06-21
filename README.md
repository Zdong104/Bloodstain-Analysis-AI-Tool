# Bloodstain Analysis AI Tool

## Authors

[Zihan Dong](https://github.com/Zdong104/), Zhengdong Zhang


[[`Paper`](https://kdd.org/kdd2023/workshops/)] 
[[`Default SAM`](https://dl.fbaipublicfiles.com/segment_anything/sam_vit_h_4b8939.pth)]
[[`Fine Tuned SAM`](https://drive.google.com/file/d/1mvh81GEjU7Z2ExLVQyUotMUV0l84UpO0/view?usp=drive_link)] 
[[`Dataset`](https://alvideo.ameslab.gov/archive/bpa-videos/)]
[[`BibTeX`](#Citing-Paper)]

## Introduction: 
Bloodstain pattern analysis plays a crucial role in crime scene investigation by studying unique blood patterns to uncover vital details about the events that occurred. Traditional manual analysis methods are time-consuming and require expertise. However, recent advancements in computer vision and AI technology offer innovative solutions. This study focuses on utilizing the Segment-Anything model developed by Meta to enhance the accuracy of blood droplet prediction. By leveraging this advanced AI model, mechanical engineers and criminology analysts can benefit from improved data processing accuracy and reliable image predictions, leading to increased efficiency and valuable insights in crime scene analysis.

## Demo notebooks
Using SAM Model and Video-to-Frame Conversion. In this demo, we will explore how to utilize the SAM (Segment Anything Model) and how to extract frames from videos and save them as images for further analysis. The demo will consist of two separate Jupyter Notebook files in the repo above. The instructions in the notebook will guide you through each notebook's purpose and usage. If you have any additional questions, please feel free to ask in the discussion community.


## License 
The model is licensed under the Apache 2.0 license.
The code is licensed under the MIT license. 



## Citing Paper

If you use code and fine tuned SAM in your research, please use the following BibTeX entry.

```
@article{kirillov2023segany,
  title={Segment Anything},
  author={Kirillov, Alexander and Mintun, Eric and Ravi, Nikhila and Mao, Hanzi and Rolland, Chloe and Gustafson, Laura and Xiao, Tete and Whitehead, Spencer and Berg, Alexander C. and Lo, Wan-Yen and Doll{\'a}r, Piotr and Girshick, Ross},
  journal={arXiv:2304.02643},
  year={2023}
}
```


## Related work
[Segment Anything Model by Facebook Meta](https://github.com/facebookresearch/segment-anything/)
