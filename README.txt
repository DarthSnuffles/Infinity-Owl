READ ME

To run the Infinity Owl prototype:
1. Download and unzip the application folder, 'InfinityOwl.zip'.
2. Download Unity Version 2018.2.15f1 Personal.
3. Run Unity and click 'Open' on the Projects screen.
4. Navigate to the unzipped application folder, and select the home directory.
5. Wait for Unity to compile the application.
6. You will also need to set up a MySQL server on localhost, 
and edit the connection details in 'db_access.py' and 'rec_system.py' accordingly.
7. On the MySQL server, run the SQL programs 'createDatabase.sql', 'insertTopics.sql' and 'createQuizzes.sql' in that order.
This will set up the database to be used by the application, and insert the sample topics and questions,
so that they can be played...
8. In Unity, add all of the scenes (in the Scenes folder) to the Build Settings, and click 'Build'.
9. Navigate to the 'LogIn' scene in Unity (in the Scenes folder).
10. Click the 'Play' button in the Unity Editor, to run the prototype application in Game View.

NOTE: You may also need to download the Standard Assets from Unity's Asset Store,
for parts of the application to be displayed correctly (such as the Particle System Sun).

NOTE 2: The only code that I claim credit for writing by hand are the C# ('.cs') and Python ('.py') files,
stored in the top level of the Assets folder, along with the SQL ('.sql') files in the Database folder. 
I created the '.unity' files in the Scenes folder using the Unity Editor. 

Some external C# packages were used, which can be found in the Packages folder.
Additionally, the Simple Scene Fade Load System was downloaded from Unity's Asset Store.

Python 2.7 must also be installed, such that Python can be executed at the file path: 'C:\\Python27\\python.exe' 
(this is required for the front-end application to interact with the back-end programs and the database).
A number of Python libraries are required, which may or may not need to be installed.
These are 'sys', 'os', 'csv', 'mySQLdb', 'random' and 'datetime'.

Thanks,
Michael