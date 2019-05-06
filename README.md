# HRRS-OOP

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
This project is simple hotel room reservation web application.
	
## Technologies
Project is created with:
* Java: 1.8
* Bootstrap: 4
* MySQL

	
## Setup
To run this project, install it locally and run on a prefferd local server:


First of all you need to config your database attributes.
I have manage those config in a seperate file called Helper.java (src/utils/Helper.java)
In there you can mention your configurations.

![Annotation 2019-05-06 090741](https://user-images.githubusercontent.com/38374168/57205923-a2216b00-6fdf-11e9-8eb6-9bf73927551d.jpg)

Next you need to migrate database => 
http://localhost:8080/MRRS-OOP/reservation_controller?command=DB_MIGRATE 
you need to give this URL and it will automatically do the migration for you and redirect to the homepage.

![Annotation 2019-05-06 090817](https://user-images.githubusercontent.com/38374168/57205984-fc223080-6fdf-11e9-994d-e6926497a919.jpg)

![Annotation 2019-05-06 090642](https://user-images.githubusercontent.com/38374168/57205994-165c0e80-6fe0-11e9-8210-4d30413bac7e.jpg)

Finally you have to add some data to rooms table.


Yes you're done ! Happy hacking <3
