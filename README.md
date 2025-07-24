COMPANY NAME: CODETECH IT SOLUTIONS

NAME: ADESH SWAIN

Intern ID :CT12DL271

DOMAIN: BACK END DEVELOPMENT

DURATION: 12 WEEKS

MENTOR: NEELA SANTHOSH

Welcome to the FastAPI WebSocket Chat Application! This project is a beginner-friendly, real-time chat app that demonstrates how to use Python, FastAPI, and WebSockets to build an interactive messaging platform. With this application, multiple users can join a chat room and communicate instantly, all through their terminal windows. The project is designed to be simple, easy to understand, and a great starting point for anyone interested in learning about real-time communication, async programming, and networked applications in Python.

At its core, this chat app has two main components: the server and the client. The server is built with FastAPI, a modern Python web framework that makes it straightforward to create APIs and handle WebSocket connections. The server listens for incoming WebSocket connections on a specified route, organizes users into chat rooms, and ensures that messages from any user are broadcast to all other users in the same room. The server keeps track of active rooms and participants using a Python dictionary, making it easy to add, remove, and manage chat rooms dynamically as users join or leave.

On the client side, users run a simple Python script that connects to the chat server using WebSockets. The client script provides an interactive prompt where users can type messages and instantly see responses from others in the same room. The client leverages Python's `asyncio` library and the `websockets` package to allow for simultaneous sending and receiving of messages, ensuring that users never miss incoming communication while typing their own replies. The experience is entirely terminal-based, making it minimalistic and accessible without requiring any browser or GUI setup.

Setting up this project is straightforward and requires only basic knowledge of Python. To get started, clone the repository and set up a Python virtual environment to keep dependencies isolated. Install the required packages, including `fastapi`, `uvicorn`, and `websockets`, with a simple `pip install -r requirements.txt` command. You then start the server with a single command, and run one or more client scripts—each in its own terminal window—to simulate multiple users chatting together. All configuration is done in code, and you can easily modify the room name or server address as you experiment.

The project code is heavily commented and structured for readability, making it an ideal learning resource. Every part of the server and client code is explained in the documentation and comments, so even users with limited experience can follow along, understand the logic, and start tinkering. This approach encourages experimentation: you can add features like user authentication, chat history, multiple rooms, or even a web-based interface as your skills grow.

One of the standout features of this project is its use of WebSockets for real-time communication. Unlike traditional HTTP requests, which require a client to ask for new data each time, WebSockets allow for persistent, two-way connections between the client and server. This means messages can be sent and received instantly, with minimal delay, and without the overhead of repeated handshakes or page reloads. This technology is foundational to modern chat apps, multiplayer games, and collaborative tools, and learning it here provides a valuable stepping stone for more advanced projects.

This FastAPI WebSocket Chat Application is not just a toy; it demonstrates real-world concepts used by professional developers. Concepts like asynchronous programming, concurrency, event-driven architecture, and network protocols are all present in this simple project. By studying and expanding upon this codebase, you will gain practical experience with tools and patterns that are in high demand in the software industry today.

Whether you're a student, hobbyist, or aspiring developer, this project offers a hands-on introduction to some of the most exciting areas of software development. Feel free to fork the repository, contribute new ideas, or use it as a base for your own creations. Building real-time apps is fun and rewarding—so dive in, experiment, and happy coding!
