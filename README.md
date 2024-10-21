# 🌿 GO Green

Welcome to **GO Green**, a simple, innovative web application designed to provide smart agricultural recommendations based on soil type and climate conditions. This project was created in just a few minutes using the **Cosmocloud** no-code/low-code platform and leverages **MongoDB** for data storage (vector search) and **GEMINI API** for embeddings.

---

### 📜 Project Overview

**GO Green** provides customized recommendations for farmers by analyzing the soil and climate data. The recommendations are designed to help optimize crop yield, manage irrigation, and improve overall soil health. With the power of Cosmocloud, the app was built in a matter of minutes!

**Key Features:**
- 🌱 Accepts soil type and climate conditions as input.
- 🌍 Provides detailed recommendations for crops, irrigation, and soil management.
- 💻 Utilizes **MongoDB** for storing soil and climate data and retrieving dynamic recommendations.
- 🔍 Embeddings created through **Cosmocloud's GEMINI API**, a no-code tool to quickly generate smart recommendations.
- ⚡ Simple and intuitive **HTML-based web application** interface, easy to use and lightweight.

---

### 🏗️ Tech Stack

- **Frontend**: Simple HTML5, CSS3
- **Backend**: Powered by Cosmocloud (No-Code/Low-Code)
- **Database**: MongoDB for efficient data storage and retrieval
- **API**: GEMI API for creating and integrating embeddings
- **Platform**: Google IDX


### 🌐 Application Workflow

1. **User Input**: Enter the soil type and climate.
2. **MongoDB Integration**: The app fetches relevant data stored in the MongoDB database.
3. **Cosmocloud GEMI API**: The soil and climate embeddings are created via Cosmocloud's no-code/low-code platform, which generates a smart, data-driven recommendation.
4. **Dynamic Results**: The app displays a detailed recommendation based on your input.

---

### 📚 Dataset Example

```json
{
    "soil": "Alluvial",
    "climate": "Hot",
    "recommendation": "Ensure adequate water supply through efficient irrigation systems such as drip irrigation to prevent drought stress. Consider growing crops like sugarcane, wheat, and rice which thrive in alluvial soil."
}
```
To add the steps for GitHub usage to your **GO Green** project, you can follow these instructions in your `README.md`:

### 🚀 Steps to Use the App

1. **Clone the repository**  
   Clone the project to your local machine:
   ```bash
   git clone https://github.com/abinayasv/gogreen.git
   cd gogreen
   ```

2. **Install Dependencies**  
   Install any required dependencies if mentioned in the repository.

3. **Open the HTML file**  
   Open the `index.html` file in your browser:
   ```bash
   open index.html
   ```

4. **Use the Application**  
   Enter the soil type and climate, and the app will provide real-time agricultural recommendations.

5. **Modify & Contribute**  
   Feel free to fork the repository, make your changes, and submit pull requests to contribute.

   OUTPUT:

<HTML>
    <h1>INPUT</h1>
    <imgsrc="Screenshot 2024-10-21 212709.png"/>
    <h2>OUTPUT</h2>
    <imgsrc="Screenshot 2024-10-21 212728.png"/>
    

</html>
