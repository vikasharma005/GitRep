# GitHub User Explorer using Streamlit

<p align="center">
  <img src="https://github.com/vikasharma005/GitRep/blob/main/github-logo.png" alt="GitHub User Explorer" width="300">
</p>

GitHub User Explorer is a dynamic web application built with [Streamlit](https://streamlit.io/) that empowers users to effortlessly explore the GitHub activities and profile of any user. By simply entering a GitHub username, you can delve into a wealth of information about the user's repositories, contributions, issues, and more.

## Features

- **Profile Overview:** Get insights into the user's bio, location, and more.
- **Repositories:** Explore a comprehensive list of repositories and their details.
- **Recent Activity:** Discover the user's recent commits, issues, and pull requests.
- **Issues & Pull Requests:** Access a snapshot of the user's issue and pull request contributions.
- **Starred Repositories:** Find out which repositories the user has starred.
- **Followers & Following:** See the user's follower and following count.
- **Gists & Organizations:** Explore gists and organizations linked to the user.

## Getting Started

1. **Clone the Repository:**

   ```sh
   git clone https://github.com/your-username/github-user-explorer.git
   cd github-user-explorer
   ```

2. **Install Dependencies:**

   ```sh
   pip install -r requirements.txt
   ```

3. **Run the Streamlit App:**

   ```sh
   streamlit run app.py
   ```

4. **Access the App:**

   Open your web browser and visit the provided URL to start using the GitHub User Explorer.

## Usage

1. **Enter a GitHub Username:**

   In the sidebar, input the GitHub username you want to explore.

2. **Explore GitHub Activities:**

   Click on the different data categories to uncover the user's diverse GitHub interactions.

## Contributing

Contributions are more than welcome! Feel free to share your suggestions and improvements by opening an issue or submitting a pull request.

## License

This project is licensed under the MIT License. For detailed information, see the [LICENSE](LICENSE) file.

## Acknowledgments

- This project leverages the [github_connector](src/github_connector.py) library to communicate with the GitHub API.
- The interactive web interface is built using the powerful Streamlit framework.
