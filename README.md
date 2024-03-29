## Mike Gontareks HomePage

The purpose of the homepage is to display my Computer Science capstone project.  Later this will be used to display some of the projects that I work on and develop down the road. 

## *Professional Self-Assessment*

I started my pursuit of my Bachelor's Degree in Computer Science in September of 2018.  It has taken me four years as I have been busy with my wife and now two little girls (4 and 1).  During my time working on my degree I have learned about many IDEs, languages, hardware, software, and applications that make Software engineering possible. I have learned how to securely write safe code that used security policies to ensure that I fix bugs, and protect from vulnerabilities.  The Computer Science program with the Software Engineering emphasis has exposed me to a lot of great tools and given me a good foundation to stand on.  Now I am looking forward to landing my first job and hitting the ground running. 
	I have two artifacts that I used to highlight the skills I have gained throughout my degree.  
	
First, I used my Java project which has a contact class with parameters for the contact information that was tested with JUnit.  I enhanced this project by adding a console log that allowed the user to run the application and enter a choice for what they would like the application to do.  Then the application would perform that function.  I made it so the user could add data and then display that data. 	 
   
Second, I used the SQL tables created in my DAD 220 class. I  enhanced them so they would reflect statistics about Minnesota Wild players on one table and the other table, I put their hometown information. 

These artifacts are described in more detail at the bottom of this page under the Artifacts header.

Five Course Outcomes 
1. Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision-making in the field of computer science
2. Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts
3. Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices (data structures and algorithms)
4. Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals (software engineering/design/database)
5.  Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources
	
   The skills used in my code review demonstrate my ability to employ strategies for building collaborative environments that enable diverse audiences to support organizational decision-making in the field of computer science.  My code review showed my ability to effectively communicate my thoughts and ideas about my project with a diverse audience. I was able to look at the code that I had written and keep best coding practices in mind.  I talked about how the code looked as well as the lack of comments as well as having too many comments at times in my code.  I supported my decision to enhance the Java application so the user could interact with the application.  When doing a code review you must critique the code and not the person who wrote it. This is something that I did to my code however when I get the chance, I will always treat my peers with the respect and dignity that I would like to be treated with. 
	
   The skills used in my artifact narratives as well as my code review demonstrate my ability to design, develop, and deliver professional-quality oral, written, and visual communication that are coherent, technically sound, and appropriately adapted to specific audiences and contexts.  When I talked about what my code did, how I needed to clean it up as well as what I planned on enhancing I showed that I can convey my ideas and communicate with oral skills.  My written communication skills are shown in my artifact narratives as I discuss why I chose an artifact, and how I enhanced the project. My written communication skills are also demonstrated in the README page of my repositories. 
	 
   The skills used in my Java console log artifact demonstrate my ability to Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices.  I created an array in this project as well as methods that would add, remove, and update the array.  The main method was not present in the first iteration of this project.  I made sure to update the algorithm to solve the problem that the user was not able to interact with the application.  By creating a main method and adding a scanner and print statements I was able to create a console log.  From there I created a while loop that includes a switch statement to capture the user’s choice.  Each switch statement allowed the user to either enter a contact, display the contacts, or exit the application.  I could have used an if /else statement to achieve these results. However, I chose to use the switch statement to ensure that my code would look neat and be easier to read. 
	
   The skills used in both artifacts demonstrate my ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals.  In the script for my SQL statements, it shows that I was displaying my table anytime I made a change to it.  This was to ensure that I was not breaking anything or changing it too much at once.  This also ensures that I don’t spend an hour working on code for it to not work.  It is best to work in smaller incremental steps to ensure these things don’t happen.  Looking at my artifacts you can see that I created code that follows industry standards in how the code is formatted.  My second artifact shows my skill when it comes to slightly more advanced techniques in SQL.  I joined my tables and picked specific data from the new table.  Adding two columns together and totaling the sum of those columns into a new column also showed my ability to use innovative techniques in SQL.  These are techniques that I did not use in my SQL class.  I learned a lot through trial and error when trying new concepts, this is where I learned the most.
	
   The skills used in my Java application demonstrated my ability to develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources.  Throughout the process of creating code in my application, I had error message after error message.  I made sure to take care of all the IDE’s error messages to ensure that I kept my code as secure as possible. By simply removing the error messages you can’t get rid of all the vulnerabilities, but it helps.  I used java so buffer overflow was not a concern to worry about like I had to with C++ in my secure coding class.  When creating this application it was important to have bounds that the contact had to fall within. For example, in the code, the contact could not be null and had to be less than 10.  When looking to add the contact the ContactService class had a method called addContact.  This method stated that if the contact ID was not null, then it would return false and not add it.  If the contact ID was null, it would return true and add the contact to the array list. This is a security feature that prevents users’ information from being overwritten and lost forever.  Anytime I create code I try to ensure that I think about what someone with bad intentions could do with my code. 

