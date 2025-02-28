# Zim Student Program Recommendation System

## Overview

The Zim Student Program Recommendation System is designed to help students determine suitable academic programs based on their O-Level and A-Level results. This system will use a dataset of subjects and student results to project the most relevant programs for each student.

## Project Goals

- Create a dataset of O-Level subjects and A-Level subjects.
- Generate a fake dataset of student results for both O-Level and A-Level.
- Develop a program recommendation model that maps student results to suitable academic programs.
- Provide a user-friendly web-based interface for students to input their results and receive program recommendations.

## Features

- O-Level and A-Level Subject Dataset: A structured list of available subjects in Zimbabwe’s education system.
- Student Results Dataset: Simulated student results to test and train the recommendation system.
- Program Mapping: A logic-based approach to match student results with potential study programs.

## Web Application: A simple interface for students to get program recommendations.

### Dataset Structure

#### O-Level Subjects Dataset (Example Format)

| Attempt | #1    | #2    |
| :---:   | :---: | :---: |
| Seconds | 301   | 283   |

Subject Code  Subject Name
4001          Mathematics
4002          English Language
4003          Physics
4004          Chemistry

#### A-Level Subjects Dataset (Example Format)

Subject Code  Subject Name
5001          Mathematics
5002          Physics
5003          Chemistry
5004          Biology

#### Fake Student Results Dataset (Example Format)

Student ID   O-Level Grades    A-Level Grades
001          A, B, C, A, B     A, B, A
002          B, C, C, A, A     B, B, C
003          A, A, B, B, A     A, A, A

## Program Recommendation Logic
The recommendation system will work by analyzing:
- The combination of subjects taken at O-Level and A-Level.
- The grades attained in key subjects.
- The minimum entry requirements for various programs at universities and colleges in Zimbabwe.
- Matching students with programs they are eligible for.

## Example Program Mapping

Subjects Taken                       Recommended Programs
Maths, Physics, Chemistry            Engineering, Computer Science, Medicine
Maths, Geography, Business Studies   Economics, Accounting, Business Administration
Biology, Chemistry, Physics          Medicine, Pharmacy, Biomedical Science

## Technology Stack

Python for data processing and analysis
- Pandas & NumPy for data manipulation
- Django/Flask for web development
- SQLite/MySQL for storing student and program data
- Machine Learning Models (optional) for advanced recommendations

## Getting Started

Clone the repository:

git clone https://github.com/yourusername/zim-student-program-recommendation-system.git
cd zim-student-program-recommendation-system

Install dependencies:

pip install -r requirements.txt

Run the application:

python manage.py runserver  # If using Django

Access the system at http://127.0.0.1:8000/

## Future Enhancements

- Integrate real student data for more accurate recommendations.
- Implement machine learning to improve recommendation accuracy.
- Expand the system to include college/university admission requirements.
- Add career guidance features to suggest potential career paths.

## Contributing

Contributions are welcome! If you want to improve the system, submit a pull request or open an issue.

## License

This project is licensed under the MIT License.

## Contact

If you have any questions, please contact Patrick Zvenyika at patrickzvenyika@gmail.com or visit LinkedIn.
