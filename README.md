# 🌱 CropMaster - Smart Crop Recommendation System 🌱

CropMaster is an intelligent web application that helps farmers and agricultural enthusiasts make informed decisions about which crops to grow based on various environmental and soil parameters. Using machine learning algorithms, the system analyzes input parameters and provides personalized crop recommendations.

## 📸 Screenshots

### Login Page
![login](https://github.com/user-attachments/assets/484be416-e729-4677-855e-bf148e102bc0)

### Home Page
![home](https://github.com/user-attachments/assets/e71d7b42-e43e-4866-a382-b588b67ae79f)

### Prediction Interface
![prediction](https://github.com/user-attachments/assets/722e2a72-48f2-4b85-b77f-a14289c22b9d)

### Sample Prediction Result
![predicted result](https://github.com/user-attachments/assets/a2ceb2e7-7582-446c-9086-da9ed8a3d8aa)

## 🚀 Features

- **User Authentication**: Secure login system for personalized experience
- **Smart Recommendations**: ML-powered crop suggestions based on multiple parameters
- **Real-time Analysis**: Instant results based on input parameters
- **User-friendly Interface**: Clean and intuitive design for easy navigation
- **Comprehensive Parameters**: Takes into account various factors affecting crop growth

## 📊 Input Parameters

The system considers the following parameters for crop recommendation:

1. **Nitrogen (N)** content in soil (range: 0-140)
2. **Phosphorus (P)** content in soil (range: 5-145)
3. **Potassium (K)** content in soil (range: 5-205)
4. **Temperature** (°C) (range: 8-44)
5. **Humidity** (%) (range: 14-100)
6. **pH** value of soil (range: 3.5-10)
7. **Rainfall** (mm) (range: 20-300)

## 🛠️ Technology Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python Flask
- **Machine Learning**: Random Forest Algorithm
- **Data Processing**: Pandas, NumPy
- **Model Training**: Scikit-learn

## 📋 Prerequisites

- Python 3.x
- Flask
- scikit-learn
- pandas
- numpy
- pickle

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/Vishwanath456/CropMaster.git
cd cropmaster
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
python app/app.py
```

## 👥 Usage

1. Access the application through your web browser at `http://localhost:5000`
2. Log in using the provided credentials
3. Enter the soil and environmental parameters
4. Get instant crop recommendations

## 🔐 Login Credentials

- Username: `admin`, Password: `123`


## 📝 Sample Inputs

### For Rice:
```
Nitrogen: 90
Phosphorus: 42
Potassium: 43
Temperature: 20.87
Humidity: 82.00
pH: 6.50
Rainfall: 202.93
```

### For Maize:
```
Nitrogen: 71
Phosphorus: 54
Potassium: 16
Temperature: 22.61
Humidity: 63.69
pH: 5.74
Rainfall: 87.75
```
