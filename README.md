# Emmanuel Abimbola Portfolio

A personal Information Technology portfolio with a built-in AI-style assistant named **Mannie**.

## Features

- Responsive dark/off-black and mint-green portfolio
- About, skills, projects, and contact sections
- Mannie chat box
- Microphone voice input using the browser's Speech Recognition API when supported
- Spoken responses using the browser's Speech Synthesis API
- No API key is required for the included demo assistant

## Open the site

The simplest option is to open `index.html` in a browser.

For the best development workflow in VS Code, use a local server such as the Live Server extension.

## Voice permissions

When you click the microphone button, the browser may ask for microphone permission. Allow it if you want to use voice input.

Speech recognition support varies by browser. Speech output generally works in modern browsers.

## Turning Mannie into a real AI

The included Mannie is a front-end demo so that the project works immediately without exposing an API key in the browser.

If you want Mannie connected to a real AI model, add a server-side backend. Keep the API key on the server and never place it directly in `index.html` or client-side JavaScript.
