# Chili 3D Engine

Chili 3D Engine is a powerful and easy-to-use 3D engine package for Node.js, delivered as an NPM package. It comes with a command-line utility to streamline your 3D project development.

## Development

This project uses TypeScript for static typing. 

### Prerequisites

- Node.js
- npm 

### Building the project

1. Clone the repository:

```bash
git clone https://github.com/chili-3d-engine/chili3d-cli.git
cd chili-3d-engine
```

2. Install the dependencies:

```bash
npm install
```

3. Build the project:

```bash
npm run build
```

This command compiles the TypeScript code into JavaScript code, and outputs it to the `dist` directory.

## Testing

To test the Chili 3D Engine locally, you can use the `npm link` command to create a symbolic link in your global node_modules directory that points to your package:

```bash
npm link
```

Then, you can test the `chili3d` command from anywhere on your system:

```bash
chili3d
```

It should print its welcome message.

When you're done testing, you can remove the global link to your package using the `npm unlink` command:

```bash
npm unlink
```

## License

Distributed under the MIT License. See `LICENSE` for more information.