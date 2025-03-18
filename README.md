# TASK CLI MANAGER

## Overview
TASK CLI MANAGER is a simple command-line task management tool. It aims to help users create, update, and delete tasks efficiently. However, it's still a work in progress—sometimes it works, sometimes it doesn't. Feel free to try it out and see how it performs!

## Project from
- [roadmap sh](https://roadmap.sh/projects/task-tracker)

## Features
- No external libraries each thing on native php
- Local Json Management
- Add new tasks
- List all tasks
- Mark in progress
- Mark as done
- Delete tasks (has some issues)
- Update tasks (has some issues)

## Future implementations
- use direcly index on json insead dinamic ids

## Known Issues
- `delete` and `update` functions are not fully reliable.
- `get_index_by_id` function doesn't always work as expected.


## Requeriments
php8 or over

## Usage
Run the script from the terminal:
```sh
chmod 777 ./task-cli
./task-cli add "new one"
```
or
```sh
php ./task-cli add "new task"
```

## Commands
```sh
./task-cli add "<name of your new task>"
./task-cli list             # enumarate all tasks aviables
./task-cli list todo        # enumerate tasks todo
./task-cli list in-progress # enumerate tasks in-progress
./task-cli list done        # enumerate tasks marks as done
./task-cli update <id> "<new description>"
./task-cli delete <id>
```

## Contributions
Since there are known bugs, contributions are welcome! Feel free to submit pull requests to improve the functionality.

## License
MIT License

## Disclaimer
Use at your own risk. No guarantees that it will work as expected!

