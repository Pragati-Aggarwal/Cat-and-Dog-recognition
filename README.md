# Cat-and-Dog-recognition
🐱🐶 Cat vs Dog Image Classifier (Using CNN with TensorFlow)
This project builds a Convolutional Neural Network (CNN) to classify images as either cats or dogs using TensorFlow and Keras.

📁 Dataset
Directory: cat_dog/train contains cats/ and dogs/ subfolders.

Directory: cat_dog/test contains test images organized similarly.

🖼️ Image Visualization
Displays a sample of cat and dog images from the dataset using matplotlib.

🔁 Data Loading
Images are loaded and prepared using:

python
Copy
Edit
image_dataset_from_directory()
Image size: 200x200

Batch size: 32

Split: Manually separated into train/ and test/

🧠 Model Architecture
A Sequential CNN model with:

4 convolution + max pooling layers

Dense layers with Batch Normalization and Dropout for regularization

Output layer with sigmoid activation (for binary classification)

⚙️ Compilation & Training
Loss: binary_crossentropy

Optimizer: Adam

Metric: accuracy

Trained for 15 epochs on training and validation data

🔍 Prediction on External Image
Loads and preprocesses an external image (test_img2.jpeg)

Predicts whether it's a cat or dog

Displays result and image

✅ Output
Dog or Cat based on prediction.

