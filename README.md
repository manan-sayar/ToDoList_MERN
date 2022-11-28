# ToDoList_MERN
Basic To do list using MERN Stack<br>
Problem Statement:
A To-do list is used to keep track of your tasks in a elegant way. To-do list has features to add todos, delete todos, edit todos, mark todo as done and tabs to sort through todos.<br>
Motivation:
The motivation for this project is to understand the basics of MERN stack and various libraries and components that can be used with MERN stack.<br>
Stack and libraries used:<br>
Node and express used as backend<br>
MongoDB local database used<br>
React used for the front end and to create the actual app and UI<br>
Cors is a library used to allow fetching and sending information to another port number as by default it is not allowed in web browers<br>
Moongoose to create the connection with the database and edit the data in it.<br>
Express route is used to route in various to the various endpoints created.<br>
Redux is used to store the state of the various components in the frontend and change them accordingly.<br>
Axios is used to call the EPI for the various tasks in the project and dispatch action used for Redux<br>
Reducer and combinereducer is a function that is used to combine various reducers together. Reducers are used to change the state of an object and pass that state to the user interface.
Redux Dev Tool Extension is a sub package of the Redux which is used to view the functionality of the Redxx in the inspect element page.<br><br>
Deployment:<br>
the react up is used as a user interface and it is what interacts with the user. by default it runs at port 3000.<br>
We use a mongo db database stored locally on the computer and we use Mongodb compass GUI provided by Mongodb in order to make changes and view the contents of the database<br>
We have an index file which is used to run the server using Express which access the backend. We use Nodemon to run the server continuously so that if any changes occur the server automatically restarts and we choose the port 8000 to run the server.<br><br>
![mern todo](https://user-images.githubusercontent.com/71921157/204312385-b52c6853-fd73-4c5c-a381-d1e1fcc535f5.jpeg)

Features:
A text field which used to type the todos<br>
On pressing enter a list of todos is displayed in dark blue.<br>
On clicking the todo there is a strike through indicating it is completed.<br>
Next to each to do there is are two icons.<br>
One is edit icon used to edit the contents of the todo.<br>
Another one next to it is the delete icon used to remove the todo.<br>
There are three tabs:All todos,Active todos,Done Todos<br>
All todos display all the todos<br><br
Active todos display todos not completed<br>
Done todos display the todos that are completed.<br>
All the todos are inserted into the database and can be viewed using mongodb compass.<br>
When we toggle a todo the done key in the document for that todo changes to true. By default it is false.<br>
Redux is used to store all the states of the objects and can be viewed on the brower using react dev tools extension.<br><br>
Future scope:<br>
User authentication login and registration <br>
Adding more features and converting it into a full fledged notes and task management app<br><br>

MERN stack project from KJSCE



