# online-chatroom

## Features of the Project

- **Study Room Interaction**: Users can create study rooms on different topics and interact with each other.
- **Templates**: Includes templates for home, room, user, activity component, feed component, topics component, delete, room form, and login/register.
- **Room Management**: Users can create, edit, and delete rooms.
- **Messaging**: Users can chat within rooms, and also edit and delete their messages.
- **Home Page**: Displays a list of topics, rooms, and recent activity, including a list of all recent chats.
- **Room Page**: Shows a list of chats for the specific room and a list of participants in that room.
- **User Authentication**: Users can login or register using the login/register form template.
- **User Page**: Displays a list of all topics, rooms created by the user, and the chats by the user in all rooms.

## Installation

The project uses Django for development. Follow these steps to install Django and set up the project:

### Steps to Install Django

1. **Install virtual environment**: Enter the following command in cmd:
    ```bash
    pip install virtualenv
    ```
2. **Set up Virtual Environment**: 
    1. Create a virtual environment by entering the command:
        ```bash
        virtualenv env_site
        ```
    2. Change directory to `env_site`:
        ```bash
        cd env_site
        ```
    3. Go to the `Scripts` directory inside `env_site` and activate the virtual environment:
        ```bash
        cd Scripts
        activate
        ```
3. **Install Django**: Install Django by entering the following command:
    ```bash
    pip install django
    ```
4. **Return to the `env_site` directory**:
    ```bash
    cd ..
    ```
5. **Start a new project**:
    ```bash
    django-admin startproject studyroom
    ```
6. **Change directory to `studyroom`**:
    ```bash
    cd studyroom
    ```
7. **Start the server**:
    ```bash
    python manage.py runserver
    ```
8. **Check if the server is running**: Go to a web browser and enter `http://127.0.0.1:8000/` as the URL.

### Steps to Execute the Project in Command Prompt

1. Change directory to `Documents`:
    ```bash
    cd Documents
    ```
2. Change directory to `studyroom`:
    ```bash
    cd studyroom
    ```
3. Install Django:
    ```bash
    pip install django
    ```
4. Run Django admin:
    ```bash
    django-admin
    ```
5. Activate the virtual environment:
    ```bash
    env\scripts\activate
    ```
6. Start the server:
    ```bash
    python manage.py runserver
    ```

### Steps to Execute the Project in Visual Studio Code

1. Activate the virtual environment:
    ```bash
    c:/Users/vanib/Documents/studyroom/env/Scripts/Activate.ps1
    ```

## Working of the Project Internally

- **URL Handling**: A URL file is created to manage all URLs. When a particular URL is requested, it is searched in the URL file, directed to the views file, and to the corresponding function mentioned in the URL.
- **Function Execution**: The function is then executed.
- **Context Dictionary**: Objects that need to be rendered in the template are passed in a context dictionary and returned at the end of the function, directing them to the appropriate template for rendering.

---

This `README.md` file provides a comprehensive overview of the project features, installation steps, and the internal working of the project. If you have any further questions or need additional assistance, feel free to ask!
