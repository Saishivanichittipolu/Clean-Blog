# Flask Blog with Bootstrap Theme

Welcome to my Flask-based blog project! This project allows you to create and manage blog posts using Flask, SQLAlchemy, and a Bootstrap theme. Users can add, edit, and delete posts with ease.

## Table of Contents
- [Project Structure](#project-structure)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
  

## Project Structure
The project structure is as follows:
- `app.py`: Main Flask application file.
- `templates/`: HTML templates for different views.
- `static/`: Static assets such as CSS, images, etc.
- `forms.py`: Flask-WTF forms for post creation and editing.
- `models.py`: SQLAlchemy model for the blog post.
- `README.md`: Project documentation.

## Setup
1. Clone the repository:

```bash
git clone https://github.com/Saishivanichittipolu/clean-blog.git
cd your-repo 
 ```
2. **Set up a virtual environment:**

    ```bash
    python -m venv .venv
    source .venv/bin/activate  # On Windows, use .venv\Scripts\activate
    ```
3. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Set environment variables:**

    ```bash
    export FLASK_APP=app.py
    export FLASK_ENV=development
    export SECRET_KEY='your_secret_key'
    export DB_URI='sqlite:///posts.db'  # Change this for production
    ```

5. **Initialize the database:**

   ```bash
    flask db upgrade
    ```
## Usage<br>
Run the Flask application:
```bash
flask run
```
Access the application at https://clean-blogx.onrender.com/.
Explore different views, create, edit, and delete blog posts.

## Contributing<br>
If you'd like to contribute to this project, please follow these steps:<br>

1.Fork the repository.<br>

2.Create a new branch:<br>
```bash
git checkout -b feature/your-feature
```
3.Make your changes and commit them:<br>
```bash
git add .
git commit -m "Add your feature"
```
4.Push the changes to your fork:<br>
```bash
 git push origin feature/your-feature.
```

