# alu-back-end

Back-end engineering projects completed as part of the Software Engineering
programme at African Leadership University (ALU).

## Projects

| Directory | Description |
| --- | --- |
| [`api/`](./api) | Python scripts that consume a REST API and process its data |

## api

Scripts that query the [JSONPlaceholder](https://jsonplaceholder.typicode.com)
REST API for employees and their TODO lists.

| File | Description |
| --- | --- |
| `0-gather_data_from_an_API.py` | Displays an employee's TODO list progress for a given employee ID |

### Usage

```bash
$ ./api/0-gather_data_from_an_API.py 2
Employee Ervin Howell is done with tasks(8/20):
	 distinctio vitae autem nihil ut molestias quo
	 ...
```

## Requirements

- Ubuntu 14.04 LTS
- Python 3.4.3
- `requests` module (`pip3 install requests`)
- Code style: PEP 8, checked with `pycodestyle`

## Author

David-Harold Koffi-Essiben ([@builtbykoffi](https://github.com/David-Harold))
