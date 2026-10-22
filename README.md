# 🌱 AgroSmart – ML-Driven Crop Recommendation System

AgroSmart is a machine learning-based agricultural application designed to help farmers make informed farming decisions using soil and environmental data. The project uses trained machine learning models to support crop recommendation, fertilizer selection, and crop yield prediction.

## 📌 About the Project

Agriculture depends on several factors, including soil nutrients, temperature, humidity, pH, and rainfall. Choosing a suitable crop and fertilizer based on these conditions can be challenging for farmers.

**AgroSmart** aims to simplify this process by using machine learning models to analyze agricultural inputs and provide useful recommendations. The project demonstrates how machine learning can be applied to agriculture to support smarter and more sustainable farming practices.

## ✨ Key Features

- 🌾 **Crop Recommendation:** Recommends suitable crops based on agricultural input data using a trained Random Forest model.
- 📊 **Crop Yield Prediction:** Includes a Decision Tree model for estimating crop yield.
- 🧪 **Fertilizer Recommendation:** Uses a trained machine learning model to support fertilizer selection.
- 🌦️ **Weather Information:** Designed to support weather-based farming decisions through weather API integration.
- 📈 **Data-Driven Decisions:** Uses agricultural data and machine learning predictions to assist users.
- 🤖 **Machine Learning Integration:** Loads trained models to generate predictions from user inputs.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Machine Learning | Agricultural predictions and recommendations |
| Scikit-learn | Machine learning model development and prediction |
| Pickle (`.pkl`) | Storage of trained models and preprocessing objects |
| Flask | Web application framework, if configured in `app.py` |
| HTML, CSS, JavaScript | Potential frontend technologies, if implemented |

## 📂 Project Structure

```text
AgroSmart-Crop-Recommendation/
│
├── app.py                # Main Python application
├── crop_app.pkl          # Trained crop recommendation model
├── dtr.pkl               # Decision Tree regression model
├── fertilizer_app.pkl    # Trained fertilizer recommendation model
├── preprocesser.pkl      # Saved preprocessing object
└── README.md             # Project documentation
```

## ⚙️ How It Works

1. **Input Collection:** The application receives relevant agricultural data, such as soil nutrients and environmental conditions.
2. **Data Preprocessing:** Input data is prepared using the saved preprocessing object, where required.
3. **Model Prediction:** The trained machine learning models process the input data.
4. **Recommendations:** The application generates crop or fertilizer recommendations and yield estimates according to the implemented functionality.
5. **Decision Support:** Users can use the generated results to help plan agricultural activities.

## 🚀 Getting Started

### Prerequisites

Install the following before running the project:

- Python 3
- pip
- Git
- Visual Studio Code or another Python editor

### 1. Clone the Repository

```bash
git clone https://github.com/manishjadhav9529/AgroSmart-Crop-Recommendation.git
```

### 2. Navigate to the Project Directory

```bash
cd AgroSmart-Crop-Recommendation
```

### 3. Install Dependencies

Install the libraries required by your application. Common dependencies for this type of project include:

```bash
pip install flask numpy pandas scikit-learn
```

If `app.py` imports additional packages, install those too. Use compatible library versions for the saved `.pkl` models.

### 4. Run the Application

```bash
python app.py
```

Check the terminal output for the local server address. If the application uses Flask's default development server, it may be available at:

`http://127.0.0.1:5000/`

Open the displayed address in your web browser.

**Note:** The exact dependencies, startup command, and local URL depend on the implementation in `app.py`.

## 🎯 Project Objectives

- Apply machine learning techniques to agricultural problems.
- Recommend suitable crops using agricultural input data.
- Support fertilizer selection and crop yield estimation.
- Demonstrate the use of trained models in a Python application.
- Explore technology-driven approaches to sustainable agriculture.

## 🔮 Future Enhancements

- Integrate real-time weather information.
- Add multilingual support for farmers.
- Develop a responsive and accessible user interface.
- Provide graphical analysis of agricultural data.
- Add more crop and fertilizer datasets.
- Deploy the application to a cloud platform.

## 👨‍💻 Author

**Manish Ganesh Jadhav**

GitHub: [@manishjadhav9529](https://github.com/manishjadhav9529)

Project Repository: [AgroSmart-Crop-Recommendation](https://github.com/manishjadhav9529/AgroSmart-Crop-Recommendation)

---

## 📄 License

No license has been specified yet. Add an appropriate open-source license if you intend to permit others to reuse or modify this project.

⭐ If you find this project useful, consider giving the repository a star!
