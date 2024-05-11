# 0x16-api_advanced

## Overview

This project is a demonstration of using advanced features of an API to retrieve and manipulate data. It specifically focuses on leveraging the Reddit API to perform various tasks such as fetching posts, comments, and more.

## Features

- Retrieve posts from specified subreddits.
- Filter posts based on criteria such as upvotes, date, and more.
- Extract comments associated with posts.
- Perform advanced searches using Reddit's search functionality.
- Cache data for improved performance and reduced API calls.
- Handle authentication and rate limiting.

## Requirements

- Python 3.x
- PRAW (Python Reddit API Wrapper) library
- Reddit API credentials (client ID, client secret, user agent)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/0x16-api_advanced.git
    ```

2. Install dependencies:

    ```bash
    pip install praw
    ```

3. Obtain Reddit API credentials by creating an application on Reddit's website. You will need a client ID, client secret, and user agent.

4. Create a `config.py` file in the project directory with the following content:

    ```python
    CLIENT_ID = 'your_client_id'
    CLIENT_SECRET = 'your_client_secret'
    USER_AGENT = 'your_user_agent'
    ```

5. Run the application:

    ```bash
    python main.py
    ```

## Usage

The application provides a command-line interface (CLI) to interact with the Reddit API. Here are some example commands:

- Fetch top posts from a subreddit:

    ```bash
    python main.py top_posts --subreddit python --limit 10
    ```

- Search for posts containing specific keywords:

    ```bash
    python main.py search_posts --query "data science" --limit 5
    ```

- Get comments associated with a post:

    ```bash
    python main.py post_comments --post_id abc123
    ```

- Perform custom searches using Reddit's search syntax:

    ```bash
    python main.py custom_search --query "author:john title:'machine learning'"
    ```

For more options and detailed usage instructions, refer to the help menu:

```bash
python main.py --help
Contributions
Contributions are welcome! If you have any suggestions, improvements, or feature requests, feel free to open an issue or submit a pull request.
