# University API
## Description
This API returns students from the university database. Use it to either return all students or a single student using the ID of the student.

## How to install
### Clone this repo
`git clone https://github.com/shanereddy/week1-university-api.git`

### Install the requirements
`python -m pip install -r requirements.txt`

## How to run
`uvicorn main:app --reload`

## Test URLs
### Main endpoint (root)
`http://127.0.0.1:8000/`

### All students
`http://127.0.0.1:8000/students`

### Student by Id
`http://127.0.0.1:8000/students/s2`

### Student Not Found
`http://127.0.0.1:8000/students/s99`