1)  Pumpkin Classifier
This is a machine learning web application that classifies images of pumpkins. It includes a trained model and a simple web interface built using Python (Flask). The app allows users to upload images and receive classification results instantly.

2)Project Structure

Pumpkin Classifier/
│
├── router/                      # Handles routing logic

├── scripts/                     # Contains ML scripts and model logic

├── static/                      # Static files (CSS, JS, images)

├── templates/                   # HTML templates (Jinja2)

├── venv/                        # Virtual environment (not pushed to Git)

├── app.py                       # Main Flask application

│
├── Screenshots/                # Project screenshots


├── Demo_Video/                 # Demo video folder
│   └── PC Recording.mp4
│

├── Pumpkin Classifier Documentation.pdf  # Detailed project documentation

└── README.md                   # Project overview (you’re reading this)

 
** Features **
Upload an image of a pumpkin and classify it using a trained ML model.

Flask-based web application.

Lightweight and easy to deploy.

Responsive UI using HTML/CSS.

⚙️ Technologies Used
Python

Flask

HTML/CSS (Jinja2 templating)

TensorFlow/Keras or PyTorch (based on your script)

OpenCV/Pillow (for image processing)

🖥️ How to Run
Clone the repo:


git clone https://github.com/Shahrukh4034/Pumpkin_Classifier.git
cd pumpkin-classifier
Set up a virtual environment:


python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the application:


python app.py
Open your browser and go to: http://localhost:5000

📸 Screenshots
See the Screenshots/ folder for example inputs and results.

🎥 Demo
A demo video is available in the Demo_Video/ folder.

📄 Documentation
For more details, refer to Pumpkin Classifier Documentation.pdf.


Demo Video Link
https://drive.google.com/file/d/1PWAPHLeDY3FjpIhYs4T4MXAPQ_kt27Vj/view?usp=drivesdk
