
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

## Repository Structure

- `models/`: Contains the pre-trained ResNet50, ResNet152, VGG16 and VGG19 models.
- `app.py`: The Python file for the Flask web application.
- `templates/`: Directory containing HTML templates for the web interface.
- `static/`: Directory for static files (images).
- `requirements.txt`: List of required Python packages and dependencies.
- `README.md`: This file, providing an overview of the project and instructions.

## Getting Started

1. Clone the repository: `git clone https://github.com/your-username/solid-waste-classification.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the Flask application: `python app.py`
4. Access the web interface by navigating to `http://localhost:5000` in your web browser.

## Usage

1. Visit the web application in your browser.
2. Choose either the "Upload Image" or "Capture Image" option to provide an image of waste.
3. The system will process the image through the ResNet152 or VGG19 model and display the predicted waste category.
4. Additional information about the classified waste material, including its environmental impact and recommended disposal or recycling methods, will be provided.


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

## Contributors
1. Juhie Sayyed
2. Ajay Kumar
3. Vedant Khergade
4. Rahul Baser
