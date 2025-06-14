# Yakoot

A modern web application built with Next.js and Supabase.

## Tech Stack

- **Framework:** Next.js 14
- **Language:** TypeScript
- **Database:** Supabase
- **Styling:** Tailwind CSS
- **Authentication:** Supabase Auth
- **Deployment:** Vercel

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/S3YLAT3R/yakoot.git
cd yakoot
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
Create a `.env.local` file in the root directory with the following variables:
```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
```

4. Run the development server:
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

```
yakoot/
├── app/                 # Next.js 14 app directory
├── components/         # Reusable components
├── lib/               # Utility functions and configurations
├── public/            # Static assets
├── styles/            # Global styles
└── types/             # TypeScript type definitions
```

## Features

- [ ] Authentication
- [ ] Database Integration
- [ ] Real-time Updates
- [ ] Responsive Design

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
