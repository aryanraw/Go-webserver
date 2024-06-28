# Go-webserver

This project is a simple Go web server that serves static files and handles form submissions. The server listens on port 8080 and provides two main functionalities:

1. Serves a static website.
2. Processes form submissions via POST requests.

## Project Structure

```
Go-webserver/
├── static/
│   ├── index.html
│   └── form.html
├── main.go
└── README.md
```

## Files

- **static/index.html**: A simple HTML file that serves as a static webpage.
- **static/form.html**: An HTML form that accepts user inputs (name and address) and submits them to the server.
- **main.go**: The main Go file that sets up the web server and handles routing.
- **README.md**: This file, which provides an overview and instructions for the project.

## Getting Started

### Prerequisites

- Go (version 1.16+ recommended)

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/go-webserver.git
    cd go-webserver
    ```

2. Create the `static` directory and add `index.html` and `form.html` files as shown above.

3. Create the `main.go` file as shown above.

---

## Running the Server

1. Navigate to the project directory:

    ```sh
    cd Go-webserver
    ```

2. Run the Go server:

    ```sh
    go run main.go
    ```

3. Open your web browser and navigate to `http://localhost:8080` to view the static website.

4. To test the form submission, navigate to `http://localhost:8080/form.html`, fill in the form, and submit it.

5. To access the hello endpoint, navigate to `http://localhost:8080/hello`.

---

Feel free to reach out if you have any questions or suggestions!
