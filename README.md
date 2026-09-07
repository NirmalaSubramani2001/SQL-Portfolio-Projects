# Employee Management System - MongoDB

## Project Objective

This project demonstrates basic MongoDB operations including:

- Insert Documents
- Find Documents
- Update Documents
- Delete Documents
- Aggregation Framework

## Technologies Used

- MongoDB
- MongoDB Shell
- VS Code
- GitHub

## Collection Structure

Employees Collection

{
  name: String,
  department: String,
  salary: Number,
  location: String
}

## Sample Operations

### View All Employees

db.employees.find()

### Filter Employees

db.employees.find({
  salary: {$gt: 45000}
})

### Update Employee

db.employees.updateOne()

### Delete Employee

db.employees.deleteOne()

### Aggregation

Average salary by department

db.employees.aggregate()

## Skills Demonstrated

- CRUD Operations
- Query Filtering
- Aggregation Framework
- MongoDB Data Modeling
