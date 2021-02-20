# Welcome to: PERCENTAGE
A web application, designed to give users the ability keep track of their expenses and their amount. Making it an ease to keep track of their spending. Users will also have access to a resource page to further their saving skills. 

[Try it out!](http://percentage.surge.sh/)

- Users will be able to add accounts dedicated to each expense by providing:
  - Name
  - Balance

![](https://scontent.ftpa1-1.fna.fbcdn.net/v/t1.0-0/p640x640/152275653_1802011736635442_5658133406167728746_o.jpg?_nc_cat=109&ccb=3&_nc_sid=730e14&_nc_ohc=8phwmbdbAXkAX9Dlkn2&_nc_ht=scontent.ftpa1-1.fna&tp=6&oh=6fb2bfd4018ac6d28f98a875d12f83a9&oe=60577E4E)
![](https://scontent.ftpa1-2.fna.fbcdn.net/v/t1.0-0/p480x480/151971580_1802011783302104_69867252899651504_o.jpg?_nc_cat=102&ccb=3&_nc_sid=730e14&_nc_ohc=jaULCU32GFwAX_2o4i2&_nc_oc=AQnkDukrCcyh0R11XjLnLeNcitkWPRjb0UDw-3sa09V1irB3Y9eT7JF-9qOmRLo5Hy2SpdHlno7YP9VWxRnfF6eT&_nc_ht=scontent.ftpa1-2.fna&tp=6&oh=2c6f993bcd9a9bdd7f66de7d7d59a0c9&oe=60544353)
![](https://scontent.ftpa1-1.fna.fbcdn.net/v/t1.0-0/p600x600/151206218_1802011839968765_4770430761819707259_o.jpg?_nc_cat=108&ccb=3&_nc_sid=730e14&_nc_ohc=UWXus3-ZgLMAX8PHbFz&_nc_ht=scontent.ftpa1-1.fna&tp=6&oh=04a9200616b6ef5957ef12804fea18f8&oe=60541044)

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
