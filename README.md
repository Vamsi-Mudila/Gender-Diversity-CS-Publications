## <div align="center"> 📊Visualizing Historical Gender Diversity in Computer Science Publications📚 

<div align="center">
  <img src="https://github.com/user-attachments/assets/ca214610-8bac-45e7-8939-853dbd410030" alt="Banner" width="600" />

  <a href="https://github.com/user-attachments/files/17845485/Report.pdf" target="_blank"></a>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.11%2B-blue" alt="Python Badge" />
  <img src="https://img.shields.io/badge/Dash-Framework-orange" alt="Dash Badge" />
  <img src="https://img.shields.io/badge/License-MIT-success" alt="License Badge" />
  <img src="https://img.shields.io/badge/Contributions-Welcome-brightgreen" alt="Contributions Badge" />
  <a href="https://github.com/user-attachments/files/17845485/Report.pdf" target="_blank"><img src="https://img.shields.io/badge/Download%20Report-PDF-blue" alt="Download Report Badge" /></a>
</div> 



## 📌 Project Description
This project visualizes historical gender diversity trends in computer science publications using data from the DBLP API and Kaggle datasets. It provides insights through an exploratory analysis and an interactive web application built with Dash. 

By integrating both analysis and visualization in a single Jupyter Notebook, this project aims to facilitate user-friendly exploration of gender diversity trends over time.


---

## 🎥 Code & Output Preview
<div align="center">
  <img src="https://github.com/user-attachments/assets/0f15ed24-f59b-4192-9fbf-fffe817775e7" alt="Code Preview" width="500" />
  <img src="https://github.com/user-attachments/assets/0e82c170-9b47-46ef-af63-e67120125c64" alt="Plot Preview" width="500" />
  <img src="https://github.com/user-attachments/assets/d1d1c189-be29-4ef1-9c22-98fccbcbc76a" alt="Output Preview" width="500" />
</div>

---

## 🚀 Installation & Usage

### Prerequisites
- **Python 3.11** or later.
- An account on [Kaggle](https://www.kaggle.com/) to access API credentials (`kaggle.json`).

### Installation Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Vamsi-Mudila/Gender-Diversity-CS.git
   cd Gender-Diversity-CS
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r workspace/requirements.txt
   ```

3. **Set Up Kaggle API**:
   - Download `kaggle.json` from your Kaggle account.
   - Place it in one of these locations:
     - **Windows**: `C:\Users\<Your Username>\.kaggle\`
     - **macOS/Linux**: `~/.kaggle/`
   - Alternatively, specify the location in the notebook:
     ```python
     import os
     os.environ['KAGGLE_CONFIG_DIR'] = "workspace/"
     ```

4. **Run the Jupyter Notebook**:
   - Navigate to `workspace/` and open `Code.ipynb` in Jupyter Notebook or Jupyter Lab.
   - Execute all cells to:
     - Fetch the Kaggle dataset.
     - Perform exploratory data analysis.
     - Launch the Dash app directly from the notebook.

5. **Run the Dash Web App**:
   - The notebook includes a cell that runs the Dash application.
   - Once executed, open the provided URL (e.g., `http://127.0.0.1:8050/`) in your browser to interact with the app.

---

## 🚀 Run on Google Colab
You can also run this project on Google Colab without setting up anything locally. Follow these steps:

1. **Open the Project on Google Colab**:
   [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Vamsi-Mudila/Gender-Diversity-CS/blob/main/workspace/Code.ipynb)

2. **Upload `kaggle.json`**:
   - After opening the notebook in Colab, upload your `kaggle.json` file by clicking on the folder icon on the left panel, then the upload button.

3. **Set Kaggle API Path**:
   ```python
   import os
   os.environ['KAGGLE_CONFIG_DIR'] = "/content/"
   ```

4. **Run All Cells**:
   - Run all the cells in the notebook to fetch the dataset, perform the analysis, and visualize the results using the Dash app.

---

## 📊 Key Features
- **Gender Representation Trends**: Analyze gender diversity over time in computer science publications.
- **Interactive Visualizations**: Includes donut charts, line plots, and bar graphs for in-depth exploration.
- **User-Friendly Web App**: Run the integrated Dash app to interact with the data visually.
- **Kaggle API Integration**: Automatically fetches datasets for reproducibility.

---

## 🛠️ Project Structure
```
Gender-Diversity-CS/
│
├── README.md                  # Main project documentation
├── LICENSE                    # MIT License details
├── workspace/                 # Working files
│   ├── Code.ipynb             # Main Jupyter Notebook (analysis + Dash app)
│   ├── kaggle.json            # Kaggle API credentials (for your use only)
│   └── requirements.txt       # Python dependencies
```

---

## 🤝 Contributions
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add some AmazingFeature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open a pull request.

---

## ⚖️ License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## 💖 Acknowledgements
- **University of Liverpool**: For providing resources and guidance.
- **DBLP API**: For providing accessible publication data.
- **Kaggle**: For datasets and tools.
- **Supervisors**: Dr. Patrick Totzke and Dr. Meng Fang for their mentorship.
- **Friends and Family**: For their unwavering support and encouragement.
