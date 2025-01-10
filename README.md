# Flask Task Master
Demo hosted on Heroku at: https://flasktaskmaster-9d9e9b2cd14f.herokuapp.com/
<br><br>

A lightweight task management web app designed to optimize productivity by providing task management tools, enabling users to create, track, update, and delete tasks in real time. This project uses Python, Flask, SQLite for database storage, HTML, CSS for the front-end, and is deployable on Heroku.
<br><br>

## Features
- **Task Management:** Users can create new tasks, view all tasks, update existing tasks, and delete tasks they no longer need.
- **Database Integration:** Task information is stored and managed using SQLite, providing a lightweight and efficient database solution.
- **Responsive Design:** The application uses HTML and CSS to create a simple, user-friendly interface.
- **Deployment Ready:** The application is designed to be deployable on Heroku for easy access and scalability.
<br>

## Prerequisites
- Python (https://www.python.org/downloads/)
- Flask (https://flask.palletsprojects.com/)
- SQLite (https://www.sqlite.org/)
- Heroku CLI (https://devcenter.heroku.com/articles/heroku-cli)
<br>

## Getting Started
1. Clone this repository to your local machine.
2. Set up your Python environment:
   - Install dependencies using `pip install -r requirements.txt`.
3. Initialize the database:
   - Open a Python/Flask shell and run:
     ```python
     from app import db
     db.create_all()
     ```
4. Run the application:
   - Execute the Flask server using `python app.py`.
5. Access the application at `http://127.0.0.1:5000/` to start managing your tasks.
<br>

## Contributing
Contributions to this project are welcome! Feel free to submit issues or pull requests.
<br><br>

## Contact
For questions or feedback, please contact me on [my profile](https://github.com/wangster6).
<br><br>

## Contributors
<a href="https://github.com/wangster6/raydsa/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=wangster6/raydsa" />
</a>
