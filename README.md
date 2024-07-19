# TO_DO_DOS
## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daily Challenges</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color:white;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 600px;
            margin: auto;
            padding:80px;
            background-color:darkcyan;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        h1 {
            text-align: center;
            color: white;
            font-weight: bold;
        }
        .add-task {
            display: flex;
            justify-content: space-between;
            margin-bottom: 30px;
        }
        .add-task input {
            flex: 1;
            padding: 10px;
            margin-right: 10px;
            border: 1px solid #ccc;
            border-radius: 10px;
        }
        .add-task button {
            padding: 10px;
            background-color:yellowgreen;
            color: #fff;
            border: none;
            cursor: pointer;
            border-radius: 30px;
        }
        .add-task button:hover {
            background-color:green;
        }
        .tasks {
            list-style: none;
            padding: 0;
        }
        .tasks li {
            display: flex;
            justify-content: space-between;
            padding: 10px;
            background-color: #f9f9f9;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 10px;
        }
        .tasks li.completed {
            text-decoration: line-through;
            color: #888;
        }
        .tasks li button {
            background-color: rgb(208, 19, 208);
            color: #fff;
            border: none;
            cursor: pointer;
            border-radius: 20px;
        }
    </style>
</head>

<body>
    <div class="container">
        <h1>WORK TO-DOS</h1>
        <h3 style="color: yellow;text-align: center;">Enter text into the input field to add items to your list</h3>
        <h3 style="color: green;text-align: center;">Click the item to mark it as complete.</h3>
        <h3 style="color: darkblue;text-align: center;">Click the "X" to remove the item from your list.</h3>
        <div class="add-task">
            <input type="text" id="taskInput" placeholder="Add a new task">
            <button onclick="addTask()">Add Task</button>
        </div>
        <ul class="tasks" id="taskList"></ul>
    </div>
    <script src="script.js"></script>
</body>
</html>
```
## OUTPUT
![image](https://github.com/user-attachments/assets/b9237ded-9058-4a3f-8ba0-7991dcc48db8)
