# Tailwind CSS Project

This project is set up to use Tailwind CSS for styling. Below are the instructions for setting up and using the project.

## Project Structure

```
tailwind-css-project
├── src
│   ├── input.css        # Input file for Tailwind CSS
│   └── output.css       # Compiled output file from Tailwind CSS
├── tailwind.config.js    # Configuration file for Tailwind CSS
├── package.json          # npm configuration file
└── README.md             # Project documentation
```

## Setup Instructions

1. **Clone the repository** (if applicable):
   ```bash
   git clone <repository-url>
   cd tailwind-css-project
   ```

2. **Install dependencies**:
   Make sure you have Node.js installed. Then run:
   ```bash
   npm install
   ```

3. **Configure Tailwind CSS**:
   The `tailwind.config.js` file is already set up to scan your HTML and JavaScript files for class names.

4. **Create your CSS file**:
   The `src/input.css` file imports Tailwind's base, components, and utilities styles. You can add custom styles here as needed.

5. **Build your CSS**:
   Use the Tailwind CLI tool to generate the final CSS file:
   ```bash
   npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
   ```

## Usage

- Include the compiled CSS file (`src/output.css`) in your HTML files to apply Tailwind styles.
- Use Tailwind's utility classes in your HTML to style your components.

## License

This project is licensed under the MIT License.