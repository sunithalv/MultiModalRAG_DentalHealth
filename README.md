# MultiModalRAG_DentalHealth

## Overview
This is a question answer engine that answers queries related to dental health of dogs and fetches information from FAISS database based on provided documents on the same. Using LangChain and OpenAI's vision and text model, alongside a Fast API web service, it provides answers complimented by images on the same for better understanding of the users.

![Screenshot 2024-06-16 203837](https://github.com/sunithalv/MultiModalRAG_DentalHealth/assets/28974154/4ae8782d-6019-415b-8b41-f7bce9e5e8c7)



## Getting Started

### Prerequisites
- Python 3.8 or later
- An OpenAI API key

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/sunithalv/MultiModalRAG_DentalHealth.git
  
2. **Set Up a Conda Environment (Recommended)**
* Create a new Conda environment:
   ```bash
   conda create -p venv python=3.10 -y
* Activate the environment:
   ```bash
   conda activate venv/

3. **Install Dependencies**
* Install the required packages using the `requirements.txt` file:
   ```bash
   pip install -r requirements.txt

4. **Set Up Your OpenAI API Key**
* Create a .env file in the root directory of the project.
* Add your OpenAI API key to the `.env` file:
   ```bash
   OPENAI_API_KEY='Your-OpenAI-API-Key-Here'

### Usage
To run the API, execute the following command:
   ```bash
   uvicorn app:app
```
The web app will be accessible at http://127.0.0.1:8000/


