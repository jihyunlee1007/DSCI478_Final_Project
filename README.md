# README

It is recommended to create a virtual environment when running this notebook to handle all of the necessarry packages. 

Make sure to change the kernel to be the same as the virtual environment managing the dependencies.

Convolutional Neural Networks can be computationally expensive. Make sure that you have the required hardware and packages to support the computational load. More on this in the notebook.

----------------------------------------------------------------------------------------------------------------------

After downloading the repository, change base_dir to the location of where the repo was extracted to. Make sure to either use r'C:\path_to_base' or 'C:\\path_to_base' format for the path declaration.

The code will generate the overlaid images and augmented dataset in the MouseNeuroImages folder. The code will process records from the Capstne_histology_data.xlsx sheet.

----------------------------------------------------------------------------------------------------------------------

When running the code, skip the UNET model training unless you have certain parameters that you want to specifically tune and have at least 20 minutes to spare.

The trained U-NET model that is best for the mask predictions of the images in this repository is located here "unet_model_best.h5". The path should already be correctly specified in the code.

-----------------------------------------------------------------------------------------------------------------------

Blob detection is done on the original overlaid images to display the results in Step 7. This does not use the predicted mask and is mostly meant to demonstrate another approach outside of a U-NET model.

The experimental section contains post-processing done on the predicted masks. The results were abysmal, thus it remains experimental. More on how this experimental design can be improved upon is included in the paper.

---------------------------------------------------------------------------------------------------------------------

## Dependencies

- Python 3.8+
- NumPy
- Pandas
- OpenCV
- scikit-image
- scikit-learn
- TensorFlow
- Keras
- Keras Tuner
- matplotlib
- PIL
- logging
- json
- shutil
- glob
- multiprocessing
- re (Regular Expressions)
  
pip install numpy pandas scikit-learn scikit-image tensorflow keras keras-tuner matplotlib Pillow


-----------------------------------------------------------------------------------------------------------------------





