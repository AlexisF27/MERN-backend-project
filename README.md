# User Stories for techNotes

1. [ ] Replace current sticky note system
2. [ ] Add a public facing page with basic contact info 
3. [ ] Add an employee login to the notes app 
4. [ ] Provide a welcome page after login 
5. [ ] Provide easy navigation
6. [ ] Display current user and assigned role 
7. [ ] Provide a logout option 
8. [ ] Require users to login at least once per week
9. [ ] Provide a way to remove users access asap if needed 
10. [ ] Notes are assigned to specific employees 
11. [ ] Notes have a ticket #, title, note body, created & updated dates
12. [ ] Notes are either OPEN or COMPLETED 
13. [ ] Users can be Employees, Managers, or Admins 
14. [ ] Notes can only be deleted by Managers or Admins 
15. [ ] Anyone can create a note (when customer checks-in)
16. [ ] Employees can only view and edit their assigned notes  
17. [ ] Managers and Admins can view, edit, and delete all notes 
18. [ ] Only Managers and Admins can access User Settings 
19. [ ] Only Managers and Admins can create new users 
20. [ ] Desktop mode is most important but should be available in mobile 

### Run this project

- Clone this project
- Then run:
  
```shell
$ npm init
```
- Install some dependencies

***NOTE:*** 
- You can run all the dependencies in one line
  - Example: npm install bcrypt cooki-parser cors ..., etc.

```shell
$ npm install bcrypt
```
```shell
$ npm install cookie-parser
```
```shell
$ npm install cors
```
```shell
$ npm install date-fns
```
```shell
$ npm install dotenv
```
```shell
$ npm install express
```
```shell
$ npm install mongoose
```

- Auto generate identification in sequence

```shell
$ npm install mongoose-sequence
```
```shell
$ npm install uuid
```
```shell
$ npm install express-async-handler
```



- Install nodemon as dev dependecie
- Nodemon allows the server to rerun after saving code 

```shell
$ npm install nodemon --save-dev
```

- Replace "scripts" attribute so you can start nodemon with dev option

```package.json
"scripts": {
    "dev": "nodemon server",
    "start": "node server"
  },
```

- Run the backend project
  
```shell
$ npm run dev
```


