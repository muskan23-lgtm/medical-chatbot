+20
Lines changed: 20 additions & 0 deletions


Original file line number	Original file line	Diff line number	Diff line change
@@ -0,0 +1,20 @@
# README: Setting Up Your Environment with Pipenv
## Prerequisite: Install Pipenv
Follow the official Pipenv installation guide to set up Pipenv on your system:  
[Install Pipenv Documentation](https://pipenv.pypa.io/en/latest/installation.html)
---
## Steps to Set Up the Environment
### Install Required Packages
Run the following commands in your terminal (assuming Pipenv is already installed):
```bash
pipenv install langchain langchain_community langchain_huggingface faiss-cpu pypdf
pipenv install huggingface_hub
pipenv install streamlit
