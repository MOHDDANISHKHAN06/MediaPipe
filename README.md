# ASL Alphabet Gesture Recognition Project

This project integrates TensorFlow, MediaPipe, and MediaPipe Model Maker to develop a gesture recognition model capable of recognizing American Sign Language (ASL) alphabets from images. It showcases the application of machine learning and computer vision technologies to improve communication accessibility.

## Data Preparation

The dataset, `AnnotatedImages.zip`, comprises images representing ASL alphabets. Preparation involves:

- Uploading and unzipping `AnnotatedImages.zip` in the project environment.
- Organizing the dataset into folders, each representing a different alphabet letter with corresponding images.

## Model Training

The training process encompasses:

1. **Creating a Dataset**: Utilize `mediapipe_model_maker` to create a dataset object from the folder containing the annotated images.
2. **Splitting the Dataset**: Divide the dataset into training, testing, and validation sets.
3. **Choosing a Model Specification**: Select MobileNetV2 as the model specification along with suitable hyperparameters and training options.
4. **Training the Model**: Train the model using the training dataset, with validation data to monitor performance.
5. **Evaluating the Model**: Post training, evaluate the model's performance on the test set to determine its accuracy and loss.

## Model Exporting

Upon achieving satisfactory training results, the model is exported for future application in recognizing ASL alphabets from new images.

## Model Usage for Gesture Recognition

- Upload new images to assess the trained model's performance.
- For each uploaded image, the model predicts the corresponding ASL alphabet, displaying the prediction along with the confidence score.
- Employ MediaPipe to annotate the images with hand landmarks, highlighting the model's focal points for predictions.

## Implementation Details

- **MediaPipe's Hand Tracking**: Identifies hand gestures within images.
- **TensorFlow and MediaPipe Model Maker**: Trains a model to recognize ASL alphabets based on hand gestures.
- **Practical Application**: Demonstrates the use of machine learning and computer vision in creating applications that enhance communication for sign language users.

## Conclusion

This project underscores the potent synergy of machine learning and computer vision technologies in crafting practical gesture recognition applications. By focusing on ASL alphabet recognition, it emphasizes these technologies' potential to improve accessibility and support communication for the deaf and hard of hearing community.

## Results
![output](https://github.com/MOHDDANISHKHAN06/MediaPipe/assets/47732298/0a6bf9bf-9844-41a9-a744-901872b398d3)

