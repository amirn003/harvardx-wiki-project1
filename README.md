# Wiki Django (HarvardX)

## Overview

This project is a part of the HarvardX course. It is a simple wiki application that allows users to create, edit, and view pages. The project is built using Python and Django.
It is available here: https://amirnaar.pythonanywhere.com/wiki/

## Features

- Create new wiki pages
- Edit existing wiki pages
- View a list of all wiki pages
- Search for wiki pages by title
- Markdown support for page content

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/harvardx-wiki-project1.git
    cd harvardx-wiki-project1
    ```

2. Create a virtual environment and activate it:

    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Apply migrations:

    ```bash
    python manage.py migrate
    ```

5. Run the development server:

    ```bash
    python manage.py runserver
    ```

6. Open your browser and navigate to `http://127.0.0.1:8000` to view the application.

## Usage

- To create a new page, click on the "Create New Page" link in the navigation bar.
- To edit an existing page, navigate to the page and click on the "Edit" button.
- To view a list of all pages, click on the "All Pages" link in the navigation bar.
- To search for a page, use the search bar in the navigation bar.
