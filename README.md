
# Chest X-Ray Image Classifier

In this project, I've chosen to work with the ["Large Dataset of Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images"](https://data.mendeley.com/datasets/rscbjbr9sj/3) for the purpose of creating a binary image classification model.

The notebook found in `student.ipynb` records the start-to-finish Data Science Process, from preprocessing and exploration to modeling and interpreting. Ultimately, this work aims to predict whether a given pediatric patient has pneumonia, given a chest x-ray image.

![xray](https://media.giphy.com/media/7HeN31sikXE76/giphy.gif)


## Repository directory

The full download of the data is quite large as constituted (7.9 GB). But most of what is contained in the download is actually not pertinent to this project. There is is the `chest_xray` folder, which is of course necessary, and which stands at 1.27 GB. What's left is a much larger folder of OCT images for diagnosing various eye conditions, which can be discarded.

After downloading, I manually moved the relevant folder, `chest_xray`, into this project repository.

The `chest_xray` folder is sectioned into `train` and `test` subfolders, each of which is further sectioned into `NORMAL` and `PNEUMONIA` subfolders. Without a dedicated folder for validation data, I manually created a `validation` folder in `chest_xray` and manually moved sixteen samples from each class of the testing set into it, making sure to choose an equal number of bacterial and viral pneumonia cases, as indicated by their respective files names. (Images may not be available here due to the folder's large size.)

The six `.h5` files are saved models that were trained in `student.ipynb`, in keeping with the iterative approach to modeling as required by the project guidelines. (Files may not be available due to their large size.)

See below for more on `presentation.pdf`.


## Executive Summary

Among the deliverables for this project is that I prepare and deliver a mock "executive summary" presentation, giving a brief overview of your problem/dataset, and each step of the OSEMN process, in a non-technical manner.

The PowerPoint slides used in this executive summary presentation are located in `presentation.pdf`.


## Blog post

Visit https://medium.com/@timsennett/unfreezing-the-layers-you-want-to-fine-tune-using-transfer-learning-1bad8cb72e5d to read my blog post on a topic related to this project.


## Support 

Reach out to me on [LinkedIn](https://www.linkedin.com/in/timsennett/) for further support, or any feedback worth sharing.
