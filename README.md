# my-repo
testing my
le todos = [];

function addTask(task) {
  todos.push(task);
  console.log("Task added:", task);
}

function showTasks() {
  console.log("Todo List:", todos);
}

addTask("Learn GitHub");
addTask("Upload projects");
showTasks();
