# tencentarc/gfpgan Cog model

This is an implementation of the [tencentarc/gfpgan](https://github.com/TencentARC/GFPGAN) as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

First, download the pre-trained weights:

    cog run script/download-weights

Then, you can run predictions:

    cog predict -i img=@demo.jpg

## Example

Input:

![alt text](demo.jpg)

Output:

![alt text](output.jpg)
