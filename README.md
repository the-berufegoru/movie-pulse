<div align="center">
  <h1>Movie Pulse | Restful API</h1>
  <p>
    Movie Pulse is a Restful API for managing movie listings with CRUD operations.
    It allows you to create, read, update, and delete movie records in a MongoDB database.
  </p>

  <br>
  <a href="https://github.com/the-berufegoru/movie-pulse/actions/workflows/snyk.yml">
    <img src="https://github.com/the-berufegoru/movie-pulse/actions/workflows/snyk.yml/badge.svg" />
  </a>
  <a href="https://github.com/the-berufegoru/movie-pulse/actions/workflows/codeql.yml">
    <img src="https://github.com/the-berufegoru/movie-pulse/actions/workflows/codeql.yml/badge.svg?branch=main" />
  </a>
  <img alt="GitHub package.json version (branch)" src="https://img.shields.io/github/package-json/v/the-berufegoru/movie-pulse/master">
  <img alt="GitHub repo size (branch)" src="https://img.shields.io/github/repo-size/the-berufegoru/movie-pulse">
  <br>
</div>

## Features

- Create, read, update, and delete movie listings
- Secure HTTPS communication with self-signed SSL certificates
- API documentation using Swagger UI Express
- Unit tests to ensure code quality and reliability

## Technologies Used

- Node.js
- Express.js
- MongoDB (via Mongoose)

## Getting Started

> To get started with Movie Pulse, follow these steps:

1. Clone the repository: `git clone https://github.com/the-berufegoru/movie-pulse.git`
2. Install the dependencies: `npm install`
3. Set up the environment variables: Create a `.env` file and populate it with the necessary configuration values. Refer to the `.env.example` file for the required variables.
4. Generate SSL certificates for HTTPS: Run the command `npm run generate-certs` to generate self-signed SSL certificates for HTTPS communication.
5. Build the project: `npm run build`
6. Start the server: `npm start`
7. The server should now be running on `https://localhost:3000`.

## API Documentation

The API endpoints and their usage are documented using Swagger UI Express.
Once the server is running, you can access the API documentation at `https://localhost:3000/docs`.

## Testing

To run the tests, use the following command: `npm test`

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the BSD 3-Clause License. See the [LICENSE](LICENSE) file for more information.

## Bugs and Issues

If you encounter any bugs or have any issues, please report them on the [GitHub Issues](https://github.com/the-berufegoru/movie-pulse/issues) page.

## Contact

For any further questions or inquiries, please contact the project maintainer:

- Name: Moobi Kabelo
- Email: [giftmoobi@gmail.com](mailto:giftmoobi@gmail.com)

Feel free to reach out if you have any questions or need assistance with using Movie Pulse.

## Contributors

This project is made possible by the following contributor:

- [Moobi Kabelo](https://github.com/the-berufegoru)

Thank you to all the contributors for their valuable contributions to the project!
