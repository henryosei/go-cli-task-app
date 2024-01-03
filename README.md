

# GoTodo CLI

GoTodo is a simple command-line interface (CLI) based Todo application written in Go. It allows you to manage your tasks efficiently from the terminal.

## Features

- Add new tasks
- View all tasks
- Mark tasks as completed
- Remove tasks
- Clear all completed tasks

## Installation

Ensure you have Go installed on your machine. Then, you can install GoTodo using the following command:

```bash
go install github.com/henryosei/go-cli-tash-app
```

## Usage

### Adding a Task

```bash
gotodo add "Buy groceries"
```

### Viewing Tasks

```bash
gotodo list
```

### Completing a Task

```bash
gotodo complete 1
```

### Removing a Task

```bash
gotodo remove 2
```

### Clearing Completed Tasks

```bash
gotodo clear
```

## Examples

- Add a task: `gotodo add "Finish project"`
- List all tasks: `gotodo list`
- Complete a task: `gotodo complete 1`
- Remove a task: `gotodo remove 2`
- Clear completed tasks: `gotodo clear`

## Contributing

Feel free to contribute to the development of GoTodo by submitting issues or pull requests. Follow the [contribution guidelines](CONTRIBUTING.md) for more details.

## License

This GoTodo CLI is distributed under the [MIT License](LICENSE).
```

Make sure to replace `yourusername` in the installation section with the actual GitHub username or repository path where you want to host your GoTodo code. Additionally, consider creating a `CONTRIBUTING.md` file with guidelines for contributing to your project. Adjust the license link accordingly based on your preferred license.