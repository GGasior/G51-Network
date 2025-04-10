# LOTcryCRT - Lotto Neural Network

A distributed neural network system for lotto prediction with lightweight client capabilities.

## Lightweight Client

The lightweight client allows you to participate in distributed training without needing to install TensorFlow or other heavy dependencies. It connects to the central server and assists with tasks like data validation, result verification, and pattern analysis.

### Requirements

- Node.js 14.0 or higher
- Internet connection to reach the central server

### Installation

1. Clone this repository
   ```
   git clone https://github.com/yourusername/LOTcryCRT.git
   cd LOTcryCRT
   ```
2. Install dependencies:
   ```
   npm install
   ```

### Usage

Run the lightweight client with:

```
npm start
```

Or to specify a custom server:

```
npm start -- http://85.215.224.204:3000
```

Alternative command:
```
node light-client.js http://85.215.224.204:3000
```

### Features

- Automatically connects to the central server
- Reports system capabilities
- Performs lightweight tasks that don't require TensorFlow
- Reconnects automatically if connection is lost
- Shows real-time training progress

### Troubleshooting

If you have connection issues:

1. Ensure the server URL is correct
2. Check that the server is running and accessible
3. Verify there are no firewalls blocking the connection
4. Confirm your network connectivity is stable

Try running with an explicit protocol if having issues:
```
node light-client.js http://85.215.224.204:3000
```

## GitHub Repository

This project is hosted on GitHub. To contribute or report issues:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 
