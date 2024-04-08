## Infinite Scrolling & Filter

This project implements infinite scrolling, which is a way to paginate through content. It fetches posts from the Json placeholder fake REST API and displays them in batches as the user scrolls.

## Project Specifications

- Create UI & custom CSS loader animation
- Fetch initial posts from API and display
- Scroll down, show loader and fetch next set of posts
- Add filtering for fetched posts

## Project Description

The project is a web application that implements infinite scrolling functionality for displaying posts. It fetches posts from the Json placeholder fake REST API and dynamically loads them as the user scrolls. The application also includes a filter feature that allows users to search for specific posts based on keywords. The UI is styled using CSS and includes a loader animation. The project is built using JavaScript. Open the application in a browser and scroll down to load more posts. Use the search bar to filter the displayed posts.

### Features

- Fetches five posts initially and dynamically loads more as the user scrolls.
- Implements a filter functionality to search for specific posts based on keywords.
- Uses CSS to style the UI and create a loader animation.

### Installation

1. Clone the repository: `git clone https://github.com/WorananH/your-repo.git`
2. Navigate to the project directory: `cd your-repo`
3. Clone the repository to your local machine.

### API

This project uses the [Json placeholder fake REST API](https://jsonplaceholder.typicode.com/) to fetch posts. You can make different types of requests to different resources such as posts, todos, or users.

To fetch posts, use the following endpoint: `https://jsonplaceholder.typicode.com/posts`

You can add parameters to the URL to specify the number of posts to fetch and the page number. For example, to fetch five posts from the second page, use: `https://jsonplaceholder.typicode.com/posts?_limit=5&_page=2`

### Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
