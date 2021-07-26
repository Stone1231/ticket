# Ticket

## Get source code
git clone https://github.com/Stone1231/ticket.git  
git submodule init  
git submodule update  
git submodule status

## Backend
### ticket-be：ASP.NET(.NET5) MVC
- Step1 DB init  
  dotnet ef migrations add init
  
  dotnet ef database update

- Step2 run backend

  dotnet run

- Step3 create test data

  curl http://localhost:8000/api/init/all

## Frontend
### ticket-fe：React

- Step1 run frontend
  
  npm install

  npm start

- Step2 please login user/password:

  admin / pwd

  pm / pwd

  rd / pwd

  qa /pwd

## ER Model
![GitHub Logo](/ER.png)
