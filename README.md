# Magnetic Ring Surface Defect Dataset (MRSDD)

The Magnetic Ring Surface Defect Dataset (MRSDD) is a new large-scale industrial defect dataset for benchmarking, which consists of over 10000 acquired images of actual defective magnetic rings. 

We are not yet able to make the entire dataset publicly available. The final content and format of its release still require further discussion and approval from the commissioning party of this defect detection task, given the large scale of MRSDD and the mass of unlabeled images it contains. 

At present, we are authorized to release a subset of our image data for preview purposes. We will open-source the rest images as soon as possible.

The released subset of the MRSDD can be downloaded from the following addresses:

- Baidu Netdisk: https://pan.baidu.com/s/1ltQVvXJpxSZ4ahhgNeEFhw (code: mrsd)

- Quark Netdisk: https://pan.quark.cn/s/843baf3916b4 (code: 1Aip)

## MRSDD

MRSDD contains six typical surface defects that may occur on a magnetic ring: ***outer missing piece***, ***inner missing piece***, ***impurity, crack***, ***circle crack***, and ***mucosa***.

In the following, some acquired images are provided to offer a clear demonstration of the MRSDD.

### (1) Outer Missing Piece

![](https://github.com/zfli-xdu/MRSDD/blob/master/demos/outer_misspiece/outer_misspiece.jpg?raw=true)

### (2) Inner Missing Piece

![](https://github.com/zfli-xdu/MRSDD/blob/master/demos/inner_misspiece/inner_misspiece.jpg?raw=true)

### (3) Impurity

![](https://github.com/zfli-xdu/MRSDD/blob/master/demos/impurities/impurities.jpg?raw=true)

### (4) Crack

![](https://github.com/zfli-xdu/MRSDD/blob/master/demos/crack/crack.jpg?raw=true)

### (5) Circle Crack

![](https://github.com/zfli-xdu/MRSDD/blob/master/demos/circle_crack/circle_crack.jpg?raw=true)

### (6) Mucosa

![](https://github.com/zfli-xdu/MRSDD/blob/master/demos/mucosa/mucosa.jpg?raw=true)

If you want to browse more images, you can use the script (utils/visualize.py) provided in the downloaded files. The usage is as follows:

- browse by image path or directory: "python utils/visualize.py -p images/"

- browse by defect category: "python utils/visualize.py -c crack"
