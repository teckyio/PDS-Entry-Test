# Tecky's Professional Data Science(PDS) Entry Test

## Motivation
[This course](https://tecky.io/en/courses/PDS) is designed for students with intermediate programming level. It is assumed that students joining this course already know the basic of Python programming language which includes control structures, classes, objects and functions in Python. Students who doesn’t have any programming experience is recommended to join our [Introduction to AI and Programming](https://tecky.io/en/courses/IAP) to learn the necessary fundamental knowledge in programming..

## Requirement
You need to build a Restful API that has the following structure:

|API| Sample Input | Sample Output|
|---|---|---|
|GET /students |`{}` | `[{name:"Ann",year:1,averageGPA:2.7},{name:"Peter",year:4,averageGPA:3.4}]` |
|POST /students| `{name:'John',year:2}` | `{updated:1}`|
|PUT /students/:id| `{id:2,name:'Ben',year:1}` | `{updated:1}`|
|DELETE /students/:id| `{id:2}` | `{updated:1}` |

On your server side, you can use the following as your 
sample data. Therefore there is no need for database.
Also it is not necessary to maintain a json file as the file
storage.

```json
{
    "students":[
        {
            "id": 1,
            "name": "Ann",
            "year": 1,
            "averageGPA": 2.7
        },
        {
            "id": 2,
            "name": "Benn",
            "year": 2,
            "averageGPA" : 3.4
        },
        {
            "id": 3,
            "name": "Peter",
            "year": 4,
            "averageGPA" : 3.4
        }
    ]
}
```

A [Postman](https://www.getpostman.com/) file is also attached for clarification.

### Technology
The implemented should be done by Python. It does not matter
which framework you make use of.

### Submission
You can try to finish your python file on your local machine and submit it to us.
