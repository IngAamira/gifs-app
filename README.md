# Gifs App

This is an Angular application that allows users to search and view gifs using the Giphy API.

## Features

- **Gif Search:** Enables users to search for gifs using keywords.
- **Tag History:** Displays a history of previous search tags.
- **Lazy Image Loading:** Uses the `LazyImageComponent` to lazily load images when they become visible in the viewport.

## Project Structure

The project is organized into various components and services:

- **GifsService:** A service that interacts with the Giphy API to perform gif searches and manage tag history.

- **SearchBoxComponent:** A search bar component that utilizes the `GifsService` to perform searches when the "Enter" key is pressed.

- **CardListComponent:** A component that displays a list of gifs and uses the `GifsService` to fetch the gif list.

- **CardComponent:** An individual component that visually represents a gif.

- **SidebarComponent:** A sidebar component that shows a history of tags and allows searches based on those tags.

- **LazyImageComponent:** A component that lazily loads images when they become visible in the viewport.

## Development

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js installed
- Angular v17.0.0
- Angular CLI installed

## Contributing

If you want to contribute to this project, follow these steps:

1. Fork the repository
2. Create a branch for your feature: `git checkout -b feature/new-feature`
3. Make your changes and commit: `git commit -m "Add new feature"`
4. Push your changes: `git push origin feature/new-feature`
5. Open a Pull Request on GitHub

## Installation

1. Clone this repository: `git clone https://github.com/IngAamira/gifs-app.git`
2. Navigate to the directory: `cd gifs-app`
3. Install dependencies: `npm install`
4. Start the application: `ng serve`

## Usage

Include any additional information on how to use the application, command-line arguments, or configuration options.

## Troubleshooting

Include common issues users might encounter and their solutions.

## FAQ

Answer frequently asked questions to help users better understand the project.
