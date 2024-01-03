# Blog Website

This is a simple blog website built with the Express framework and MongoDB as the database.

## Features

- **User-friendly Interface:** Clean and intuitive design for a pleasant user experience.
- **Create and Publish:** Create and publish your blog posts easily.
- **Read and Comment:** Read posts from other users and leave comments.

## Technologies Used

- **Express:** Fast, unopinionated, minimalist web framework for Node.js.
- **MongoDB:** A NoSQL database for storing blog posts and user data.
- **EJS:** Embedded JavaScript templates for rendering dynamic content.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.
- MongoDB installed locally or a MongoDB Atlas account for a cloud database.

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/KshitijTiwari0/Blog.git
    ```

2. Navigate to the project directory:

    ```bash
    cd blog-website
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Set up environment variables:

    Create a `.env` file in the root directory with the following content:

    ```env
    PORT=3000
    MONGODB_URI=your-mongodb-uri
    ```

    Replace `your-mongodb-uri` with the connection string for your MongoDB database.

5. Start the server:

    ```bash
    npm start
    ```

6. Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to view the blog website.

## Contributing

If you would like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -m 'Add your feature'`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
