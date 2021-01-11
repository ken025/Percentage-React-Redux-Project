# Welcome to: PERCENTAGE
A web application, designed to give users the ability keep track of their expenses and their amount. Making it an ease to keep track of their spending. Users will also have access to a resource page to further their saving skills. 

- Users will be able to add accounts dedicated to each expense by providing:
  - Name
  - Balance

## Installation

  - Navigate to https://github.com/ken025/Percentage-React-Redux-Project.git
  - Provided there, are the folders to the Frontend and Backend which are also linked below 
  - Click the green **Code** button and copy the link by clicking on the **clipboard**
  - Once the repository is cloned: 
    - cd into the backend and run `bundle install` to load the gems and dependencies
    - When loaded, run `rake db:create` to create the database
    - Once that is done, run `rake db:migrate` to have access to the database
    - To have access to user and/or default posts, run `rake db:seed`
    - To access the web application run `rails s` 

  - Once that is done successfully:
    - cd into the frontend and enter `npm install` to download its dependencies
    - Run `npm start` to launch the application

## Repos

  [Backend](https://github.com/ken025/Percentage-Backend.git)

  [Frontend](https://github.com/ken025/Percentage-Frontend.git)

## Contributing

Bug reports and pull requests are welcomed.

## License
This code is free to use under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Future Plans for this Project
- Implement deposit and withdraw for each account
- Add a dynamic doughnut chart dependent on the account amounts
