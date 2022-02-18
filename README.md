  "scripts": {
    "start": "node server/index.js",
    "dev": "nodemon server/index.js",
    "build": "cd client && npm install && npm run build",
    "start:dev": "nodemon --watch './**/*.ts' --exec ts-node src/index.ts"
  },