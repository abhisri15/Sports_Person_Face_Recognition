# Sports Person Face Recognition
---
Welcome to the Celebrity Face Recognition WebApp project! This data science and machine learning project focuses on classifying sports personalities using facial recognition. The project involves several steps including data collection, preprocessing, feature extraction, model training, and deployment as a web application.

---

## Project Overview

In this project, we have chosen to classify five sports personalities:

1. Maria Sharapova
2. Serena Williams
3. Virat Kohli
4. Roger Federer
5. Lionel Messi
---

The key technologies and tools used in this project include:

- Python
- Numpy and OpenCV for data preprocessing
- Matplotlib & Seaborn for data visualization
- Sklearn for model building
- Jupyter Notebook, Visual Studio Code, and PyCharm as IDEs
- Python Flask for the backend HTTP server
- HTML, CSS, and JavaScript for the user interface
---

## Project Workflow

1. **Data Collection**: We collected images of the athletes from the internet.
2. **Data Preprocessing**: Detected and cropped faces in the images using OpenCV.
3. **Feature Extraction**: Utilized Wavelet transformation to extract key facial features.
4. **Model Building**: Explored various algorithms and selected SVM for its superior results.
5. **WebApp Development**: Created a Flask application to handle user inputs and provide classification results.
---

## Getting Started

To run the web application locally, follow these steps:

1. Clone this repository: `git clone https://github.com/your-username/celebrity-face-recognition.git`
2. Navigate to the project directory: `cd celebrity-face-recognition`
3. Install the required Python packages: `pip install -r requirements.txt`
4. Run the Flask application: `python app.py`
5. Open a web browser and go to `http://localhost:5000` to access the WebApp.
---

## Future Enhancements

- Improve model accuracy with more diverse training data.
- Expand the classification to include additional celebrities.
- Implement user authentication for personalized experiences.

Feel free to contribute to this project by opening issues or submitting pull requests!
