<p align="center">
  <a href="https://www.perceptilabs.com">
  <img src="./pl_logo.png">
  </a>
</p>

# Metal Defect Dataset
This dataset<sup>1</sup> contains 224x224-pixel images of defects found in metal sheets.

The data can be used to build and train an ML model that can detect defects in materials. 

# Structure
This repo has the following structure:
* **/data/\<subdirectory name\>**: the various subdirectories contain images of the defects indicated by their respective subdirectory name (descriptions are provided below).
* **/data/defect_ten_log.csv**: CSV file that maps the images to 10 nominal classification values for use in loading the data into PerceptiLabs. 

The following shows a partial example of the data stored in the CSV file:

| image_path | target |
| :---------- | :------ |
| silk_spot/silkspot_640.jpeg | 6 |
| water_spot/waterspot_20.jpeg | 8 |

The following table lists the 10 nominal defect classifications values and provides a brief description of each defect: 

| Defect | Nominal Classification Value | Description |
| :---------- | :------ | :------- |
| Crease | 0 | Vertical or transverse folds across a metal strip caused during the uncoiling process. |
| Crescent Gap | 1 | Defects caused by cutting, in the shape of a half circle.
 |
| Inclusion | 2 | Surface defects in various shapes (e.g., fish scale shape) which may be loose and easy to fall off or pressed into the metal.
 |
| Oil Spot | 3 | Contamination caused by mechanical lubricant that affects the product's appearance.
 |
| Punching | 4 | Steel strips with additional, unwanted punching holes caused by mechanical failure. |
| Rolled Pit | 5 | Periodic bulges or pits on the metal's surface often caused by work or tension roll damage.
 |
| Silk Spot | 6 | Wave-like plaque on the surface often caused by the uneven pressure or temperature of a roller.
 |
| Waist Folding | 7 | A weld line that occurs when a steel strip is changed. 
 |
| Water Spot | 8 | Spots which occur when drying the metal during production.
 |
| Welding Line | 9 | Wrinkle-like folds caused by low-carbon.
 |

<b>Note</b>: see [Kaggle](https://www.kaggle.com/zhangyunsheng/defects-class-and-location) for additional information about these defects.


# Community

Got questions, feedback, or want to join a community of machine learning practitioners working with exciting tools and projects? Check out our [Community](https://forum.perceptilabs.com/)!

<sup>1</sup> Dataset Credits: https://www.kaggle.com/zhangyunsheng/defects-class-and-location
