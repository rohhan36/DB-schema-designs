# DB-schema-designs
Some database schema design made by me as per the given requirements. I made these with lucid charts. 

1) [Netflix DB schema](https://raw.githubusercontent.com/rohhan36/DB-schema-designs/07a5e816c0184948f6f24139a14e2d16f256be66/Netflix.svg)

**Requirements**
  -Netflix has users
  
  -Every user has an email and a password
  -Users can create profiles to have separate independent environments.
  -Each profile has a name and a type. Type can be KID or ADULT.
  -There are multiple videos on Netflix.
  -For each video, there will be a title, description and a cast.
  -A cast is a list of actors who were a part of the video. For each actor, we need to know their name and list of videos they were a part of.
  -For every video, for any profile who watched that video, we need to know the status (COMPLETED/ IN PROGRESS).
  -For every profile for whom a video is in progress, we want to know their last watch timestamp.
  
2) [Movies](https://raw.githubusercontent.com/rohhan36/DB-schema-designs/07a5e816c0184948f6f24139a14e2d16f256be66/movies_schema_design.svg)

**Requirements**
  -Design a movies database. Each movie has a title and year, one (and only one) director, and some number of actors.
  -Actors can star in multiple movies.
  -Directors can direct multiple movies.
  -Some movies have the same title such as Ocean’s Eleven (the 2001 version directed by Steven Sodenbergh had George Clooney, Brad Pitt, Matt Damon, Julia Roberts, and many others,
    but the 1960 version was directed by Lewis Milestone and starred Frank Sinatra, Dean Martin and Sammy Davis Jr).
  -The schema should be normalized enough to avoid duplicating strings too much, and also to be able to efficiently answer questions like these two:
    1. Who acted in Fight Club (1999)?
    2. What are the 10 most recent movies that George Clooney starred in?
    
3) [Online Teaching Platform](https://raw.githubusercontent.com/rohhan36/DB-schema-designs/07a5e816c0184948f6f24139a14e2d16f256be66/online_learning_platform.svg)

**Requirements**
  -Students can register for different batches (Ex: Feb’20)
  -Students attend daily lectures on various topics (like, Trees, Linked lists, stacks etc.)
  -Every lecture has an assignment and homework.
  -Every assignment and homework can have 0-10 problems.
  -Every class has an instructor, some prelecture content and lecture notes.
  -Students should be able to see the class timeline, problem solve percentage, attendance percentage and status of all the problems in all the assignments/homework in the dashboard.
  -Instructors should be able to see a list of classes taken by him and his upcoming class.
  -Instructors should be able to create lessons for all the batches and should be able to add and modify the assignments and homework problems.

Future Scope:
  -Store ratings and feedback or the class.
  -Collaborative lectures taken by multiple instructors.
  -Daily Streak calculation.    
  
