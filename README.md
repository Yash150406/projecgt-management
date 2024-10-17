Project Management Report System
This is a C program designed to manage and report on project tasks for the fiscal years 2024-2025. The program allows users to input various details about project tasks and generates a comprehensive report summarizing the project's progress, costs, and efficiency.

Features
Input task details including title, assigned personnel, status, submission date, and deadlines.
Calculate the total number of tasks, completed tasks, and tasks completed on or before deadlines.
Report total project costs, profit, and loss.
Generate performance evaluations based on completion percentages.
Getting Started
Prerequisites
To compile and run this program, you need to have a C compiler installed. You can use GCC or any other compiler that supports C.

Installation
Clone the repository:

bash
Copy code
git clone [https://github.com/yourusername/project-management-report.git](https://github.com/Yash150406/project-management)
cd project-management-report
Compile the program:

bash
Copy code
gcc project_management_report.c -o project_management_report
Run the program:

bash
Copy code
./project_management_report
Usage
When prompted, enter the total number of tasks.
For each task, provide the title, allocated person's name, task status (complete/incomplete), submission date, deadline, and cost.
The program will generate a report based on the inputs provided.
Example Input
mathematica
Copy code
Enter total number of tasks : 
3
TASK NUMBER : 1
Enter title of the task : 
Design
Enter name of allocated person for the task: 
Alice
Enter status of task (1=complete, 0=incomplete) : 
1
Enter date of submission of the task (DD MM YYYY) : 
01 03 2024
Enter deadline date (DD MM YYYY) : 
15 03 2024
Enter cost of the task : 
500
Output
The program outputs a summary report detailing:

Total number of completed tasks.
Number of tasks completed on or before the deadline.
Percentages of tasks completed.
Total project costs, profit, and loss.
Performance evaluation based on task completion rates.
Contributing
If you would like to contribute to this project, feel free to fork the repository and submit a pull request. All contributions are welcome!

Acknowledgements
Thanks to the open-source community for inspiration and resources.
