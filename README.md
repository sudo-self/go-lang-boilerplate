# Go Starter
Here you can easily get started with [Go](https://go.dev/) and experiment.<hr>
<img width="832" alt="Screenshot 2023-10-29 at 08 42 44" src="https://github.com/sudo-self/go-lang-boilerplate/assets/119916323/b2cfc298-94e7-4650-9135-8ac303c55e44">
## task.json
{
  // These tasks will run in order when initializing your CodeSandbox project.
  "setupTasks": [],

  // These tasks can be run from CodeSandbox. Running one will open a log in the app.
  "tasks": {
    "go run": {
      "name": "Run",
      "command": "go run main.go",
      "runAtStart": true,
      "restartOn": {
        "files": ["./main.go"]
      }
    }
  }
}
