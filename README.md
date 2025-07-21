# StudyBud

StudyBud is a community-based study room and messaging platform built with Django that helps students collaborate and discuss topics in real time. Users can create “rooms” around specific subjects or topics and post messages to start discussions. Designed for collaborative learning, StudyBud makes it easy for users to find study partners and engage in group conversations.

## Features

- **Room creation and management** – Authenticated users can create, update, and delete study rooms.
- **User authentication** – Login, signup, and logout functionalities via Django’s built-in auth.
- **Topic organization** – Rooms are categorized by topics (e.g. Python, Math, etc.).
- **Discussion threads** – Each room has a message board for interactive discussions.
- **Search and filtering** – Users can search rooms by topic names or keywords.
- **Message posting** – Users can post messages and delete their own messages.
- **User profiles** – Custom bios, profile images, etc.
- **Custom user model** – For extended user functionality beyond Django’s default.

## Tech Stack

| Category        | Technology               |
|----------------|--------------------------|
| **Language**    | Python                   |
| **Framework**   | Django                   |
| **Frontend**    | HTML, CSS, Bootstrap     |
| **Database**    | SQLite                   |
| **Version Control** | Git, GitHub         |
| **Environment** | Virtualenv               |

### Cloning the repository

--> Clone the repository using the command below :
```bash
git clone https://github.com/divanov11/StudyBud.git

```

--> Move into the directory where we have the project files : 
```bash
cd StudyBud

```

--> Create a virtual environment :
```bash
# Let's install virtualenv first
pip install virtualenv

# Then we create our virtual environment
virtualenv envname

```

--> Activate the virtual environment :
```bash
envname\scripts\activate

```

--> Install the requirements :
```bash
pip install -r requirements.txt

```

#

### Running the App

--> To run the App, we use :
```bash
python manage.py runserver

```

> ⚠ Then, the development server will be started at http://127.0.0.1:8000/

#

### App Preview :

<p align="center">
  Feed Home
</p>
<img src="">
</td> 
<td width="50%">
<br>
<p align="center">
  Room Conversation Preview
</p>
<img src="">  
</td>
</table>
