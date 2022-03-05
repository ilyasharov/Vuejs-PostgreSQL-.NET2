#DB

create table Department(
    DepartmentId serial,
    DepartmentName varchar(500)
);

insert inro Department(DepartmentName) values('IT');
insert inro Department(DepartmentName) values('Support');

create table Employee(
    EmployeeId serial,
    EmployeeName varchar(500),
    Department varchar(500),
    DateOfJoining date,
    PhotoFileName varchar(500)
);

insert into Employee(EmployeeName, Department, DateOfJoining, PhotoFileName)
values ('Bob','IT','2021-06-21','anonymous.png');