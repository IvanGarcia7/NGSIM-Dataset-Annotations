# Manually annotated video sequences

These video sequences have been annotated in order to carry out the evaluation phase of the proposal presented in the following link:

* https://github.com/IvanGarcia7/ALAF

Four video sequences from US Highway 101 Dataset have been used. These videos has been captured by highway video surveillance systems from high perspective and belong to the U.S. Department of Transportation. These systems collect a series of sequences with a large number of small vehicles. The sequences have a total duration of about 15 minutes. See more info in the following url: 

* https://www.fhwa.dot.gov/publications/research/operations/07030/index.cfm

From the beginning of each video sequence, 1 minute has been manually annotated (632 manually labeled images with a total of 19343 vehicles) in order to evaluate our proposal by obtaining the Mean Average Precision (mAP) once the fine tuning has been applied. 

In addition, the annotations created for the M30-HD sequence of the dataset named GRAM are included.

# Content:

For each of the video sequences, the set of frames that made up the video have been labeled, including these images in the following links:

* https://github.com/IvanGarcia7/NGSIM-Dataset-Annotations/tree/main/Sequence1/images
* https://github.com/IvanGarcia7/NGSIM-Dataset-Annotations/tree/main/Sequence2/images
* https://github.com/IvanGarcia7/NGSIM-Dataset-Annotations/tree/main/Sequence3/images
* https://github.com/IvanGarcia7/NGSIM-Dataset-Annotations/tree/main/Sequence4/images
* https://github.com/IvanGarcia7/NGSIM-Dataset-Annotations/tree/main/M30-HD/images

Additionally, the JSON in COCO format has been included to carry out the tests.

# Information:

If you use some of the sequences established in this repository, don't forget to cite both the original datasets as well as the following articles:

```
@article{GarcaAguilar2021,
  doi = {10.1111/exsy.12930},
  url = {https://doi.org/10.1111/exsy.12930},
  year = {2021},
  month = dec,
  publisher = {Wiley},
  volume = {39},
  number = {2},
  author = {Iv{\'{a}}n Garc{\'{\i}}a-Aguilar and Rafael Marcos Luque-Baena and Ezequiel L{\'{o}}pez-Rubio},
  title = {Improved detection of small objects in road network sequences using
		            {CNN}
		            and super resolution},
  journal = {Expert Systems}
}
```
