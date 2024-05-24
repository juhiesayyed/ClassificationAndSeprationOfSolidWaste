
# Efficient Image Classification System for Solid Waste Management

## Overview
The escalating global issue of solid waste management poses severe environmental and health risks, exacerbated by the rapidly increasing volume of waste generated worldwide. Improper disposal and inadequate segregation of waste materials contribute significantly to pollution, resource depletion, and ecological degradation.

This project aims to develop an efficient image classification system for solid waste management, addressing the critical challenge of accurately categorizing waste into organic and inorganic components, and further classifying inorganic waste into nine distinct classes, including aluminium, glass, paper, wood, textiles, and plastic.

## Features
- **Accurate Waste Categorization**: Classifies waste into organic and inorganic components.
- **Detailed Inorganic Classification**: Further classifies inorganic waste into aluminium, glass, paper, wood, textiles, and plastic.
- **Advanced Deep Learning Models**: Utilizes ResNet and VGG architectures for high classification accuracy.
- **User-Friendly Interface**: Allows users to easily upload or capture images for waste classification.

## Methodology
The methodology involves leveraging the power of deep learning algorithms, specifically the ResNet and VGG architectures, which are widely acclaimed for their exceptional performance in computer vision tasks. The approach employed a comprehensive evaluation of four state-of-the-art models:
- ResNet152
- ResNet50
- VGG16
- VGG19

These models were rigorously trained and evaluated using a diverse dataset of waste images. The key findings revealed that the VGG19 model outperformed the others, achieving the highest classification accuracy, closely followed by the ResNet152 model. Consequently, these two models were selected for integration into the final waste classification system.


## Installation
To run this project locally, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/solid-waste-classification.git
   cd solid-waste-classification
   ```

2. **Install Dependencies**
   Ensure you have Python installed. Then install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download Pre-trained Models**
   Download the pre-trained VGG19 and ResNet152 models and place them in the `models` directory.

## Usage
1. **Run the Application**
   ```bash
   python app.py
   ```

2. **Using the Interface**
   - Upload or capture an image of the waste.
   - Select the classification model (VGG19 or ResNet152).
   - Click "Classify" to see the results.

## Dataset
The dataset used for training and evaluation includes diverse images of waste materials which I have added to this repository

## Results
The VGG19 model achieved the highest classification accuracy, closely followed by the ResNet152 model. These models provide reliable and efficient classification of waste materials, facilitating better waste management practices.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## Keywords
Waste classification, ResNet, VGG, Image classification, Deep learning, Organic waste, Inorganic waste.

## Contact
For any questions or inquiries, please contact [your-email@example.com](mailto:juhiesayyed44@gmail.com).
