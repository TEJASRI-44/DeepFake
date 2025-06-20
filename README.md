# Deepfake Detection Project
Deepfake Detection System is an AI-powered application that detects whether an image or video is real or fake. It uses a lightweight CNN model for image classification and a 3D CNN model for video-based deepfake detection. The project is built with a React frontend, Flask or Spring Boot backend, and integrates deep learning models to ensure reliable and fast inference. 
It provides a user-friendly interface for uploading media and visualizes prediction results effectively.

This repository contains the full source code for a Deepfake Detection system that uses deep learning models to classify images and videos as real or fake.

---

## 📂 Project Structure

- `frontend/` — React frontend user interface  
- `backend/` — Backend API (Flask or Spring Boot) serving the deepfake detection model  
- `backend/models_Saved/` — **Not included here due to large size**  
- `MODEL_DOWNLOAD_LINK.txt` — Contains a link to download the pre-trained model file

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/deepfake-detection-project-full.git
cd deepfake-detection-project-full
```

### 2. Download the Pre-trained Model

The model file is large and hosted on Google Drive. Please download it here:

[Download the model here](https://drive.google.com/file/d/1QwbC68_iLtF9IHJG27gFU_f8TGm65YiM/view?usp=sharing)

After downloading, place the model file at this location inside your local repo:

```
backend/models_Saved/lightweight_cnn_model_final.h5
```

If the `models_Saved` folder does not exist, create it inside the `backend` folder.

---

### 3. Setup Backend Environment

Create a Python virtual environment (recommended) and install dependencies:

```bash
cd backend

# Create virtual environment (optional but recommended)
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install Python packages
pip install -r requirements.txt
```

Run the backend server:

```bash
python app.py
```

---

### 4. Setup Frontend

Open a new terminal, navigate to the frontend folder, install dependencies, and start the React app:

```bash
cd frontend
npm install
npm start
```

Your frontend UI will be available at:

```
http://localhost:3000
```

---

## 🔧 Usage

- Use the web interface to upload images or videos.
- The backend will load the downloaded model to perform deepfake detection.
- Results will be displayed on the frontend.

---

## 📦 Important Notes

- The model file is too large to include directly in this repo, so download it separately.
- Make sure to place the model in the correct folder before starting the backend.
- Dependencies like `node_modules` and Python packages are managed locally and not tracked in Git.
- `.gitignore` excludes large or unnecessary files to keep the repo lightweight.

---

## 🤝 Contributions

Contributions, bug reports, and feature requests are welcome! Please open an issue or submit a pull request.


## 📄 License

This project is licensed under the MIT License.


## 📞 Contact

Bathini Venkata Tejasri — venkatatejasribathini@gmail.com  
Project link: https://github.com/TEJASRI-44/deepfake-detection-project-full
