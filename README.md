# Medical imaging

That repository contains several methods, applied to the problems of Medical Imaging.<br>
- The first model is for the Segmentation of Nevus images (located in "nevus_segmentation.ipynb").
In that project the nevus images segmentation is performed with PyTorch.<br>
Standard **SegNet** is tried with different losses (BCE, Focal loss, Dice loss), as well as **Unet** with different upsampling mechanisms.<br>
The data is taken from the [ADDI project](https://www.fc.up.pt/addi/ph2%20database.html).
