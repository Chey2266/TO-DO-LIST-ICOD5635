# TO-DO-LIST-ICOD5635
TITLE: CODTECH IT SOLUTIONS Internship - Task Documentation: "To-Do LIST" Using HTML, CSS and JAVASCRIPT.

INTERN INFORMATION:
Name: Chaitanya Mulaka
ID: ICOD5635

INTRODUCTION

The To-Do List Web Development Internship task at CODTECH IT SOLUTIONS challenges interns to create a fully functional web-based To-Do List application using HTML, CSS, and JavaScript. The task involves developing a user-friendly interface where users can effortlessly manage their tasks, add new tasks, mark tasks as completed, and remove tasks as needed. Through this internship task, interns will demonstrate their proficiency in front-end web development and their ability to implement essential functionalities for task management applications. 

The transition to digital to-do lists has opened up a plethora of possibilities for customization, real-time collaboration, and accessibility across devices. Despite the availability of numerous applications in the market, there remains a considerable opportunity to create a more intuitive, user-friendly, and flexible tool that caters to the varied needs of users. This project is driven by the vision to harness the capabilities of JavaScript and the versatility of web technologies to deliver a superior task management experience.


TASK IMPLEMENTATION:

The provided HTML file serves as the foundation for the To-Do List application. It includes the necessary elements such as input fields for adding tasks, buttons for user interaction, and a list container to display tasks. The structure is designed to be responsive, ensuring compatibility across various devices and screen sizes.

HTML Structure:

The HTML structure begins with the <!DOCTYPE html> declaration, followed by the <html> element with the lang="en" attribute for specifying the document's language. Within the <head> section, meta tags define the character set and viewport settings, while a link tag imports an external CSS file (To-Do.css) to style the application. The <title> element sets the title of the web page.

CSS Styling: The CSS stylesheet (To-Do.css) applies styles to the HTML elements, ensuring a visually appealing and user-friendly interface. This includes font styles, color schemes, layout adjustments, and responsive design principles.


APPLICATION INTERFACE:

The application interface consists of a container (div.container) that encapsulates the entire To-Do List app. Within this container, the div.todo-app class represents the main To-Do List application. The heading (<h2>) displays the title "To-Do List" along with an optional icon. Below the heading, a row (div.row) contains an input field (<input>) for adding tasks and a button (<button>) to trigger the task addition process.

FUNCTIONALITY IMPLEMENTATION:

The JavaScript code embedded within <script> tags provides the core functionality of the To-Do List application. Key functions include AddTask(), which adds a new task to the list when the user clicks the "Add" button. This function validates the input field to ensure that the user enters a task before adding it to the list. Tasks are added dynamically as list items (<li>) within the <ul> element (list-container). Each task item includes a close button (represented by a small "x") appended as a <span> element.

EVENT HANDLING:

The listContainer element listens for click events, allowing users to mark tasks as completed or remove them from the list. When a user clicks on a task (<li> element), its completion status is toggled by adding or removing the checked class. Clicking on the close button (<span>) removes the corresponding task from the list. Both actions trigger the saveData() function, which stores the updated task list in the browser's local storage.

PERSISTANCE:

The To-Do List application leverages local storage to persist user data across sessions. The saveData() function stores the current state of the task list in the browser's local storage using the setItem() method. Conversely, the showTask() function retrieves the saved task data from local storage using the getItem() method and updates the list accordingly. This ensures that users can access their previously added tasks even after closing or refreshing the application.

USAGE:

Adding a Task: Users enter a task in the input field and click "Enter" to add it to the list.
Marking a Task as Completed: Users click on a task to toggle its "completed" status.
Removing a Task: Users click the "×" button on a task to remove it from the list.

CONCLUSION:

In conclusion, the To-Do List Web Development Internship task at CODTECH IT SOLUTIONS offers interns a valuable opportunity to apply their knowledge and skills in web development to create a practical and functional web-based application. Through the implementation of essential functionalities such as task management, user interface design, and data persistence, interns demonstrate their proficiency and competence in front-end web development technologies. This documentation highlights the key aspects of the task, including HTML structure, functionality implementation, event handling, and data management, showcasing the intern's ability to develop user-friendly and efficient web applications.

OUTPUT:
![Screenshot 2024-04-01 184947](https://github.com/Chey2266/TO-DO-LIST-ICOD5635/assets/153630592/21e842c2-e949-413b-8139-43e82f1022e0)

![Screenshot 2024-04-01 185111](https://github.com/Chey2266/TO-DO-LIST-ICOD5635/assets/153630592/de7f18a7-d4b2-4e18-bcab-6dee70032ebc)




