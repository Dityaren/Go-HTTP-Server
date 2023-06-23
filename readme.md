# Simple Go HTTP Server

This is a simple Go HTTP server that handles different routes and requests.

## Installation

To run the server, make sure you have Go installed. Then, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repository.git
```

2. Change into the project directory:

```bash
cd your-repository
```

3. Build the project:

```bash
go build
```

4. Run the server:

```bash
./your-repository
```

The server will start running on `http://localhost:8080`.

## Routes

- `/` - Serves static files from the `static` directory.
- `/form` - Handles POST requests and displays form data.
- `/hello` - Responds with "Hello" for GET requests.

## Usage

### Static Files

Any static files placed in the `static` directory will be served by the server. Access them using the base URL.

Example: `http://localhost:8080/index.html`

### Form Submission

To submit a form, send a POST request to `http://localhost:8080/form` with the following parameters:

- `name`: Your name
- `address`: Your address

The server will respond with the submitted form data.

### Hello Endpoint

To receive a "Hello" response, send a GET request to `http://localhost:8080/hello`.

## Contributing

If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
