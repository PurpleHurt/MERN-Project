# MERN-Project Fitness Tracker
This is the seconde milestone project in the KSU FullStack Softward Development Bootcamp. This was a team project where we decided to build an app to track your fitness activities by logging the date, type of activity, and time spent on the activity.

## Deployment
https://milstone-project-frontend.herokuapp.com/

## Technologies
### Front End
 - React
### Back End
 - Node w/Express
 - MongoDB

### Users API
| Method | Path                                 | Purpose                                   |
| ------ | ------------------------------------ | ----------------------------------------- |
| POST   | /register                            | Register a user                           |
| POST   | /login                               | Login a user in                           |
| GET    | /profile                             | Show user's tracked activities            |              
| DELETE | /                                    | Delete user                               |
| PUT    | /update                              | Update user information                   |

### Activity API
| Method | Path                                 | Purpose                                   |
| ------ | ------------------------------------ | ----------------------------------------- |
| GET    | /exercise                            | Show user activities                      |
| POST   | /add                                 | Add a user activity                       |          
| DELETE | /delete/:id                          | Delete a user activity                    |