## *Code Review*
   This code review was done at the begging of the class before any enhancements were done.  This allowed me to discuss areas of opportunity for my code and how    I could better what I had up to that point.  I discuss the code and what it does here as well as the plans I had to enhance my code. 
 <a href="https://www.youtube.com/watch?v=zUO0tyRGisA"> Code Review Link </a>

   
## Areas of enhancements

1. Software Design
2. Algorithm and Data Structures
4. Database

## *Atifacts*:
1. Program that creates contacts, appointments, and tasks.  As well as testing the code with JUnit to ensure that my coverage of the code is efficient.  This artifact was created in my CS 320: Software Testing, Automation, and Quality Assurance. I enhanced the contact class as I was able to create a console log the user can interact with. 
2. This is a script with some screenshots that I put together.  I took a database that I created in my DAD 220: Introduction to SQL class.  This database was then transformed into the database that you'll see in the link.  The database shows me updating and manipulating the data to find certain information about Minnesota Wild players and their statistics.  

## *Original code as well as enhanced code for my artifacts*:

Original code:

<a href="https://github.com/mikegontarek/mikegontarek.github.io/blob/main/Original%20Contact.java"> Original Contact class </a>

<a href="https://github.com/mikegontarek/mikegontarek.github.io/blob/main/Original%20ContactService.java"> Original ContactService class </a>

Enhanced Code: 

<a href="https://github.com/mikegontarek/mikegontarek.github.io/blob/main/Contact.java"> Enhanced Contact class </a>  The enhancement is the main file in this calss.

<a href="https://github.com/mikegontarek/mikegontarek.github.io/blob/main/ContactService.java"> Enhanced ContactService class </a> This enhancement is the displayContact method at the bottom of file.

Live SQL code. 

I have quite a few lines of code here as I had to recreate my tables from DAD:220.  We used Codio to make our database and tables. Since I was over two years removed from taking this class I needed to recreate the entire final project for that class then I could enhance the tables. 

<a href="https://github.com/mikegontarek/mikegontarek.github.io/blob/main/sqlscript%20(3).sql"> All SQL statements.</a>  This shows what I did that did and did not work.  This shows how I learned and made adjustments along the way. 

### Screenshots for SQL

<a href="https://github.com/mikegontarek/mikegontarek.github.io/blob/main/inner%20join%20of%20goals%20and%20assists.1.png"> Inner Join </a>

<a href="https://github.com/mikegontarek/mikegontarek.github.io/blob/main/USA%20GOALS.1.png"> USA Goals </a>

<a href="https://github.com/mikegontarek/mikegontarek.github.io/blob/main/TOTAL%20RUS%20GOALS.1.png"> Russia Goals </a>

<a href="https://github.com/mikegontarek/mikegontarek.github.io/blob/main/TOTAL%20CAN%20GOALS.1.png"> Canada Goals </a>

<a href="https://github.com/mikegontarek/mikegontarek.github.io/blob/main/WILD%20PLAYER%20POINTS.1.png"> Wild Player Points </a>



## *Naratives for artifacts*
<a href="https://github.com/mikegontarek/mikegontarek.github.io/blob/main/3-2%20Milestone%20Two--%20Enhancement%20One--%20Software%20Design%20and%20Engineering%202.docx"> Link to artifact 1 narative </a>

<a href="https://github.com/mikegontarek/mikegontarek.github.io/blob/main/4-2%20Milestone%20Three--%20Enhancement%20Two--%20Algorithms%20and%20Data%20Structure.docx"> Link to artifact 2 narative </a>

<a href="https://github.com/mikegontarek/mikegontarek.github.io/blob/main/5-2%20Milestone%20Four--%20Enhancement%20Three--%20Databases.docx"> Link to artifact 3 narative </a>
