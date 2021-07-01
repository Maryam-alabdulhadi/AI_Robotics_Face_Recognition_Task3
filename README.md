# AI_Robotics_Face_Recognition_Task3


**Note:** 

- This is a collaborated work with Weiam Abed

- Please check the Attached files, Pictures, Video

--------------------------------------------------------------


**On this task we worked on real-time face recognition using python, visual studio code, OpenCV, Python Virtual Environment and more on my OS Windows 10.**

1- I Installed Python 3.9.6 through their main website and I checked the box "Add Python 3.9 to path" then started the installaition.

2- I downloaded Visual Studio (The community eddition and check Python Development package, Node.JS, Desktop web c++)

3- Downloaded Visual Studio Code by following the simple installaition steps 

4- from Face Recognition offical website and copied the following code (source method):

    $ git clone git://github.com/ageitgey/face_recognition
    
5- After that I created a dirctory on my desktop called "facerecog"

6- through the terminal I enterd the dirctory path and cloned the previous source method code.

7- Unfotuntly, I faced the following error " git:the term'git' is not recognized.." and fixed it with downloading GIT from the offcial website. 

8- In the same dirctory path I excuted the folllowing which took a lot of time to download the packages:

     pip install virtualenv
     
9- after I entered this code:

    virtualenv maryamenv
    
10- I entered the path of the new created enviroment and enterd the Scripts path to run the following in order activate the enviroment:

    .\activate
    
11- Here I faced the following error "File Cannot Be Loaded Because Running Scripts Is Disabled on This System" and fixed it with this code inside windows power shell:

    Get-ExecutionPolicy -List
    Set-ExecutionPolicy Unrestricted
    Y
    Set-ExecutionPolicy Unrestricted -Force
    
12- inside the enviroment I runed:

    pip install cmake
    
13- Also, which took a lot of time to download all the nesseccary packages. 

    $ python setup.py install

14- I added this code to check the packages are installed "check the picture"

    pip freeze
    
![Screenshot_24](https://user-images.githubusercontent.com/85658893/124128315-56ff2780-da85-11eb-97e3-9b7104f3dc13.png)

15- To open up the python shell:

    python

16- Then entered:

    import face_recognition

17- 

18-

19-

20-

21-

22-

23-

24-

25-

26-

27-

28-

29-

30-
