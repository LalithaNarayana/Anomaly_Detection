# Anomaly_Detection
This project involves training a DenseNet121-based deep learning model to classify images into 14 different anomaly categories using TensorFlow. The model is then used to analyze video frames for activity detection, displaying real-time activity labels and tracking occurrences of each activity type.

https://github.com/user-attachments/assets/a26a587a-868b-4afc-a2db-da5566efcebf

```markdown
# Anomaly Detection in Images and Videos

## Overview
This project trains a DenseNet121-based model to classify images into 14 anomaly categories. After training, the model is used to analyze video frames, detecting and labeling activities in real-time. The results are visualized with activity counts and confidence scores.

## Requirements
- Python 3.x
- TensorFlow
- OpenCV
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- scikit-learn

Install the required packages using:
```bash
pip install pandas numpy matplotlib seaborn plotly tensorflow scikit-learn opencv-python
```

## Data Preparation
- **Train Directory**: `F:\\Anomaly_Images\\Train`
- **Test Directory**: `F:\\Anomaly_Images\\Test`

## Training
The model is trained using data from the specified directories, with an initial learning rate of `0.00003` and trained for `10` epochs. The trained model is saved to `F:\\Model_Saved\\Trained\\ADmodel.keras`.

## Video Analysis
- **Video Path**: Path to the video file you want to analyze (e.g., `C:\\Users\\lalit\\Desktop\\New folder\\New folder\\gun.mp4`).
- **Output Directory**: Directory to store extracted frames (e.g., `output_frames`).

Run the `display_video_with_activity` function to analyze the video and display real-time activity detection results.

## Usage
1. Modify the paths in the script to match your directories and video file location.
2. Execute the script to train the model and analyze the video.

## License
This project is licensed under the MIT License.
```

This README provides a concise overview of the project, including setup instructions, data preparation, training, and usage details. Adjust the paths and filenames as needed for your specific environment.
