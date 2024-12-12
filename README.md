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

![](images/e46db0d3e5a5f8665a1f1656a3891c4837492ff8.jpg)

### (2) Inner Missing Piece

![](images/5762110b70d3e8e188a8261e1317dadb81a0068c.jpg)

### (3) Impurity

![](images/93996cb9f197356ff6a69dfff23977362631afcd.jpg)

### (4) Crack

![](images/6b75e88c5900653c88b9de2b275c2cb866bf53cb.jpg)

### (5) Circle Crack

![](images/ede578546068fe62568f2e28c4cac6ab7f3705f5.jpg)

### (6) Mucosa

![](images/b865b290d080da361deef70c6e48cdc9ba88f5fd.jpg)

If you want to browse more images, you can use the script (utils/visualize.py) provided in the downloaded files. The usage is as follows:

- browse by image path or directory: "python utils/visualize.py -p images/"

- browse by defect category: "python utils/visualize.py -c crack"


