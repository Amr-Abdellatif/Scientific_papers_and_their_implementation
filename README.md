# Scientific_papers_and_their_implementation

## youtube explanation playlist in arabic
https://www.youtube.com/playlist?list=PLhBhgortqAchR5-n6XT73BSdIfCISwAEw

## lets talk about science

### A brief intro to CNN :
The convolutional operation is a fundamental component of a convolutional neural network, as its name suggests. In computer vision, an image can be represented as a matrix of RGB values. For instance, the following 6x6 matrix can be considered as a segment of an image:

![1_aGSthcPASa2OT1UBm7paOA](https://user-images.githubusercontent.com/92921252/231789798-484be4ac-bea0-4396-80e8-d8301cb7f9d2.png)


And the filter will be the following matrix:


![1_591OPcvDKUN9liZ_VQ1M5g](https://user-images.githubusercontent.com/92921252/231789869-3081a327-7187-4897-8e18-962dcf906d4f.png)


## how CONVOLUTION works :
![1_VJCoCYjnjBBtWDLrugCBYQ](https://user-images.githubusercontent.com/92921252/231789315-db1860ba-c4aa-4f6c-818e-bb78837ab39e.gif)

## Maxpooling :

Maxpooling consist of extracting features from input feature map and outputig maximum value of each channel.

![1_Ziqq69FhwOAbBi9-FNruAA](https://user-images.githubusercontent.com/92921252/231790840-99a8a7db-fabf-48a4-8e9b-b7a245b4fc04.png)

## since we're talking about Pooling 
There's something called ROI pooling in which we mmap a fixed size input to a fixed size output and based on the calculations in the figure we approximate the size of Stride to reach the output 

![Capture](https://user-images.githubusercontent.com/92921252/235786448-8db42d29-7ff0-407a-86a1-860eed5f1627.JPG)


## padding = zero 

we add zero frame pixels around the image so we don't lose any information in the edges it's called zero padding 
in code it's called using keras and written like (padding = "same") and the name comes from the idea of keeping the same pixel size after applying the padding

![1_O06nY1U7zoP4vE5AZEnxKA](https://user-images.githubusercontent.com/92921252/231793881-14366d3e-e73b-42f9-b745-40c18fa0e5cf.gif)



