# Image-Inpainting | Photo Reconstruction

Developing generative models capable of restoring and reconstructing the absent or damaged sections of images.

Our photos are often damaged over the years, old artifacts and manuscripts, over time, get degraded, and certain parts of the image can go missing. Even in the digital domains, sometimes, due to network issues and unreliability in some regions, images may be missing parts or have lower resolutions. This challenge will focus on building models with the generative ability to reconstruct images' lost/damaged parts.

## Input
* Animal images (256 x 256) with missing sections (masks)
* Missing sections are in the form of squares of 75 x 75, and exactly two are in each image.
* Information about the masks will be provided

  ![image](https://github.com/ssneeraj23/Image-Inpainting/assets/101348975/1db7e591-7fc7-46a0-9e68-26c0e65d8d38)

## Output
* Animal image reconstructed (256 x 256)

### Some more results of the model are as follows
![Screenshot from 2023-07-08 13-59-57](https://github.com/ssneeraj23/Image-Inpainting/assets/101348975/079f1789-1e9f-4952-a51a-4c206b1fbee5)
![Screenshot from 2023-07-08 14-00-30](https://github.com/ssneeraj23/Image-Inpainting/assets/101348975/9c3ad5d2-1884-47ea-bce8-301ffc2a22cd)
![Screenshot from 2023-07-08 14-00-43](https://github.com/ssneeraj23/Image-Inpainting/assets/101348975/8dfe9f69-ffe4-45e2-b8ba-e6234b5f5396)



