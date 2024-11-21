# Ecole

Ecole is an app that allows users to sign in with ZAPT and interact with jokes and additional features.

## User Journeys

### 1. Sign In

1. Open the app, and you are presented with a sign-in page.
2. Click on "Sign in with ZAPT".
3. You can sign in using magic link or social providers like Google, Facebook, or Apple.
4. Upon successful sign-in, you are redirected to the home page.

### 2. View and Add Jokes

1. On the home page, you can see a list of your saved jokes.
2. To add a new joke, fill in the "Setup" and "Punchline" fields.
3. Click "Save Joke" to save it to your list.
4. Your new joke will appear in the joke list.

### 3. Generate Joke

1. Click on "Generate Joke" to have the app generate a new joke for you.
2. The generated joke will be filled into the "Setup" and "Punchline" fields.
3. You can edit the joke if desired.
4. Click "Save Joke" to add it to your joke list.

### 4. Additional Features

- **Generate Image**: Click this button to generate a funny image related to jokes.
- **Text to Speech**: Convert your joke into audio.
- **Generate Markdown**: Generate a funny story in markdown format.

### 5. Sign Out

1. Click on the "Sign Out" button on the top right corner to sign out of the app.

## External APIs Used

- **ZAPT**: For authentication and event handling.
- **OpenAI API**: Used for joke generation, image generation, and text-to-speech features.

## Environment Variables

- `VITE_PUBLIC_APP_ID`: The app ID for ZAPT integration.
- `VITE_PUBLIC_SENTRY_DSN`: Sentry DSN for error logging.
- `VITE_PUBLIC_APP_ENV`: Environment variable for Sentry.
