# Event CRUD

Over the course of the week, we will allow users to CRUD events:


Day 2:

Started from the bottom now we're back at the bottom...



Events have the following fields:

* Date (date)
* Location (string)
* Description (text)
* Capacity (integer)
* Requires ID (boolean)

To make this work:

* `cd ~/workspace`
* git clone this repo
* cd into the directory
* Run `bundle`
* Run `rake db:create`
* write a list (again) somewhere (notes, evernote, text file, etc.) of what will be required to allow a user to CRU events. Index/New/Create/Show/Edit. (What order do we need to do the things to make this work? Migrations, controllers, forms, routes, etc. Try to create this list before starting)

* As you finish each task, check off the item you've completed


 * Stories

* Create an events index page that lists all events in a table.
* Link to "New Event" that allows users to create events.
* From Events Index page link to all show pages for events.
* From Events Index page, link to "Delete", that deletes that event.
* Show page that shows all event details.
* Show Page also has Breadcrumb back to index(link to index)
* Edit Page that shows event details and allows user to make updates.
* Edit Page also has Breadcrumbs(links to show and index page)

* Don't worry about CSS or formatting.
* CRUD CRUD CRUD!!!

NOTE: no need to include Twitter Bootstrap here.
NOTE: gl hf
