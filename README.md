Disk Scheduling Simulator

Overview

The Disk Scheduling Simulator is a tool designed to visualize and analyze different disk scheduling algorithms, including FCFS (First-Come, First-Served), SSTF (Shortest Seek Time First), SCAN, and C-SCAN. Users can input custom disk access requests and observe how these algorithms optimize seek time and system throughput. This simulator is useful for students, researchers, and system administrators to understand disk scheduling mechanisms and improve storage efficiency.

Features

Support for Multiple Algorithms: Includes FCFS, SSTF, SCAN, and C-SCAN scheduling algorithms.

Custom Disk Requests: Users can input their own sequences of disk requests.

Performance Metrics: Displays key performance metrics like total head movement, average seek time, and system throughput.

Graphical Visualization: Shows real-time head movement through interactive graphs.

Comparison Mode: Allows users to compare different scheduling algorithms side by side.

Export Results: Enables saving of performance reports in CSV, PDF, or JSON formats.

Technologies Used

Programming Language: Python

Libraries & Frameworks:

Matplotlib: Visual representation of disk head movement.

Flask: Backend API for processing scheduling logic.

Tkinter / PyQt: GUI for user interaction and visualization.

Pandas: Data handling and performance metric calculations.

Database: SQLite / PostgreSQL (for storing request logs and performance analysis data)

How It Works

User Inputs Disk Requests: Users enter disk request sequences and specify the initial head position.

Algorithm Execution: The selected scheduling algorithm processes the requests.

Visualization & Metrics: The system displays disk head movement and calculates performance metrics.

Comparison & Reporting: Users can compare different algorithms and export results.

Future Enhancements

Additional Algorithms: Implement LOOK, C-LOOK, and Elevator algorithms.

Real-Time Disk Monitoring: Integrate with actual disk I/O for real-time scheduling analysis.

AI-Based Optimization: Use machine learning models to predict optimal scheduling strategies.

Cloud Integration: Enable remote access and cloud-based storage of disk scheduling logs.
