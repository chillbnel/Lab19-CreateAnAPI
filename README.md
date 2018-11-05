# To-Do List API
To-Do” list API that consist of individual tasks that can be saved into the database and extracted as needed. It also has the ability to get all of the tasks by a simple get request. 

## Components
Two controllers with CRUD endpoints, two models (ToDo and ToDOList), two database tables (one for each model).

## Instructions
1) When accessing the Get action on \api\ToDo, it will output all the individual ToDos.

2) When accessing the Get action on \api\ToDo\{id}, it will output the details of the individual ToDo AND the ToDoList it is a part of.

3) When accessing the Get action on \api\ToDoList, it will output all the ToDoLists.

4) When accessing the Get action on \api\ToDoList\{id}, it will output the individual ToDo list AND the individual tasks associated with it

## Screen Capture
![White Board]()

## Version
1.0.0
