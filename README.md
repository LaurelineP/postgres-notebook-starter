# Jupyter Notebook Boilerplate for PostgreSQL
Interactively query your PostgreSQL database while taking notes with this notebook template.


https://github.com/user-attachments/assets/f40ce7b3-c4c9-4fe5-9905-099865fc8e6d



## 📋 Required Technologies
- **IDE**: VSCode
- **Database**: Postgres
- **Dependencies**
    - `python`: main programming language to use with Jupyter Notebook
    - `psycopg2`: library to connect to the Postgres driver

## 🚀 Quick Start
1. Fork this repository on GitHub (click the **Fork** button at the top-right).  
2. Clone your fork locally:
```sh
    git clone git@github.com:<your-username>/postgres-notebook-starter.git
```
- Copy the file `.example.sample` and rename it as `.env`
```sh
   cp .example.sample .env
```
3. Update the `.env` file with your database information
4. Create a virtual environment (e.g.: `venv`) with your Python version
5. Install the dependencies requirements
```sh
    pip install -r requirements.txt
```
You are now all set to interact with the notebook!
Everything else are detailed in the notebook.

## 💡 Use Cases
- Explore and analyze your PostgreSQL database interactively.
- Learn SQL by running queries and seeing immediate results.
- Take notes and document insights directly alongside query results.
and more..
Use as a boilerplate for future projects that require database exploration \
and experimentation.

## 🧹 Cleanup
If you cloned this repository directly instead of forking, \
you may want to remove the original remote to avoid accidentally pushing:

```sh
    git remote remove origin
```
