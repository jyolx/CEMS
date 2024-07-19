# Campus Event Management

## Description

The project seeks to establish a centralized hub where students and staff of the Institute can access information regarding events like cultural festivities, academic seminars, sports competitions, and alumni gatherings taking place on campus. By consolidating event details into a single platform, the aim is to provide easier access to event information and a wider reach to the intended audience.Ultimately, the project endeavors to enhance the overall campus experience by facilitating greater participation, connectivity, and enjoyment among students, faculty, staff, and alumni.

The project is implemented using the Django framework and MySQL as the Database Management System. For the frontend, we have made use of HTML, CSS and Bootstrap.

## Table of Contents (Optional)

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)

## Installation

Make sure you have Python, MySQL and Django installed on your system.

Clone the repo
```bash
git clone https://github.com/jyolx/CEMS.git
```
Navigate to the src directory and install all required python packages
```bash
cd CEMS/src
pip install -r requirements.txt 
```

## Usage

Change the database password to your mysql root password in ![src/CEMS/settings.py under DATABASES["PASSWORD"]](https://github.com/jyolx/CEMS/blob/ebc783440e8107abdc214d9a26667c4a77e44826/src/CEMS/settings.py#L91)

Create CEMS database in MySQL 
~~~~sql
CREATE DATABASE CEMS;
USE CEMS;
~~~~

The required tables in MySQL have to be created through Django. Run

```bash
cd CEMS/src/
python manage.py migrate
```

Run Server

```bash
python manage.py runserver
```

Visit http://127.0.0.1:8000/ with your web browser to see the code in action!



To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative filepath, add it to your README using the following syntax:

    ```md
    ![Fresh view of Website HomePage](assets/images/website_blank.png)
    ```

## Credits

List your collaborators, if any, with links to their GitHub profiles.

If you used any third-party assets that require attribution, list the creators with links to their primary web presence in this section.

If you followed tutorials, include links to those here as well.

