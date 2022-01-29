# Hardcoders
Github repository containing the submission for Cuvette Codoctober Hackathon 2021 by team Hardcoders

### Routes 


- `/user` Routes

#### Get `/user/signup` Signup Page Route
#### Get `/user/login` Login Page Route
#### Post `/user/signup` Signup a new user(POST)
#### Post `/user/login` Login an existing user(POST)
#### Get `user/logout` Logout a logged in user

- Other user Routes

#### Get `/user/tracks` Route to get all the tracks of the logged In user
#### Post `/user/tracks` Route to add a new track with milestones and each milstone contains resources
#### Get `/user/profile` Route to view the profile of the logged In user
#### Get `/user/public-profile/:name` Route to view the public profile of the user with unique name
#### Post `/user/profile` Route to Edit user profile details
#### Get `/user/notes` Route to get all the notes of the logged In user
#### Post `/user/notes` Route to add a new note

- `/forum` Routes

#### Get `/forum` Route to render forum/Discussion page

- Other forum Routes

#### Post `/forum/create` Post route to create a new discussion/question
#### Get `/forum/view/:id` Route to view a particular discussion thread
#### Post `/forum/answer/:id` Route to answer a particular question

