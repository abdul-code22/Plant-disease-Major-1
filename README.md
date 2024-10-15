#Potato Leaf Disease Classification using CNN


This project uses a Convolutional Neural Network (CNN) to classify potato leaf diseases, helping farmers identify Early Blight, Late Blight, and Healthy leaves.

--Features--

Deep Learning Model: Achieves 97% accuracy in classifying potato leaf diseases.

Real-time API: Built with FastAPI for quick predictions using image inputs.

Dataset: Based on the PlantVillage dataset, with augmented images to improve accuracy.

--Technologies Used--

Python

TensorFlow & Keras

FastAPI for API

Jupyter Notebook for model development

--How to Run--

Clone the repository.

Install dependencies: pip install -r requirements.txt

Start the API: uvicorn main:app --reload

Access the API documentation at http://localhost:8000/docs for image upload and classification.


--Results--
Training Accuracy: 98.59%
Testing Accuracy: 97.3%


License
This project is licensed under the MIT License.

