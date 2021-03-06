### Project 3 - File storage 

Building a file storage app that allows user upload/view/edit/delete files 

- - - -

### Owners

- [J(Jehee) Choi](https://github.com/JeheeChoi)
- [Jasmine Edwards](https://github.com/jasmineked)
- [Nathan Gundy](https://github.com/gundyn)
- [Christopher Farish](https://github.com/orgs/CJNJC/people/CPF32)

- - - -
### Teamwork

- Get | Update : Jasmine & Nathan 
- Delete | Create : Chris & J
- Worked all together on back end before moving on to front end

- - - -

### Planning, process and problem-solving strategy

- Day 1: Wireframe, ERD, front end/backend init, and catalog of routes. AWS s3 bucket setup, backend model schema
- Day 2: MOB coding of backend API routes, front end create function
- Day 3: Pair coding of index and delete functions. Basic outline for styling of application
- Day 4: MOB coding for delete and update, as well as all unsolved issues in previous days work. deployed front and backend repos.

- - - -

### User Stories 
- As an unregistered user, I would like to sign up with email and password.
- As a registered user, I would like to sign in with email and password.
- As a signed in user, I would like to change password.
- As a signed in user, I would like to sign out.
- As a signed in user, I would like to upload a file to AWS.
- As a signed in user, I would like to update the meta-data of my file on AWS.
- As a signed in user, I would like to see the name of all files on AWS.
- As a signed in user, I would like to see the preview of all files on AWS.
- As a signed in user, I would like to delete the reference of my file from the database.
- As a signed in user, I would like to see the following meta-data for any file: date created/uploaded date modified/owner (user who uploaded the file)/tag

- - - -

### WireFrames 

- Nathan

![wireframe1](https://slack-imgs.com/?c=1&o1=ro&url=https%3A%2F%2Fi.imgur.com%2FG74T3poh.jpgttps://i.imgur.com/GNA3lxo.png)

- J

![wireframe2](https://i.imgur.com/pIEb9C5.png)

- Chris

![wireframe4](https://i.imgur.com/msGUx6W.jpg)

- Jasmine

![wireframe5](https://slack-imgs.com/?c=1&o1=ro&url=https%3A%2F%2Fi.imgur.com%2FvRMXl7j.jpg)

- - - -

### Important Links

- [Project Front End Repo](https://github.com/CJNJC/project3-react-client)
- [Project Back End Repo](https://github.com/CJNJC/project3-api)
- [Deployed API](https://safe-eyrie-19741.herokuapp.com/uploads)
- [Deployed Client](https://CJNJC/github.io/project3-react-client)

- - - -

### Technologies Used

- React
- JavaScript
- JSX
- CSS
- Express
- MongoDB
- Mongoose

- - - -


## File Storage API
| HTTP Method   | URL Path     | Result            |
|:--------------|:-------------|:------------------|
| GET           | /home       | index of uplods    |
| GET           | /uploads/`:id` | show single upload  |
| POST          | /uploads       | create upload       |
| PATCH         | /uploads/`:id` | update upload       |
| DELETE        | /uploads/`:id` | delete upload      |

- - - -

### Unsolved Problems 

- We'd like to make the application more user friendly and professionally styled
- We'd like to be able to categorize uploaded files by date uploaded, date updated, file type, owner, and tag
