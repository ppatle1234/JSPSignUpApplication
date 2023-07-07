# JSPSignUpApplication

CREATE DATABASE USE EmployeeDBMgnt

CREATE TABLE employee(empid INT,empname VARCHAR(255),empaddress VARCHAR(255),empsalary DOUBLE,
empemailid VARCHAR(255),empcontactnumber BIGINT,PRIMARY KEY(empid),UNIQUE KEY(empcontactnumber))

SELECT * FROM employee
