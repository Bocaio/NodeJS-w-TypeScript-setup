# Node.js with TypeScript Setup

A basic setup for a Node.js project using TypeScript.

## Prerequisites

Before you begin, ensure you have met the following requirements:
* You have installed the latest version of [Node.js and npm](https://nodejs.org/)

## Installation

To install the project dependencies, run the following command in your terminal:

```bash
npm install
```

## Usage

To run the project in development mode (with automatic restarts on file changes), use:

```bash
npm run dev
```

To build the project for production, use:

```bash
npm run build
```

To run the compiled JavaScript code (after building), use:

```bash
npm start
```

## Scripts

The `package.json` file contains the following scripts:

* `start`: Runs the compiled JavaScript output from the `dist` folder.
* `build`: Compiles the TypeScript code into JavaScript and outputs it to the `dist` folder.
* `dev`: Starts the development server using `ts-node-dev`, which automatically restarts the server on file changes.

## Technologies Used

* [Node.js](https://nodejs.org/) - JavaScript runtime environment
* [TypeScript](https://www.typescriptlang.org/) - Superset of JavaScript that adds static typing
* [ts-node-dev](https://github.com/wclr/ts-node-dev) - Development tool for TypeScript projects that restarts the server on file changes

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.
