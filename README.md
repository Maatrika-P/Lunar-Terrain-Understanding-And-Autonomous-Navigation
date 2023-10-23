# Lunar Terrain Understanding and Navigation 🌕🌖

🌕🚀 This project focuses on lunar terrain understanding and autonomous navigation for lunar rovers. Utilizing UNet with VGG16 architecture, we aim to facilitate better navigation by enhancing terrain comprehension.

## Overview

This project is centered on critical aspects of lunar exploration, emphasizing lunar terrain understanding and autonomous navigation for lunar rovers. While advanced lunar landscape generation may be incorporated later, our primary objective is to enhance terrain comprehension for better rover navigation.

## Dataset

📂 We leverage a dataset containing 9,766 realistic renders of lunar landscapes with segmented classes: sky, smaller rocks, and larger rocks. Bounding box data for larger rocks is also provided.

- Dataset source: [Artificial Lunar Landscape]([https://www.unb.ca/cic/datasets/nsl.html](https://www.kaggle.com/datasets/romainpessia/artificial-lunar-rocky-landscape-dataset])

## Models

🔍 We exclusively employ the following model for lunar terrain understanding:

1. **UNet with VGG16 Backbone**: Combining VGG16 for feature extraction and segmentation layers, it enhances terrain understanding for safer rover navigation.

   - **Model Description**: The UNet architecture is a convolutional neural network (CNN) designed for image segmentation tasks. In this project, we implement it using the VGG16 backbone as a pre-trained model for feature extraction, and additional layers for segmentation. This approach significantly enhances our ability to understand lunar terrains, which, in turn, aids in autonomous rover navigation.

## Setting Up

🚀 Follow these steps to set up and use the project:

1. **Clone the Repository**: Clone this repository to your local machine:

   ```bash
   gh repo clone Maatrika-P/Lunar-Terrain-Understanding-Autonomous-Navigation

2. **Install Dependencies**: Navigate to the project directory and install the required Python packages:
   
   ```bash
   pip install -r requirements.txt

3. **Explore Notebooks**: Open the Jupyter Notebooks provided in the repository to train and evaluate the UNet with VGG16 model for lunar terrain understanding and rover navigation.

4. **Data Preprocessing**: Follow the instructions in the notebooks to load and preprocess the dataset.

5. **Train the Model**: Execute the training sections in the notebooks to train the model on the lunar terrain dataset.

6. **Evaluation**: Evaluate the model's performance using the provided metrics in the notebooks.

7. **Testing**: Further, implement autonomous rover navigation testing if necessary.

8. **Documentation**: Modify the project documentation to suit your specific use case.

## Milestones

🎯 Key milestones for this project:

- Dataset Collection and Preprocessing
- Model Selection and Architecture Implementation
- Model Training and Performance Evaluation
- Autonomous Rover Navigation Testing
- Project Completion and Documentation

## Roadblocks

🚧 Potential roadblocks:

- Limited Hardware Resources
- Complex Model Training
- Real-world Rover Integration Challenges
- Data Anomalies and Noise

## Conclusion

📈 By utilizing the UNet with VGG16 model, we aim to enhance lunar terrain understanding, enabling autonomous rover navigation. This project contributes to safer and more efficient lunar missions with the potential for advanced landscape generation in the future.

## Acknowledgments

🙏 We acknowledge the creators and contributors to lunar datasets and machine learning libraries used in this project.

## Contribution

Contributions are welcome. Whether you want to suggest improvements, submit bug reports, or add new features, feel free to open an issue or create a pull request.

Join us in advancing lunar exploration technology with machine learning. 🌕🛰️🤖
