🌱 Crop & Fertilizer Recommendation System
📌 Description

A Machine Learning-based web application that recommends the best crop and suitable fertilizer based on soil and environmental conditions.

🛠️ Technologies Used
Python
Flask
Scikit-learn
HTML, CSS

📂 Project Structure
CROP-AND-FERTILISER/
│── app.py
│── crop_model.pkl
│── fertilizer_model.pkl
│── crop_encoder.pkl
│── fertilizer_encoder.pkl
│── Crop_recommendation.csv
│── Fertilizer.csv
│
├── templates/
├── static/


⚙️ How to Run
Install dependencies:
pip install flask scikit-learn pandas numpy
Run the project:
python app.py
Open in browser:
http://127.0.0.1:5000/
📊 Input Parameters
Nitrogen (N)
Phosphorus (P)
Potassium (K)
Temperature
Humidity
pH
Rainfall


🎯 Output
Recommended Crop
Suggested Fertilizer
