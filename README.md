## JUSTIN BISHOP - SHOPIFY BACKEND SOFTWARE ENGINEER ASSESSMENT
Project Goals

Make the tests pass for CRUD and search. ✔
Learn Ruby on Rails from scratch with this project! ✔

![me](me.png)
![example](example)
![testpass](tests)

# What I did:

Initialize Environment
How to run my version:
bundle install
rails db:migrate
rails db:seed
rails server

Project Initialization:
Created the Articles controller with an index action.
Ran rails generate model Article title:string content:text author:string date:date to create the Article model.
Executed rails db:migrate to apply migrations.
Added dummy data using the Rails console (rails c).
Added the view for listing articles.

Individual Article View:
Configured route article/:id to display an individual article.
Implemented the show action in the controller.

New Article Feature:
Created a new article view with validations in both the model and the form.
Utilized the _form.html.erb partial for shared functionality between new.html and show.html.

CRUD Features:
Added edit functionality with CRUD operations.
Integrated the delete function in the controller.
Modified the "See All" link to navigate back to the main page.

Search Feature:
Implemented a search bar for articles.

Testing:
Encountered errors on running rails test. Resolved by executing rails db:test:prepare.
Wrote additional tests for comprehensive coverage.
Passed all tests included in the application.

Final Steps:
Commented code for better readability.
Ran tests one last time.
Submitted a pull request.

References:
Used the official Rails Getting Started Guide for guidance.

## Conclusion:
Successfully completed and submitted the Shopify assessment, demonstrating proficiency in CRUD operations, testing, and project organization.

Thank you!
Justin Bishop
## justinb.developer@gmail.com
