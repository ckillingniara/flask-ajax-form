## Generate a dynamic form in Flask with AJAX

### Functionality

User selects a *department* from a drop down list. Once selected, an AJAX request is sent with the *department_id* to the server-side to grab the appropriate *employee* and *employee_id* based on the *department_id*. The JSON data response sent back contains the *employee* that populates a second drop down list.

### Install

1. Clone repo
1. Activate vitrualenv
1. Install requirements

### Run JSON

1. JSON example: `python json-example/app.py`

### Run SQL

1. Create database: `python sql-example/db_init.py`
1. SQL example: `python sql-example/app.py`

