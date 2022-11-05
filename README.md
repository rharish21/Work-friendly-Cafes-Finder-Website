# Work-Friendly Cafes Finder

## Overview
Work-Friendly Cafes Finder is a web application built using Python and Flask that helps users discover cafes suitable for working. The project leverages SQLAlchemy for database management, REST APIs for data interaction, Jinja for templating, and Bootstrap for frontend styling.

## Features
- **Database Management:** Uses SQLite and SQLAlchemy to store and retrieve cafe details.
- **User-Friendly UI:** Built with Flask and Bootstrap5 for a responsive interface.
- **REST API Integration:** Allows interaction with the database through API endpoints.
- **Search Functionality:** Users can search for cafes based on specific criteria.
- **CRUD Operations:** Ability to add, update, and delete cafe details.

## Technologies Used
- **Python**
- **Flask**
- **SQLAlchemy**
- **Bootstrap5**
- **Jinja Templating**
- **SQLite**
- **REST APIs**

## Installation
### Prerequisites
Ensure you have Python installed. You can check by running:

```bash
python --version
```

### Steps
1. Clone the repository:

```bash
   git clone <repository-url>
   cd work-friendly-cafes-finder
```

2. Create a virtual environment:

```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. Install dependencies:

```bash
   pip install -r requirements.txt
```

4. Run the application:

```bash
   python main.py
```

5. Open a browser and go to `http://127.0.0.1:5000`

## Usage
- Run the application and browse available cafes.
- Use the search feature to filter cafes based on work-friendly amenities.
- Add new cafes by filling out the form.
- Edit or delete existing cafes as needed.

---