# OS-Practical-Day_20-30.05.2025-

01. This program pair illustrates System V Message Queue IPC between a sender and receiver process:
      The sender uses ftok() to generate a unique key, creates a message queue with msgget(), reads a string from the user, and sends it using msgsnd().
      The receiver accesses the same message queue using the same key and receives the message using msgrcv().
      After reading the message, the queue is properly deleted with msgctl().
This is a clear and effective example of simple message passing using message queues for inter-program communication on Unix-like systems.

![output](https://github.com/user-attachments/assets/57812c69-bfbe-4160-9335-f94b8f333e2e)
