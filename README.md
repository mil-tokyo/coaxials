# Coaxials dataset
  - Coaxials dataset was created in a research on the semantic segmentation task of automonous mobility robots operating near humans.
  - The dataset contains coaxial color (RGB) images and long wavelength infrared (LWIR) images captured with the same optical axis.
  - As a notable feature of the dataset, one of the annotated labels is "glass", such as windows, walls, and automatic doors. Glass is transparent in color images but opaque in LWIR images.
  - According to our [paper](https://ieeexplore.ieee.org/document/8968095), you can detect transparent glass using coaxial RGB and LWIR images.

# Images and annotations
  - The images was captured with a coaxial camera, FIRplus, manufactured by the ViewPlus Corporation, Japan.
  - The dataset contains 17,023 image pairs, which is divided into 8,050 pairs of learning data, 8,373 pairs of evaluation data, and 600 pairs of verification data.
  - Nine labels were annotated: glass, pedestrian, road, aisle, tree, bicycle, car, devaluation, and curb.
  - The images were captured in eight lighting condition: daytime (clear sky, cloudy, rainy, snowy, indoor), evening, and night.

  - Examples of image# Images and annotations

![Image example](https://github.com/mil-tokyo/coaxials/blob/master/ImageExample.jpg)

# Download dataset
  - Coaxials dataset is available on [google drive](https://drive.google.com/file/d/1bHfDfEAUqSQS59kkus4pZoQsyCZPmwaJ/view?usp=sharing). The file size is about 3 GB.

# Citation
  - If you use Coaxials dataset in your work, please cite the following paper.
    ```
    @PROCEEDINGS{coaxials-2019,
      title = {Simultaneous transparent and non-transparent object segmentation with multispectral scenes},
      author = {Okazawa, Atsuro and Takahata, Tomoyuki and Harada, Tatsuya},
      booktitle = {2019 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS2019)},
      year = {2019}
    }
    ```
