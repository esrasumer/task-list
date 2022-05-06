<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.2.0/css/all.css">
    <link rel="stylesheet" href="style.css">
    <title>My Task List</title>
</head>

<body>

    <div class="container p-3">
        <h1 class="app-title" id="header">To Do App</h1>
        <div class="card">
            <div class="card-header">
                New Task
            </div>
            <div class="card-body">
                <form id="addTaskForm">
                    <div class="input-group mb-3">
                        <input id="txtTaskName" name="taskName" type="text" class="form-control" placeholder="Type a new task" aria-describedby="btnAddNewTask">
                        <div class="input-group-append">
                            <button class="btn btn-primary" type="button" id="btnAddNewTask">
								<i class="fas fa-plus"></i>
							</button>
                        </div>
                    </div>
                </form>
            </div>
        </div>
        <div class="card mt-3">
            <div class="card-header">
                Task List
                <a id="btnDeleteAll" href="#" class="btn btn-outline-danger btn-sm delete-all float-right">	
						Delete All
					</a>
            </div>

            <ul id="task-list" class="list-group">
                <li class="list-group-item list-group-item-secondary">To do item
                    <a href="#" class="delete-item float-right">
                        <i class="fas fa-times"></i>
                    </a>
                </li>
                <li class="list-group-item list-group-item-secondary">To do item
                    <a href="#" class="delete-item float-right">
                        <i class="fas fa-times"></i>
                    </a>
                </li>
                <li class="list-group-item list-group-item-secondary">To do item
                    <a href="#" class="delete-item float-right">
                        <i class="fas fa-times"></i>
                    </a>
                </li>
                <li class="list-group-item list-group-item-danger">To do item
                    <a href="#" class="delete-item float-right">
                        <i class="fas fa-times"></i>
                    </a>
                </li>

            </ul>

        </div>
    </div>

    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js"></script>
    <script src="script.js"></script>
</body>

</html>
