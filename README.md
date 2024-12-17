# Fractal Generator

A web-based application for generating fractal images using recursive mathematical formulas.

## Project Structure

```
fractal-generator/
├── src/                  
│   ├── fractal.ts
│   ├── logger.ts
│   ├── render.ts
│   ├── server.ts
│   └── utils.ts
├── static/
│   ├── index.html
│   └── style.css
├── tsconfig.json
└── package.json
```


## Features

- Custom Formulas: Generate fractals using user-defined mathematical formulas (e.g., z = z^2 + c).
- Adjustable Recursion Depth: Control the level of detail by specifying the recursion depth. 
- Customizable Colors: Choose a base color for rendering and create beautiful gradient-based visualizations. 
- Interactive UI: Easily adjust settings via an intuitive interface. 
- Optimized Rendering: Smooth rendering for fractals, including large canvases and high recursion depths.

## Requirements
- Node.js (version 20)

## How to start

#### 1. Install dependencies:
- install npm modules, run `npm install`

#### 2. Run the application:
- run `npm run build`
- run `npm run start`

#### 3. Open your browser and navigate to:
- http://localhost:8080
