### DAT250: Software Technology Experiment Assignment 2

* Technical problems
  - In this assignment, I encountered several techical problems. I managed to get through (most of) them in the end. The first one was when installing Derby, where I had problem with the environment variables. The problem was that the variables disappears when I opened another terminal window. I solved that by adding them to my .zhsrc file.
  - The biggest problem I had in this assignment, was when I tried to setup a whole JPA application. I tried both following the tutorial, and using the given maven project as a starting point. I just could not get the database to work. To solve this, I had to manually set our Derby driver (in our IDE) to a .jar file (which was hard to find) in our Derby installation. After that, the database connection worked.
  - In the end, I had a few small problems with the database, and with some of my entity connections. My code should be correct, however I still get some error messages that I couldn't figure out. I checked my implementation with some other students, I they had the same annotations and the same structure as me.
* Link to GitHub:
  - https://github.com/gunnarkleiven/dat250-expass2
* Inspecting the databases
  - For this project, I created two smaller entities for testing: PersonSimple and AddressSimple. This was so I could test by only adding two eintities with ManyToMany connections. This went fine, and can be tested by uncommenting the function call on line 15 in BankingMain.java. To inspect the databases in IntelliJ, we can click the "Database" banner on the far right, and then click the databases we want to inspect. Because of the error messages I get on the Banking example, we currently can't see the database there.
* Pending issues
  - As I mentioned above, I get some errors and exceptions that I did not manage to fix, even tho the important parts of my code should be correct. 

