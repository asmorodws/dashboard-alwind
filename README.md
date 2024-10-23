
# Dashboard with Alpine.js and Tailwind CSS

A modern responsive dashboard layout built with Alpine.js and Tailwind CSS, featuring a dynamic theme switcher.

## Features

- Responsive sidebar navigation
- Dark/Light theme switcher
- Clean and modern UI design
- Built with Alpine.js for interactivity
- Styled using Tailwind CSS utility classes

## Theme Switcher

The theme switcher allows users to toggle between light and dark modes. It uses Alpine.js for state management and Tailwind's dark mode classes.


<div x-data="{ darkMode: false }">
  <button @click="darkMode = !darkMode" 
          :class="{ 'bg-gray-800': darkMode, 'bg-gray-200': !darkMode }">
    Toggle Theme
  </button>
</div>


## Setup

1. Include required dependencies:

<script src="//unpkg.com/alpinejs" defer></script>
<link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">


2. Add the following to your tailwind.config.js:

module.exports = {
  darkMode: 'class',
  // ... rest of your config
}


## Layout Structure

- Responsive sidebar
- Top navigation bar
- Main content area
- Footer section

## Components

- Navigation menu
- User profile section
- Statistics cards
- Data tables
- Charts and graphs
- Theme toggle button

## Usage

1. Clone the repository
2. Install dependencies
3. Run the development server
4. Customize the components as needed

## Customization

The dashboard can be customized by:
- Modifying Tailwind CSS classes
- Adjusting Alpine.js functionality
- Adding new components
- Customizing color schemes
- Modifying layout structure

