# Dev Detective

Dev Detective is a web application that fetches and displays GitHub user profiles based on the provided username. It allows users to view detailed information about a GitHub user, including their avatar, bio, repositories, followers, following, and more. The application also supports dark and light modes, and it saves the user's preferred theme in local storage.

## Features

- Fetch and display GitHub user profiles by username.
- Show user details like avatar, name, username, bio, repositories, followers, following, location, website, Twitter handle, and company.
- Toggle between dark and light modes.
- Save user's theme preference in local storage.
- Handle invalid GitHub usernames gracefully.

## Technologies Used

- HTML
- CSS
- JavaScript
- GitHub API

## Getting Started

### Prerequisites

- A web browser (Chrome, Firefox, Safari, etc.)

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/your-username/dev-detective.git
    ```

2. Navigate to the project directory:

    ```sh
    cd dev-detective
    ```

3. Open `index.html` in your web browser.

## Usage

1. Enter a GitHub username in the input field.
2. Click the "Search" button or press "Enter" to fetch and display the user profile.
3. Toggle between dark and light modes using the button in the top-right corner.
4. The user's theme preference is saved and applied on subsequent visits.

## Code Overview

### Main JavaScript Functions

- **Fetch User Data**: Fetches GitHub user data from the provided URL and updates the profile.
- **Update Profile**: Updates the user profile section with the fetched data.
- **Dark Mode Toggle**: Toggles between dark and light modes and saves the preference in local storage.

### Event Listeners

- **Search Button Click**: Fetches user data when the "Search" button is clicked.
- **Enter Key Press**: Fetches user data when the "Enter" key is pressed.
- **Dark Mode Button Click**: Toggles between dark and light modes.

## Dark Mode Preference

- Checks the user's device preference for dark mode and applies the corresponding theme.
- Saves and retrieves the user's theme preference from local storage.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [GitHub API](https://docs.github.com/en/rest)
- [FontAwesome](https://fontawesome.com/) for icons
