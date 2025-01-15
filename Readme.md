
# grpcApp

A gRPC application implemented in Go, demonstrating client-server communication using Protocol Buffers.

## 🌟 Features

- Efficient client-server communication with gRPC.
- Clear service definitions using Protocol Buffers.
- Modular implementation for client and server.

## 📋 Prerequisites

Make sure you have installed:

- [Go](https://go.dev/) (version 1.16 or higher)
- [Protocol Buffers Compiler (protoc)](https://grpc.io/docs/protoc-installation/)

## 🚀 Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/Jonablo/grpcApp.git
   cd grpcApp
   ```

2. Install project dependencies:

   ```bash
   go mod tidy
   ```

3. Generate the gRPC and Protocol Buffers files (if not already generated):

   ```bash
   protoc --go_out=. --go-grpc_out=. proto/service.proto
   ```

## 💻 Execution

1. Open two terminals, one for the server and another for the client.

2. In the first terminal, start the server:

   ```bash
   cd server
   go run *.go
   ```

3. In the second terminal, start the client:

   ```bash
   cd client
   go run *.go
   ```

## 🛠️ Technologies Used

- **Go**: Programming language.
- **gRPC**: Remote communication framework.
- **Protocol Buffers**: For efficient data serialization.

## 🤝 Contributions

Contributions are welcome! If you want to improve this project, follow these steps:

1. Fork the repository.
2. Create a branch for your changes (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m 'Add a new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a Pull Request.

## 📄 License

This project is licensed under the [MIT License](LICENSE). You can use, modify, and distribute it as needed.