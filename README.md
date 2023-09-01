You are provided with a React application, a to-do list that accepts user input. 

Upon pressing 'Enter,' the input is added to the list below. The 'App.jsx' file contains a simple functional component with a state variable called 'task.' 
The 'list' component takes two children props: 'list' and 'remove,' which are used for item management. However, when the screen is refreshed, the task data disappears.

Your task in this code is to create a higher-order component (HOC) that checks whether local storage is available using state variables and a try-catch block. This HOC will render its output within 'App.jsx', where the 'list' component is located. By doing so, the data will persist even when the page is refreshed, depending on the availability of local storage.