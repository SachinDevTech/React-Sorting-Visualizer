# Sorting Algorithm Visualizer

This project is a React-based sorting algorithm visualizer that allows users to observe the functioning of various sorting algorithms in real-time. Users can adjust settings to change the sorting speed and array size, providing an interactive and educational experience with the algorithms.

## Features

- **Algorithms Implemented**:
  - Bubble Sort
  - Selection Sort
  - Insertion Sort
  - Merge Sort
  - Quick Sort
  - Heap Sort
- **Customizable Settings**:
  - Adjust array size
  - Adjust sorting speed
- **Interactive Visualization**:
  - Visual representation of sorting steps with animated bars
  - Color-coded to highlight sorting process

## Project Structure

- **src/**
  - `algorithms/`: Contains JavaScript files for each sorting algorithm.
    - `bubblesort.js`
    - `heapsort.js`
    - `insertion.js`
    - `mergesort.js`
    - `quicksort.js`
    - `selectionsort.js`
    - `swap.js`: Utility function for swapping elements.
  - `Icons/`: Contains the `GithubIcon` component for the GitHub link.
  - `SortingVisualizer/`: Contains the main sorting visualizer component files.
    - `colorCodes.js`: Defines color codes for different parts of the visualization.
  - `App.css`, `App.jsx`: Main application styling and layout.
  - `index.css`, `index.jsx`: Entry point for the React application.
- **public/**: Contains the `index.html` file and other assets.
- **dist/** and **build/**: Output directories for the application bundle.
- **site.webmanifest**: Manifest file for web app configuration.

## Installation and Setup

## Clone the Repository
```bash
git clone https://github.com/SachinDevTech/React-Sorting-Visualizer.git
cd React-Sorting-Visualizer
npm install
npm run dev
```

## Usage
- **Select Algorithm**: Use the dropdown to select a sorting algorithm.
- **Adjust Settings**: Modify the array size and sorting speed using the sliders.
- **Sort**: Click the "Sort" button to start the sorting animation.
- **Reset**: Click "Reset" to generate a new random array.

## Technologies Used
- **React**: For creating the user interface.
- **JavaScript**: For implementing the sorting algorithms.
- **CSS**: For styling the visualizer.


## View the Deployed Project
[Click here to view the deployed project](https://react-sorting-visualizer-sachindevtech.vercel.app/)
