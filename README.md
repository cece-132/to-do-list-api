# README

## TLDR: What is this api doing?

Create an API for managing a to-do list. Users can create, read, update, and delete tasks. 
Implement features like task priorities, due dates, and marking tasks as completed.

#### Things I found helpful to know:

* Ruby version: ruby 2.7.2
* Rails version: Rails 5.2.8.1

##### How I built it
- My goal is to build an API that uses a PostgreSql database. Here are the steps I took to achieve that goal.

1. run `rails new <api_name> --api --database=postgresql` from CLI
1. cd into the new api `cd <api_name>`
1. Go to github, click on 'New Repository'. Once there you will need to type in the name of the repo you built from the CLI. *ONLY TYPE IN THE NAME DONT CLICK ON ANY OF THE OTHER OPTIONS* The reason is that GitHub will assume you are creating a repo in GitHub. Which in this case we have created a repo on our local computer that we are trying to add the remote repo too.
1. Click create repository.
1. You should be brought to a page that has the direction about how to connect the two from the command line. Now once there I prefer the SSH key, so that is the perscpective from which I will speak from. Go ahead and copy the SSH.
1. Return to the CLI
1. run `git remote add origin <paste in the SSH key>`
1. run `git branch -M main`
1. run `git add`
1. run `git commit -m 'Initial commit'`

Where are we?
At this point we have installed a rails api, with a postgresql database.

* System dependencies

* Configuration

* Database creation



* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
