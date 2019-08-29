# _Product_Review_

#### _Project for Week 16 at the coding school, Epicodus, written on August 29, 2019._

#### By _**Josh Mabry, Hugh Donkin, Tae Lee, and Alex Siegberg**_

## Description

_You've in the running for a freelance development job as the developer for Mario's Speciality Food Products (or another fictional company of your choosing). First, Mario wants to make sure you're the right person for the job. He's asked you for an MVP and wants it by 5:00 tonight. The stakes are higher than usual, since Mario's old site had thousands of unique visitors each day. If you can get the job, this is a great way to increase your profile as a developer. In particular, Mario is concerned about the information in his database being correct; your goal for today is to have the most comprehensive validations and callbacks to ensure information is properly saved and formatted in the database.

Database
The site should have functionality to review products so your database should include a one-to-many relationship between Products and Reviews. All products must have a name, cost and country_of_origin. All reviews should have an author, content_body and rating. (A rating can be a number between 1 and 5.) You can include other fields of your choosing as well._

## Setup/Installation Requirements

* _For demonstration only,_
* _locate this address (http://floating-scrubland-71604.herokuapp.com/) on your browser._\

* _For local deployment_
* _Clone this repository_
* _Open terminal and type 'git clone [git link]'_
* _Navigate to project directory using cd in terminal_
* _Open project in text editor (atom .)_
* _Type 'bundle install' in terminal to load Gems_
* _postgres DB installation with sql script in project_
* _rake db:create_
* _rake db:migrate_
* _rake db:seed_
* _rails s_
* _open browser and locate localhost:3000_
<br>
* _For database,
* _in order to backup, please execute followings in terminal,_
* _pg_dump [YOUR DATABASE NAME] > database_backup.sql_
* _for database restore after clone, please execute followings in terminal_
* _createdb [DATABASE NAME]_
* _psql [DATABASE_NAME] < database_backup.sql_
* _createdb -T [DATABASE NAME] [TEST DATABASE NAME]_

## Specs
| Behavior                                       | Input                                 | Output                                       |
| ---------------------------------------------- |:-------------------------------------:| --------------------------------------------:|
| DB schema design for one-to-many relationship  | create products table                 |                                              |

## Known Bugs
_No known bugs_

## Support and contact details

_Please contact us if you have any issues at: taebumlee@gmail.com_

## Technologies Used

* Ruby 2.5.1
* Rails 5.2.3
* Postgres DB 10.5
* JavaScript ES6
* Heroku 7.29
* Gems (turbolinks, jbuilder, dotenv-rails, rest-client, sass-rails, devise, money, alphavantagerb, faker ...)
* API information for real stock market from Alpha Vantage (https://www.alphavantage.co/)

### License
_This software is licensed under MIT license._

Copyright (c) 2019 **Josh Mabry, Hugh Donkin, Tae Lee, and Alex Siegberg**


# README
* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions
