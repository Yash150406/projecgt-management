# Project Management Report Program

## Overview

This C program generates a project management report for tasks associated with a project scheduled for the 2024-2025 period. It allows users to input various details about tasks, including their status, completion dates, and costs. The program then calculates statistics such as the number of completed tasks, those completed on or before the deadline, and total costs.

## Features

- Input and manage multiple tasks.
- Track task status (complete/incomplete).
- Validate submission and deadline dates.
- Calculate and display:
  - Total completed tasks.
  - Percentage of tasks completed on time.
  - Total project costs, profits, and losses.
  - Performance evaluation based on efficiency thresholds.

## Getting Started

### Prerequisites

- A C compiler (e.g., GCC) installed on your machine.

### Compilation

To compile the program, use the following command in your terminal:

```bash
gcc project_management_report.c -o project_management_report
```

### Running the Program

Execute the compiled program with:

```bash
./project_management_report
```

### Input Format

1. Enter the total number of tasks.
2. For each task, provide the following details:
   - Title of the task
   - Name of the person allocated to the task
   - Status of the task (1 for complete, 0 for incomplete)
   - Submission date (DD MM YYYY)
   - Deadline date (DD MM YYYY) for completed tasks
   - Cost associated with the task

### Example Input

```
Enter total number of tasks : 
3
TASK NUMBER : 1
Enter title of the task : 
Task 1
Enter name of allocated person for the task: 
Alice
Enter status of task (1=complete, 0=incomplete) : 
1
Enter date of submission of the task (DD MM YYYY) : 
15 10 2024
Enter deadline date (DD MM YYYY) : 
20 10 2024
Enter cost of the task : 
500
```

## Output

The program outputs the following information based on the input:

- Total number of completed tasks
- Percentage of tasks completed in the project
- Total cost of the project
- Total profit and loss
- Performance evaluation based on efficiency metrics

## Contributing

Contributions to improve the functionality, usability, or performance of the program are welcome. Please fork the repository, make your changes, and submit a pull request.



## Acknowledgements

Thanks to the open-source community for providing resources and tools that help in software development.
