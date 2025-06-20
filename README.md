# PDF Extraction Backend

This backend server accepts PDF uploads, extracts the text using `pdf-parse`, and returns the extracted text as JSON. It is designed to work with your React Native app for AI-powered PDF summarization.

## Setup

1. Install dependencies:
   ```sh
   npm install
   ```

2. Start the server:
   ```sh
   npm start
   ```

The server will run on [http://localhost:3000](http://localhost:3000).

## Endpoint

### POST `/extract-text`
- Accepts: `multipart/form-data` with a `pdf` file field.
- Returns: `{ extractedText: string }`

## Notes
- Make sure your mobile app can access this server. If testing on a real device, use your computer's local IP address instead of `localhost` in the app code. #   a i s u m m a r y B a c k e n d  
 #   a i s u m m a r y B a c k e n d  
 