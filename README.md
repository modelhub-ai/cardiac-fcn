# cardiac-fcn

This repository hosts the contributor source files for the cardiac-fcn model. ModelHub integrates these files into an engine and controlled runtime environment. A unified API allows for out-of-the-box reproducible implementations of published models. For more information, please visit [www.modelhub.ai](http://modelhub.ai/) or contact us [info@modelhub.ai](mailto:info@modelhub.ai).

## meta

|                  |                                       |
| ---------------- | ------------------------------------- |
| id               | 985c8604-1381-4ebf-85af-bfe32080fb55  |
| application_area | Cardiac Imaging                       |
| task             | Segmentation                          |
| task_extended    | Segmenting the right ventricle in MRI |
| data_type        | Magnetic Resonance (MRI)              |
| data_source      | http://www.litislab.fr/?projet=1rvsc  |

## publication

|                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| title          | A Fully Convolutional Neural Network for Cardiac Segmentation in Short-Axis MRI                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| source         | arXiv                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| url | https://arxiv.org/abs/1604.00494 |
| year           | 2016                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| authors        | Phi Vu Tran                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| abstract       | Automated cardiac segmentation from magnetic resonance imaging datasets is an essential step in the timely diagnosis and management of cardiac pathologies. We propose to tackle the problem of automated left and right ventricle segmentation through the application of a deep fully convolutional neural network architecture. Our model is efficiently trained end-to-end in a single learning stage from wholeimage inputs and ground truths to make inference at every pixel. To our knowledge, this is the first application of a fully convolutional neural network architecture for pixel-wise labeling in cardiac magnetic resonance imaging. Numerical experiments demonstrate that our model is robust to outperform previous fully automated methods across multiple evaluation measures on a range of cardiac datasets. Moreover, our model is fast and can leverage commodity compute resources such as the graphics processing unit to enable state-of-the-art cardiac segmentation at massive scales. The models and code are available at https://github.com/vuptran/cardiac-segmentation. |
| google_scholar | https://scholar.google.com/scholar?um=1&ie=UTF-8&lr&cites=6323192966698785729                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| bibtex         | @article{DBLP:journals/corr/Tran16, author = {Phi Vu Tran}, title = {A Fully Convolutional Neural Network for Cardiac Segmentation in Short-Axis {MRI}}, journal = {CoRR}, volume = {abs/1604.00494}, year = {2016}, url = {http://arxiv.org/abs/1604.00494}, archivePrefix = {arXiv}, eprint = {1604.00494}, timestamp = {Wed, 07 Jun 2017 14:41:57 +0200}, biburl = {http://dblp.org/rec/bib/journals/corr/Tran16}, bibsource = {dblp computer science bibliography, http://dblp.org} }                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |

## model

|               |                                                                                                                                                                                                                                                                                      |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| description   | The proposed FCN architecture is efficiently trained end-to-end on a graphics processing unit (GPU) in a single learning stage from whole image inputs and ground truths to make inference at every pixel, a task commonly known as pixel-wise labeling or per-pixel classification. |
| architecture  | Fully Convolutional Neural Network (FCN)                                                                                                                                                                                                                                             |
| learning_type | Supervised learning                                                                                                                                                                                                                                                                  |
| format        | .h5                                                                                                                                                                                                                                                                                  |
| I/O           | model I/O can be viewed [here](contrib_src/model/config.json)                                                                                                                                                                                                                        |
| license       | model license can be viewed [here](contrib_src/license/model)                                                                                                                                                                                                                        |

## run

To run this model and view others in the collection, view the instructions on [ModelHub](http://app.modelhub.ai/).

## contribute

To contribute models, visit the [ModelHub docs](https://modelhub.readthedocs.io/en/latest/).
