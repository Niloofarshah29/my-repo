# my-repo
testing my
let todos = [];

function addTask(task) {
  todos.push(task);
  console.log("Task added:", task);
}

functio showTasks() {
  console.log("Todo List:", todos);
}

addTask("Learn GitHub");
addTask("Upload projects");
showTasks();
