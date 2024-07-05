# Wedding Website

Welcome to our wedding website! This site is designed to share our pre-wedding pictures, provide details about the date and venue of our wedding, and offer a program of events. 

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Display of pre-wedding pictures
- Wedding date and venue information
- Program schedule of the wedding
- User-friendly and responsive design
- Firebase integration for real-time updates and authentication

## Technologies Used

- HTML
- CSS
- JavaScript
- Firebase (for authentication and real-time database)

## Setup

To set up the project locally, follow these steps:

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/wedding-website.git
    cd wedding-website
    ```

2. **Install dependencies:**

    This project uses Firebase, so you'll need to set up Firebase for the project. Follow the [Firebase setup guide](https://firebase.google.com/docs/web/setup) to create a Firebase project and obtain your configuration details.

3. **Configure Firebase:**

    Create a `firebaseConfig.js` file in the `src` directory and add your Firebase configuration:

    ```js
    // firebaseConfig.js
    const firebaseConfig = {
        apiKey: "your-api-key",
        authDomain: "your-auth-domain",
        projectId: "your-project-id",
        storageBucket: "your-storage-bucket",
        messagingSenderId: "your-messaging-sender-id",
        appId: "your-app-id"
    };
    export default firebaseConfig;
    ```

4. **Run the project:**

    Open `index.html` in your web browser to view the wedding website.

## Usage

- **Home Page:** Displays a welcome message and a slideshow of pre-wedding pictures.
- **Details Page:** Provides the date and venue of the wedding.
- **Program Page:** Lists the schedule of events for the wedding day.
- **Gallery Page:** Displays a gallery of pre-wedding pictures.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards and passes all tests.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for visiting our wedding website repository! We hope you find it useful and easy to use.
