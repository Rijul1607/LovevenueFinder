
# Love Venue Finder

A modern web application for discovering and booking wedding and event venues, built with React, TypeScript, and Supabase.

## Features

- Browse and search for venues with detailed filters
- View venue details with photos, descriptions, and availability
- Book venues with a streamlined booking process
- User authentication with email verification
- Wishlist functionality to save your favorite venues
- Review system for venues with star ratings

## Technologies Used

- Vite
- TypeScript
- React
- React Router
- Supabase for backend and authentication
- shadcn-ui component library
- Tailwind CSS for styling
- React Hook Form for form handling
- Zod for schema validation

## Getting Started

Follow these steps to set up the project locally:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd love-venue-finder

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

## Environment Variables

Create a `.env` file in the root directory with the following variables:

```
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## Deployment

The site can be built for production using:

```sh
npm run build
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
