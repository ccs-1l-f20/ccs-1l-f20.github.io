# ccs-1l-f20.github.io

Notes from class

* [Edit me](https://github.com/ccs-1l-f20/ccs-1l-f20.github.io/edit/main/README.md)  
* [See me on GitHub](https://github.com/ccs-1l-f20/ccs-1l-f20.github.io/blob/main/README.md) 


# Tuesday 10/20

* Luke: Windows, Desktop application to configure keys and shortcuts with a GUI for Windows
* Josiah: Windows, Board Game Simulator: platform "Blazor"?  C# based backend. 
* Michael: Mac, Sound Software, Audio for C++ 23 or 26
* Geordie: Linux/Windows, but all programming on Linux, build a new open source Speech-To-Text software pkg
* Devin: Mac, A thing like Word Press for creating your own website.  backend in JavaScript now
* Anmol: Windows, NLP model for jobs.   Python/Flask.
* Aditya: Mac, Course Planning, iOS Swift


# Thursday 10/15

* Luke: Windows, Desktop application to configure keys and shortcuts with a GUI for Windows
* Josiah: Windows, Board Game Simulator: platform "Blazor"?  C# based backend. 
* Michael: Mac, Sound Software, Audio for C++ 23 or 26
* Geordie: Linux/Windows, but all programming on Linux, build a new open source Speech-To-Text software pkg
  * Found: https://github.com/clab/dynet
  * For next week: learning the jargon
* Devin: Mac, A thing like Word Press for creating your own website.  backend in JavaScript now
* Anmol: Windows, NLP model for jobs.   Python/Flask.
* Aditya: Mac, Course Planning, iOS Swift



# Tuesday 10/13

* Luke: Windows, Desktop application to configure keys and shortcuts with a GUI for Windows
  * Using Java, made a program that can create new scripts
  * Figuring out why other button doesn't work
  * Demo... 
  
* Josiah: Windows, Board Game Simulator: platform "Blazor"?  C# based backend. 
  * More refactoring
  * Websockets, client to server
  * client to server to a different client?  How to go about this?
  * have a demo for tonight
  * adding in chess pieces with transparency... checking if a pixel is transparent.
  
* Michael: Mac, Sound Software, Audio for C++ 23 or 26
  * Able to make sounds..
  * No user input yet
  * GUI... linking statically
  * Their demos compile, but mine don't yet...
  * Try a sound demo on Thursday...
  
* Geordie: Linux/Windows, but all programming on Linux, build a new open source Speech-To-Text software pkg
  * SQL API working...
  * Can query tables / etc. from C++ code
  * Made a few prototype files...  Levenshtein distance measure of how close one sequence is to another insertions/delections/replacements to change one to the other ...
  

* Devin: Mac, A thing like Word Press for creating your own website.  backend in JavaScript now
  - frontend React.
  - a minimal API running locally 
  - a little webapp, hello world demo
  - React Router
  - demo

* Anmol: Windows, NLP model for jobs.   Python/Flask.
  - Fixed credentials
  - Tried out machine learning model with NLP
  - Some issue with Pandas and shape of the array
  - Deep learning model for NLP
  - Classification: This is a job title, and this is not a job title...

* Aditya: Mac, Course Planning, iOS Swift
  - parsing json in Swift
  - demo.. 
  
 




# Thursday 10/08


* Devin: Mac, Webapp for Select a programming language examples of code from public github repos.   Flask
  - GitHub mostly used for accessing your own repos.
  - Not so sure about accessing public repos from all over the place
  So: NEW PROJECT
  - A thing like Word Press for creating your own website
  - logins, who has access to your website, calendar, using a db and an API
  - Content Management System (CMS)
    - Category for things like Wordpress, Joomla, Drupal <--open source, SquareSpace (commerical)
  - backend in JavaScript now
  - frontend React.
  Some suggestions:
  - Would it be worthwhile to spend a little time familiarizing yourself with Wordpress,
    Drupal just to get a sense of what systems like that do?
  - Mostly: the pain points...
  - Code vs. WYSIWYG editing... leaning towards WYSIWYG... 
  - <https://ckeditor.com/>
  - Consider Heroku: use Postgres 
  - Consider: node + express + react...
  - Consider: next.js: 
  - Consider: Auth0 for the authorization... have people login
    - Delegate logins to Google, GitHub, Facebook, Twitter... (auth0.com)
  - Documentation at https://ucsb-cs48.github.io website... 
  - Goal: Hello World demo on Tuesday
* Aditya: Mac, Course Planning, iOS Swift
  - Got key, and it worked, and got the email to get own key
  - Ran on terminal and got output from RestFul API
  - On Swift, created a Restful API for getting Covid Data, to practice API requests
  - some demo code for the UCSB Courses API: <https://github.com/ucsb-cs56-w20/ucsb-courses-search>
  - We got Swift code reading the UCSB courses data!
* Anmol: Windows, NLP model for jobs.   Python/Flask.
  - Uploaded SQLLite DBs to GitHub
  - Added to the README, plus Google Sheets link
  - Let's discuss how to handle secrets/credentials with configuration files
  - Jurafsky text... some chapters that may be useful
    - classification... naive Bayes and sentiment classification, etc.
    - At some point, connect you to William Wang, Xifeng Yan, who are two of our local NLP experts
      (Computational Linguistics).
  - Goal for Tuesday: demo of doing some NLP on some data
* Geordie: Linux/Windows, but all programming on Linux, build a new open source Speech-To-Text software pkg
  - Got some packages: SQL db, testing it out with dedicated client
  - Some example tables, dbs
  - Issues connecting SQL and C++ ...
  - Need to learn classes in C++, and probably STL (Standard Template Library)
  - Follow up with Jurafsky text
* Josiah: Windows, Board Game Simulator: platform "Blazor"?  C# based backend. 
  - From old code, have room system, able to move stuff around...  
  - All in Blazor server, so refactor into Blazor web assembly
  - Still need some more refactoring
  - Can move things around on screen, but others in the same "room" don't see the changes
  - May not be the most secure solution, but it works
* Luke: Windows, Desktop application to configure keys and shortcuts with a GUI for Windows
  - Reading up on running autohotkey scripts from Java and creating GUIs...
* Michael: Mac, Sound Software, Audio for C++ 23 or 26
  - got the examples to compile, and a test script
  - made own makefile rather than using CMake
    - it looks nicer
    - but it won't necessariy be portable?
    - But as it turns out, the implementation is Mac only as this point anyway...
  - May need to read about std::atomic because there may be multiple threads.
  - May need to read up on threads.
  
# Tuesday 10/06

## Status update on project plans

* Aditya: Course Planning, iOS Swift
* Anmol: NLP model for jobs.   Python/Flask.
* Devin: Webapp for Select a programming language examples of code from public github repos.   Flask
* Geordie: build or improve an existing open source Speech-To-Text software pkg
  - learning towards making one from scratch
  - with Libravox (public domain)
    - The extra stuff at the beginning and the end of Libravox might be a problem
    - Need: some heuristic to line up the text and the speech, and to remove extraneous speech (stuff that's not in the text.)
  - Instead: consider the corpus voxforge
  - Approx diff to know how to line up a Libravox recording...
* Josiah: Board Game Simulator: platform "Blazor"?  C# based backend. 
* Luke: Desktop application to configure keys and shortcuts with a GUI for Windows
* Michael: Sound Software
  - Audio for C++ 23 or 26 (Mac)
  - Coreaudio (stdaudio that wraps coreaudio)


# Thursday 10/01

* Welcome
* How this class works
  * Choosing a project
  * Setting up a Github Repo and Kanban board
* Units

## The GitHub organization, and the GitHub linker

Please take the following steps:
* Create a GitHub account at <https://github.com> if you don't already have one
* Add your ucsb email to that account
* Login at <https://ucsb-cs-github-linker.herokuapp.com>
* Choose to join the course `ccs-1l-f20`
* You should see a link to an invitation to the organization.  Click to accept
  - Or, find an invitation in your email, and accept
  - Or, visit <https://github.com/ccs-1l-f20> and accept it there.
* Now you should be a part of the organization

## Creating a Repo for your project

## Creating a Kanban board for your project

