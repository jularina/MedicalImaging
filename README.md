# Medical imaging

That repository contains several methods, applied to the problems of Medical Imaging.<br>
- The first model is for the Segmentation of Nevus images (located in "nevus_segmentation.ipynb").<br>
In that project the nevus images segmentation is performed with PyTorch.<br>
Standard **SegNet** is tried with different losses (BCE, Focal loss, Dice loss), as well as **Unet** with different upsampling mechanisms.<br>
The data is taken from the [ADDI project](https://www.fc.up.pt/addi/ph2%20database.html).

- The second model solves the autoencoding program on blood cell data (located in "vae_cells.ipynb").<br>
Here VAE architecture is applied to find the distribution of the blood cells images and create new ones in the future. Due to the privacy reasons, it can be hard to get such medical data in large volumes, but such model can produce these large amounts of data for the purposes of future exploring different types of normal peripheral blood cells. 
The source of the data is the Hospital Clinic de Barcelona, the data is stored in [Mendeley Data](https://data.mendeley.com/datasets/snkd93bnjr/1).
