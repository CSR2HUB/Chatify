# Minimal Chatify React

This is a minimal version of the Chatify React frontend, extracted for standalone use and testing.

## Usage

1. Install dependencies:
   ```sh
   npm install
   ```
2. Start the development server:
   ```sh
   npm start
   ```
3. Build for production:
   ```sh
   npm run build
   ```
4. Run tests:
   ```sh
   npm test
   ```

## Docker

To run in Docker:
```sh
docker build -t chatify-minimal-react .
docker run -p 3000:3000 chatify-minimal-react
```
