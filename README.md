# RAG Report Search Application - Datamaran
![Datamaran Logo](./app/rag-report-search/images/Datamaran_Logo_.jpg)
## Overview
The RAG Report Search application is designed to facilitate efficient search and retrieval of information from PDF reports. It leverages advanced AI models to index and query documents, providing users with accurate and comprehensive responses.
## Features
- **PDF Ingestion**: Load and index PDF documents for efficient searching.
- **AI-Powered Search**: Utilize AI models to retrieve and synthesize information from embedded documents.
- **Streamlit Interface**: User-friendly interface for uploading files and performing searches.
- **Docker Deployment**: Easily deploy the application using Docker.
## Quickstart Guide
### Prerequisites
- Python 3.10
- Docker
- OpenAI API Key
### Local Setup
1. **Clone the Repository**
   ```bash
   git clone git@bitbucket.org:datamaran/rag-report-search.git
   cd rag-report-search
   ```
2. **Install Dependencies**
   Use `uv` to install dependencies locally:
   ```bash
   uv sync
   ```
   Activate the virtual environment:
   ```bash
   source .venv/bin/activate
   ```
3. **Set Up Environment Variables**
   In the `.venv` directory created by `uv`, add your OpenAI API key to the `pyvenv.cfg` file:
   ```
   OPENAI_API_KEY=<your-key>
   ```
   Ensure your environment is configured to load variables from `pyvenv.cfg`.
4. **Add a "data" Directory**
   Create a "data" directory in the root directory and add a "pdf_reports" directory inside it with the PDF reports you want to search.
   Alternatively, you can use the application's upload feature to add files.
5. **Run the Application Locally**
   Start the Streamlit app by executing:
   ```bash
   streamlit run app/rag-report-search/src/streamlit_app.py
   ```
   Access the application at `http://localhost:8501`.
### Docker Deployment
1. **Build the Docker Image**
   From the root directory of the project, build the Docker image:
   ```bash
   docker build -t datamaran-rag .
   ```
2. **Run the Docker Container**
   Use the following command to run the application in a Docker container, ensuring you replace `<your-key>` with your actual OpenAI API key:
   ```bash
   docker run -it --rm \
     -v $(pwd)/app:/app \
     -w /app \
     -p 8501:8501 \
     -e OPENAI_API_KEY=<your-key> \
     datamaran-rag
   ```
   Access the application at `http://localhost:8501`.
## Usage
- **Upload PDF Files**: Use the application interface to upload PDF files for indexing.
- **Search and Retrieve Information**: Enter your search queries to retrieve information from the indexed documents.


--------------------------------------------------------------------------------------------


# Hello, I'm Angelo! 👋

I am a Machine Learning Engineer and Software developmer.

Reach me:

[![LinkedIn](https://img.shields.io/badge/-Connect-blue?style=flat&logo=LinkedIn)](https://www.linkedin.com/in/angelo-d-157381105/)
[![GitHub](https://img.shields.io/badge/-Follow-black?style=flat&logo=GitHub)](https://github.com/adgianv)

## 🚀 Favourite Programming Languages and Frameworks

<p align="center">
  <img src="https://raw.githubusercontent.com/rahul-jha98/github_readme_icons/main/language_and_tools/square/python/python.svg" alt="Python" height="50px"/>
  <img src="https://raw.githubusercontent.com/rahul-jha98/github_readme_icons/main/language_and_tools/square/c/c.svg" alt="C" height="50px"/>
  <img src="https://img.icons8.com/color/48/000000/mysql.png" alt="SQL" height="50px"/>
  <img src="https://img.icons8.com/color/48/000000/git.png" alt="Git" height="50px"/>
  <img src="https://raw.githubusercontent.com/rahul-jha98/github_readme_icons/main/language_and_tools/square/html/html.svg" alt="HTML" height="50px"/>
  <img src="https://raw.githubusercontent.com/rahul-jha98/github_readme_icons/main/language_and_tools/square/css/css.svg" alt="CSS" height="50px"/>
  <img src="https://raw.githubusercontent.com/rahul-jha98/github_readme_icons/main/language_and_tools/square/tensorflow/tensorflow.svg" alt="TensorFlow" height="50px"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg" alt="PyTorch" height="50px"/>
  <img src="https://raw.githubusercontent.com/rahul-jha98/github_readme_icons/main/language_and_tools/square/bash/bash.svg" alt="Bash" height="50px"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" alt="MongoDB" height="50px"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/neo4j/neo4j-original.svg" alt="Neo4j" height="50px"/>
</p>

## 🧠 Expertise

### 🤖 Machine Learning & AI
- **Machine Learning**: 📈 Developing ML models for various applications.
- **Deep Learning**: ⛓️ Solving problems building ANNs.
- **Natural Language Processing (NLP)**: 📝 Leveraging NLP models (LLMs, RNNs, LSTMs...) for sequential data analysis and embedding systems.
- **Image Analysis**: 🎇 Computer vision techniques to analyze image data (CNNs, ResNet, YOLO, U-Net, Object Location, Semantic Segmentation...).
- **Reinforcement Learning**: 🎮 Implementing RL algorithms for decision-making.
- **TensorFlow/PyTorch**: 🛠️ Building using TensorFlow and PyTorch.

### 🌐 Data Science & Analytics
- **Big Data Management**: 📊 Handling and analyzing large-scale datasets.
- **Data Engineering**: 🛠️ Designing and optimizing data pipelines.
- **Statistical Analysis**: 📈 Applying statistical methods to extract insights.
- **Advanced Mathematics**: 🧮 Solving problems with mathematical modeling.

### 🚀 Software Development
- **Programming Languages**: 💻 Proficient in Python, C, SQL, HTML, CSS, Bash.
- **Version Control**: 📜 Experienced with Git for version control.

## 🌟 Featured Projects
- [🤖 Computer Vision - Master Thesis: War through the Lens of AI. Detecting war images in Television News](https://github.com/adgianv/Thesis---War-Image-Classification)
- [🤖 Computer Vision - Object Detection model for tanks in war images using YOLO](https://github.com/adgianv/Object-Detection-Model)
- [🧠 Deep Learning and NLP - Transformer Architectures for Financial Sentiment Analysis (Python and Jupyter)](https://github.com/adgianv/NLP-Transformer_architectures-Financial_Sentiment_Analysis_Twitter)
- [🧠 Deep Learning - Health Conditions Prediction (Python and Jupyter)](https://github.com/adgianv/DeepLearning-MLP_Patients_Health_Predictions)
- [🔁 NLP - Job Resume Matching Algorithm (Python and Jupyter)](https://github.com/adgianv/NLP-Job_CV_Matcher)
- [🎮 2D Game (C)](https://github.com/adgianv/2D_Game-PacMan)

## 📫 Get in Touch

Let's connect and collaborate! Feel free to reach out:

- 📧 Email: a.digianvito@hotmail.it
- 🌐 LinkedIn: [Angelo di Gianvito](https://www.linkedin.com/in/angelo-d-157381105/)

Looking forward to exciting projects and opportunities!
