# Expo Starter

A minimal [Expo](https://expo.dev) starter template with Expo Router and TypeScript.

## Getting Started

To run your Expo app locally, install dependencies:

```sh
npm install
```

Then start the development server:

```sh
npm run dev
```

Open the app on your device using the Expo Go app, or press `w` to open in web browser.

## Project Structure

This template includes:

- **Expo Router** for file-based routing with tabs navigation
- **TypeScript** for type safety
- **Lucide Icons** for React Native
- **Supabase** integration ready
- **React Native** components ready to use

```
app/
├── (tabs)/          # Tab-based navigation
│   ├── _layout.tsx  # Tab navigator configuration
│   └── index.tsx    # Home screen
├── _layout.tsx      # Root layout
├── index.tsx        # Redirects to tabs
└── +not-found.tsx   # 404 page
```

## Development

Edit files in the `app/` directory to start building your application.

To add more tabs, create new files in `app/(tabs)/` and register them in `app/(tabs)/_layout.tsx`.

## Scripts

- `npm run dev` - Start the development server
- `npm run build:web` - Build for web deployment
- `npm run lint` - Run ESLint
- `npm run typecheck` - Run TypeScript type checking
