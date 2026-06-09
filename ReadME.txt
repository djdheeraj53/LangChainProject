1. Create virtual environment---
  conda create -p venv python=3.10

  activate---
  conda activate venv/
  conda activate /Users/adcb-dheerajkumar/Desktop/Git/LangChainProject/venv
  conda activate venv
  conda deactivate
  conda env list  
  conda remove -n langchain_env --all -y

  remove all dependencies
  pip freeze | xargs pip uninstall -y
  pip cache purge // clean pip cache

2. pip install -r requirements.txt

pypdf its use for pdf parsing
bs4=beautifulsoup4, its use to extract text from html files
arxiv its use to extract text from research papers
pymupdf its use to extract text from pdf files

Install dependencies
python -m pip install --upgrade pip
python -m pip install -r requirements.txt