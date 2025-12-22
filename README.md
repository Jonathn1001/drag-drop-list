# Drag & Drop Project

A TypeScript-based project management application with drag-and-drop functionality. This project demonstrates advanced TypeScript concepts including decorators, generics, interfaces, and object-oriented programming principles.

## Features

- **Project Management**: Create new projects with title, description, and team size
- **Drag & Drop Interface**: Move projects between "Active" and "Finished" states
- **Form Validation**: Input validation with custom validation logic
- **State Management**: Centralized state management using the Singleton pattern
- **Responsive Design**: Clean, modern UI with CSS styling

## Project Structure

- [`src/app.ts`](src/app.ts) - Main TypeScript application code
- [`index.html`](index.html) - HTML template with project templates
- [`app.css`](app.css) - Styling for the application
- [`tsconfig.json`](tsconfig.json) - TypeScript configuration with decorator support

## Key TypeScript Concepts Demonstrated

- **Decorators**: Custom `@autobind` decorator for method binding
- **Interfaces**: `Draggable` and `DragTarget` for drag-and-drop functionality
- **Generics**: Generic `State<T>` and `Component<T, U>` classes
- **Abstract Classes**: Base `Component` class for shared functionality
- **Enums**: `ProjectStatus` for project state management
- **Validation**: Type-safe input validation system

## Getting Started

1. Install dependencies:

   ```bash
   npm install
   ```

2. Compile TypeScript:

   ```bash
   tsc
   ```

3. Start the development server:
   ```bash
   npm start
   ```

## Usage

1. Fill out the form to create a new project
2. Projects appear in the "Active Projects" section
3. Drag projects to the "Finished Projects" section to mark them complete
4. Projects can be moved back and forth between sections

## Technologies Used

- TypeScript
- HTML5 (Templates, Drag & Drop API)
- CSS3
- Lite Server (for development)
