# Lung Tumor Detection using YOLOv8 Segmentation Models and Flask Web Application

This project aims to develop an end-to-end solution for lung tumor detection using YOLOv8 segmentation models and a Flask web application. The model is trained on CT scan images collected from various sources to accurately identify tumors within lung scans. The Flask web application enhances usability and reduces processing time, providing a seamless experience for users.

## Key Features

- Utilizes YOLOv8 segmentation models for accurate tumor detection in lung CT scan images.
- Hyperparameter tuning performed to optimize model performance, ensuring superior results.
- Flask web application created to provide an intuitive interface for users.
- End-to-end solution allows for efficient tumor detection without the need for complex setups.


## Demo

### Web Application

![Demo_gif](https://github.com/AbdullahTabassam/Lungs_Tumor_Segmentation/blob/master/Demo.gif)

#### Images

<div>
<img src="https://github.com/AbdullahTabassam/Lungs_Tumor_Segmentation/blob/master/static/images/000117.png" alt="Image" height="250" width="250">
<img src="https://github.com/AbdullahTabassam/Lungs_Tumor_Segmentation/blob/master/static/images/000157.png" alt="Image" height="250" width="250">
<img src="https://github.com/AbdullahTabassam/Lungs_Tumor_Segmentation/blob/master/static/images/000163.png" alt="Image" height="250" width="250">
</div>
<div>
<img src="https://github.com/AbdullahTabassam/Lungs_Tumor_Segmentation/blob/master/static/results/predicted_000117.png" alt="Image" height="250" width="250">
<img src="https://github.com/AbdullahTabassam/Lungs_Tumor_Segmentation/blob/master/static/results/predicted_000157.png" alt="Image" height="250" width="250">
<img src="https://github.com/AbdullahTabassam/Lungs_Tumor_Segmentation/blob/master/static/results/predicted_000163.png" alt="Image" height="250" width="250">
</div>


## Training Results

The model's effectiveness is demonstrated through the following results:

<table style="margin: 0 auto; border-collapse: collapse;">
  <tr>
    <th colspan="4" style="text-align: center;">Box</th>
    <th style="border-left: 1px solid white;"></th>
    <th colspan="4" style="text-align: center;">Mask</th>
  </tr>
  <tr>
    <th style="text-align:center;">Precision</th>
    <th style="text-align:center;">Recall</th>
    <th style="text-align:center;">mAP50</th>
    <th style="text-align:center;">mAP50-95</th>
    <td style="border-left: 1px solid white;"></td>
    <th style="text-align:center;">Precision</th>
    <th style="text-align:center;">Recall</th>
    <th style="text-align:center;">mAP50</th>
    <th style="text-align:center;">mAP50-95</th>
  </tr>
  <tr>
    <td style="text-align:center;">94.1%</td>
    <td style="text-align:center;">94.4%</td>
    <td style="text-align:center;">98.7%</td>
    <td style="text-align:center;">86.4%</td>
    <td style="border-left: 1px solid white;"></td>
    <td style="text-align:center;">94.6%</td>
    <td style="text-align:center;">97.1%</td>
    <td style="text-align:center;">98.9%</td>
    <td style="text-align:center;">81.9%</td>
  </tr>
</table>

## Usage

To utilize the Flask web application:

1. Clone this repository to your local machine.
```bash
git clone https://github.com/AbdullahTabassam/Lungs_Tumor_Segmentation.git
```
2. Install the required dependencies using :
```bash
pip install -r requirements.txt
```
3. Run the Flask application using:
```bash
python app.py
```
4. Access the application through a web browser at `http://localhost:5000`.


## Acknowledgments

- Inspired by the need for efficient and accurate lung tumor detection techniques.
- Built upon the YOLOv8 architecture and Flask framework.
- Grateful to the contributors of open-source libraries utilized in this project.
