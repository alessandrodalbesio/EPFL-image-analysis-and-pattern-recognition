# Image Analysis and Pattern Recognition

## Course information
* Lecturer: [Jean-Philippe Thiran][jpt]
* [EE-451 coursebook][coursebook]

[jpt]: https://people.epfl.ch/115534
[coursebook]: https://edu.epfl.ch/coursebook/en/image-analysis-and-pattern-recognition-EE-451

## Team members
This project has been done by:
- Alessandro Dalbesio
- Gianluca Radi
- Camillo Nicolò De Sabbata

## Repository content
You can find the following files in this repository:
- `README.md`: this file
- `report.pdf`: the report of the project. This is a brief summary of the work done, the results obtained at the different steps and the discussion of the choices made.
- `data_project/`: the folder containing the data of the project. It contains the following folders:
  - `input`: the input data during the defence. It contains both already seen images that have been used for the training and new images that have never been seen before.
  - `solutions`: the output data with the following structure:
    - `mask`: the masks obtained after the tresholding.
    - `feature_map`: the feature map obtained after the pipeline.
    - `cluster_image`: the clusters obtained after the pipeline.
  - `project_description`: the file containing the code to load and preprocess the data.
  - `training`: the training dataset.