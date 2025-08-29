# MULTITHREADED-CHAT-APPLICATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: PRABHU DEVRAJ BANGARI

*INTERN ID*: CTO4DY391

*DOMAIN*: JAVA PROGRAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

MULTITHREADED CHAT APPLICATION DETAILED DESCRIPTION:-

For my networking-based project, I created a Multithreaded Chat Application using Java sockets and multithreading. The purpose of this project was to understand how client-server architecture works in real-world applications like WhatsApp, Telegram, or Messenger, where multiple users interact simultaneously.

This application demonstrates how a server can manage multiple clients at the same time using threads, and how messages can be broadcast in real time to all connected users. By implementing this, I not only learned the technical aspects of Java networking but also gained an understanding of how scalable and concurrent systems work.

Tools I Used

For building this project, I relied on the following tools:

Java Development Kit (JDK):
I used Java as the core programming language because it provides built-in networking classes like Socket, ServerSocket, PrintWriter, and BufferedReader. Java also supports multithreading through the Thread class, which is essential to handle multiple users at once.

Command Prompt (Windows CMD):
I did not use any heavy IDE such as Eclipse or IntelliJ for this project. Instead, I used the Command Prompt in Windows to compile and execute my program. By doing so, I gained more clarity about how Java files are compiled (javac) and executed (java). Running in CMD also helped me simulate multiple clients by opening multiple terminal windows at the same time.

Notepad / Text Editor:
To write my code, I used a simple text editor (like Notepad). I saved the server program as ChatServer.java and the client program as ChatClient.java. This simple approach helped me stay close to the fundamentals instead of relying on IDE shortcuts.

My Experience Running the Program

To execute the program, I first compiled both files using the command:

javac ChatServer.java ChatClient.java


Then, I ran the server with:

java ChatServer


This initialized the server and kept it waiting for client connections.

After that, I opened two or more new command prompt windows and executed:

java ChatClient


Each client connected to the server. Once connected, any message typed in one client’s terminal was broadcast to all other clients, including the sender.

For example:

Client 1 typed: Hello everyone

Server printed: Received: Hello everyone

Client 2 and Client 3 immediately saw the message on their screens.

This real-time communication proved that my multithreaded chat app was working correctly.

Future Uses and Importance

This project has strong practical applications in today’s digital world. Some future uses and extensions include:

Group Chat Applications:
The basic idea of this project can be expanded to create group chat systems like WhatsApp groups or Slack channels.

Private Messaging:
Currently, all messages are broadcast to every connected client. In the future, I can extend this by adding user IDs and allowing direct one-to-one private chats.

File Sharing:
With additional coding, this system can be improved to send not just text messages but also files, images, and documents.

Real-World Networking Systems:
This project gave me insight into how actual servers handle concurrent users. The same principle is applied in multiplayer games, live classrooms, and video conferencing applications.

Learning for Advanced Frameworks:
By working directly with sockets and threads, I have built a foundation that will help me understand advanced frameworks like Netty or web-based real-time communication systems such as WebSockets.

Conclusion

Developing the Multithreaded Chat Application taught me how powerful Java’s networking and threading capabilities are. By running it through the Windows Command Prompt, I also strengthened my fundamentals of compiling, executing, and managing multiple Java programs simultaneously.

The project not only allowed me to practice coding but also helped me understand how real-time communication works in today’s connected world. It is a stepping stone toward building more advanced client-server applications that could be used in real-world scenarios.

In the future, I can extend this project with features such as private messaging, authentication, file transfers, and even GUI-based chat windows using JavaFX or Swing. Overall, this project was a valuable experience in learning how servers and clients interact over a network and how multithreading ensures scalability in communication systems.

*OUTPUT*:
