# Blog Application

This is a simple blog application built with Node.js and Express.js, utilizing MongoDB for data storage. The application follows the MVC (Model-View-Controller) architecture to manage the data flow.

## Features

- **User Comments:** Users can comment on posts using the commentsModel.
- **Post Likes:** Users can like and unlike posts using the likeModel.
- **Post Creation:** Users can create new posts using the postModel.
- **Post Retrieval:** Users can retrieve all posts using the postModel.

## Installation

1. Clone the repository: `git clone https://github.com/your-username/blog-application.git`
2. Install dependencies: `npm install`
3. Set up MongoDB, POSTMAN: Ensure MongoDB and POSTMAN are installed and running on your machine.
4. Start the server: `node server.js`

## Usage

1. Use Postman or any other API testing tool to test the endpoints.
2. Endpoint for creating comments: `POST /comments/create`
3. Endpoint for creating posts: `POST /posts/create`
4. Endpoint for retrieving all posts: `GET /posts`
5. Endpoint for liking a post: `POST /likes/like`
6. Endpoint for unliking a post: `POST /likes/unlike`

## Technologies Used

- Node.js
- Express.js
- MongoDB
- POSTMAN