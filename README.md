# Cluster-Manager

Job Management System for SLURM using Django REST and Angular
This project involves developing a web-based system for managing jobs submitted to clusters utilizing SLURM (Simple Linux Utility for Resource Management) as the workload management system. Using Django REST Framework for the backend and Angular for the frontend, the goal is to provide an intuitive interface that allows users to submit, monitor, and view the status and logs of jobs directly through a browser, without the need for authentication.

## Key Features:

* Job Submission: Users can submit jobs to SLURM via a web interface with customizable parameters such as runtime, number of tasks, partition, and scripts.
* Job Monitoring: View the real-time status of submitted jobs (pending, running, completed, or failed).
* Logs and Outputs: Direct access to job output and error logs through the interface, with the ability to download files.
* Job History: Access a complete history of executed jobs, including execution time and final status.
* Responsive Interface: Built with Angular, the interface is user-friendly and fully responsive, ensuring access on any device.

## Objectives:

Automate the job submission and monitoring process in SLURM, making it accessible via the web.
Eliminate the need for manual interactions with the terminal for users managing jobs on clusters.
Facilitate quick and practical access to job execution logs and results.

## Technologies Used:

* Django REST Framework for creating RESTful APIs.
* Angular for frontend development.
* SLURM for job submission and management in clusters.
* MySQL for storing job information.
* Docker for easy deployment and orchestration of the system.

This system is ideal for high-performance computing (HPC) environments where multiple users need to manage jobs simultaneously, without the need for authentication and permission control.
