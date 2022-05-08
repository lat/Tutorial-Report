### Documentation

—

To be totally honest there’s really not a whole lot going on here.
The ‘main’ file resides in App.js. In App.js we define a handful of styles that make up how our app looks and behaves.
There are ‘View’ styles and ‘Text’ styles.
View styles define how things are displayed on our app, where components go, etc.
Text styles define how text is displayed, fonts, weight, etc.
The information for these styles are defined at the bottom of the .js file in a series of CSS-esque elements where we input information like Hex color codes.
You’ll also notice there’s a Tasks.js that we use elements from in App.js. We define a special component in ‘Tasks.js’ called a Task (who would’ve thought?).
A Task is something that has special properties. In Tasks we set it so it has an opacity square that can be toggled and interacted with in order to ensure that whenever we finish a task, we can check it off.
