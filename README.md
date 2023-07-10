# Next.js YouTube Demo

This repository contains a simple app that serves as a demonstration of the fundamentals of Next.js, a popular React-based framework for building server-rendered and statically generated websites. The app showcases basic concepts and features of Next.js while integrating with the YouTube API.

## Features

- Home Page: Displays a list of YouTube videos fetched from the YouTube API.
- Video Detail Page: Shows detailed information about a selected video, including its title, description, and thumbnail.

## Technologies Used

- Next.js: The core framework used to build the application, providing server-side rendering, routing, and other Next.js features.
- React: The JavaScript library for building user interfaces.
- YouTube API: Used to fetch and display YouTube video data in the app.
- CSS Modules: Enables scoped and modular CSS styling for components.

## Getting Started

To run the app locally, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/nextjs-youtube-demo.git`
2. Install dependencies: `npm install`
3. Set up YouTube API credentials: Obtain an API key from the Google Developer Console and add it to the `.env.local` file. See `.env.example` for reference.
4. Start the development server: `npm run dev`
5. Open your browser and visit `http://localhost:3000` to see the app in action.

## Folder Structure

The repository follows a standard Next.js project structure, with the following notable directories and files:

- `/pages`: Contains the Next.js pages that define the app's routes and corresponding components.
- `/components`: Houses reusable React components used throughout the app.
- `/lib`: Holds utility functions or modules used for fetching YouTube API data.
- `/styles`: Contains CSS files and modules for styling the app.

## Contributing

Contributions to improve and expand the app are welcome! If you would like to contribute, please follow the guidelines outlined in the `CONTRIBUTING.md` file.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

The app is developed as a learning resource and inspired by various Next.js tutorials and documentation.

---

We hope this Next.js YouTube Demo provides a solid foundation for understanding Next.js concepts and encourages further exploration of the framework. Enjoy building your Next.js applications!
