# Diffusion-Network
This implementation leverages the principles of diffusion networks, tailored specifically for processing low-resolution images. By utilizing the CIFAR-10 dataset, which comprises diverse categories of objects in low-resolution images, this approach aims to capture intricate details and subtle features within the constrained pixel space. Through iterative diffusion processes, the network gradually refines representations, allowing for enhanced recognition and classification of objects despite the limited resolution. This adaptation showcases the versatility of diffusion networks in handling various image complexities, even in lower resolutions.

##  Requirements

Use the .YAML file to create a virtual environment and train the model, run the below code create "diffusion" virtual environment 

```conda env create -f environment.yaml```

## Overview of Repository Contents

- **models.py**: Contains implementations of the UNet architecture model and the Diffusion model utilized in the project.

- **train_prototype.ipynb**: Jupyter Notebook featuring code for downloading, training, and inferring using the diffusion model.

- **environment.yaml**: Generated file encompassing all dependencies utilized in the project, essential for creating a Virtual environment.

## Training the Model and Generating Images

To train the model or generate images using the inference model, execute the cells within the provided Jupyter Notebook. Any modifications to the architecture can be made in the models.py file.

## Visualizing Real and Synthetic Images

### CIFAR-10
![CIFAR-10 Images](./images/cifar10_1000.jpeg)

## References

This implementation draws inspiration from Jonathan Ho's original diffusion models [repository](https://github.com/hojonathanho/diffusion). The PyTorch implementation by OpenAI, available [here](https://github.com/hojonathanho/diffusion), served as a reference for common design choices in diffusion models.

This experiment serves as a learning endeavor into the diffusion process, with intentions to build upon it in future projects.
