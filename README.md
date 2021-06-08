# SimSwap: An Efficient Framework For High Fidelity Face Swapping
## Proceedings of the 28th ACM International Conference on Multimedia
**The official repository with Pytorch**

Currently only the test code is available, training scripts are coming soon

[[Conference paper]](https://dl.acm.org/doi/10.1145/3394171.3413630)



## Results
![Results1](/doc/img/results1.PNG)

![Results2](/doc/img/total.PNG)

## Video
<img src="./doc/img/video.webp"/>

**High-quality videos can be found in the link below:**

[[Baidu Drive link for video]](https://pan.baidu.com/s/1WTS6jm2TY17bYJurw57LUg ) Password: ```b26n```

## Dependencies
- python3.6+
- pytorch1.5+
- torchvision
- opencv
- pillow
- numpy


## Usage
### To test the pretrained model
```
python test_one_image.py --isTrain false  --name people --Arc_path models/BEST_checkpoint.tar --pic_a_path crop_224/mars.jpg --pic_b_path crop_224/ds.jpg --output_path output/
```

--name refers to the checkpoint name.

## Pretrained model
[[Google Drive]](https://dl.acm.org/doi/10.1145/3394171.3413630)
[[Baidu Drive]](https://pan.baidu.com/s/1wFV11RVZMHqd-ky4YpLdcA) Password: ```jd2v```


## To cite our paper
```
@inproceedings{DBLP:conf/mm/ChenCNG20,
  author    = {Renwang Chen and
               Xuanhong Chen and
               Bingbing Ni and
               Yanhao Ge},
  title     = {SimSwap: An Efficient Framework For High Fidelity Face Swapping},
  booktitle = {{MM} '20: The 28th {ACM} International Conference on Multimedia},
  pages     = {2003--2011},
  publisher = {{ACM}},
  year      = {2020},
  url       = {https://doi.org/10.1145/3394171.3413630},
  doi       = {10.1145/3394171.3413630},
  timestamp = {Thu, 15 Oct 2020 16:32:08 +0200},
  biburl    = {https://dblp.org/rec/conf/mm/ChenCNG20.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```

## Related Projects
Learn about our other projects [[RainNet]](https://neuralchen.github.io/RainNet), [[Sketch Generation]](https://github.com/TZYSJTU/Sketch-Generation-with-Drawing-Process-Guided-by-Vector-Flow-and-Grayscale), [[CooGAN]](https://github.com/neuralchen/CooGAN), [[Knowledge Style Transfer]](https://github.com/AceSix/Knowledge_Transfer), [[SimSwap]](https://github.com/neuralchen/SimSwap).