# Hand Gesture Recognition Using CNN

This project aims to develop a system for hand gesture recognition utilizing Convolutional Neural Networks (CNNs), with a focus on the American Sign Language (ASL). The system can interpret hand gestures to understand and potentially translate them into text or commands, providing accessibility and communication assistance for individuals with hearing impairments or language barriers.

## Project Overview

The Hand Gesture Recognition System is designed to recognize and interpret hand gestures captured through image or video input. It employs a deep learning approach, specifically CNNs, to automatically learn and extract features from the input data for accurate classification.

## Key Features

1. **CNN Architecture**: Utilizes a CNN architecture for feature extraction and classification. CNNs are known for their effectiveness in image-related tasks due to their ability to capture spatial hierarchies of features.

2. **American Sign Language (ASL)**: The system is trained on a dataset comprising hand gestures representing ASL. This dataset includes various gestures corresponding to alphabets, numbers, and potentially common words or phrases.

3. **Data Preprocessing**: Implements preprocessing techniques such as normalization, resizing, and augmentation to enhance the robustness and generalization of the model.

4. **Model Training**: Trains the CNN model using labeled data to learn the patterns and representations associated with different hand gestures.

5. **Real-time Recognition**: Enables real-time recognition of hand gestures from live video feeds or static images.

6. **User Interface**: Provides a user-friendly interface for interaction, displaying recognized gestures and their corresponding interpretations.

## Usage

1. **Install Dependencies**: Make sure to install all required libraries and dependencies mentioned in the project documentation.

2. **Data Collection**: Run the provided script to collect images for training and testing purposes. The script captures images from a webcam feed and saves them according to the detected hand gesture.

3. **Training**: Train the CNN model using the collected training images. Preprocess the data if necessary and use appropriate training techniques to optimize the model's performance.

4. **Testing**: Evaluate the trained model using the testing images to assess its accuracy and generalization capabilities.

   - **Training Images**: Approximately 70,400 training images of ASL symbols.
   - **Testing Images**: Approximately 8,700 images for testing purposes.

5. **Integration**: Integrate the trained model into your application or system for real-world usage, ensuring proper input handling and interpretation of recognized gestures.

## Contributors

## Contributors

- [Riya Sahu]
- [Sejal Agrawal]
- [Suyash Khare]
- [Yashi Agarwal]

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use, modify, and distribute the code for both non-commercial and commercial purposes, with appropriate attribution.

## Contact

For any inquiries, suggestions, or feedback, please contact [Suyash Khare](mailto:suyashkhareji@gmail.com).

---

**Disclaimer**: This project is developed for educational and research purposes. While efforts have been made to ensure its accuracy and reliability, the developers do not guarantee its performance in all scenarios. 
