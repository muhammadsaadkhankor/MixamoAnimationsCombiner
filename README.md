# Overview

This project integrates Ready Player Me and Avaturn avatars with custom animations (e.g., flying idle, walking, running) downloaded from Mixamo. The animations are applied to the avatars with different skeleton structures using JavaScript and TypeScript. The project leverages Three.js for 3D rendering and animation handling.

## Features

- Integration of avatars from Ready Player Me and Avaturn.
- Application of custom animations to avatars.
- Support for animations like flying idle, walking, and running.
- Handling skeleton differences between avatars.
- Built with JavaScript, TypeScript, and Three.js.

## Prerequisites

Ensure you have the following installed on your system:

- Node.js (version 14 or later recommended)
- npm (comes with Node.js)
- A modern web browser (e.g., Chrome, Firefox)

## Setup

Clone the repository to your local machine:

```bash
git clone [<repository-url>](https://github.com/muhammadsaadkhankor/MixamoAnimationsCombiner.git)
```

Navigate to the project directory:

```bash
cd MixamoAnimationsCombiner
```

Install dependencies:

```bash
npm install
```

## Running the Project

To start the development server:

```bash
npm run dev
```

The application will be accessible at [http://localhost:3000/](http://localhost:3000/) or another port specified in your terminal.

## How to Use

1. Open the application in your browser.
2. Choose an avatar (Ready Player Me or Avaturn) to load.
3. Select animations from the provided list (e.g., flying idle, walking, running).
4. The selected animations will play on the loaded avatar in real-time.

## Folder Structure

- `src/`: Contains the source code, including TypeScript files and Three.js integration.
- `public/`: Static assets such as textures and models.
- `assets/`: Mixamo animations and avatar files.
- `dist/`: Build output directory.

## Key Technologies

- **Three.js**: For rendering 3D models and handling animations.
- **TypeScript**: For robust type-checking and development.
- **Mixamo**: Source of custom animations.

## Customization

- Replace existing avatars or animations by adding new models and animation files to the `assets/` directory.
- Update the animation logic in the source code to handle new skeleton structures or behaviors.

## Troubleshooting

- Ensure all dependencies are installed by running `npm install`.
- Check the console for any runtime errors.
- Verify that avatar and animation files are correctly placed in the `assets/` directory.

## License

This project is licensed under [Your License Here].

## Acknowledgments

- **Ready Player Me** for avatar generation.
- **Avaturn** for additional avatar options.
- **Mixamo** for providing animations.
- **Three.js** for the 3D rendering framework.
