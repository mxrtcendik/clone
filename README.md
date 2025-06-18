# Clone

Clone is an open-source clone of T3 Chat.

## Features

- Modern, responsive UI built with Tailwind CSS
- Multiple AI provider support (OpenAI, Anthropic, Google, Mistral, and more)
- Real-time chat functionality
- Markdown support for messages
- Dark/Light theme support
- Type-safe development with TypeScript

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (v18 or higher)
- npm
- Git

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/mxrtcendik/clone.git
cd clone
```

2. Install dependencies:

```bash
npm install
```

3. Set up environment variables:
   Create a `.env.local` file in the root directory and add your necessary API keys and URLs:

```env
OPENAI_API_KEY=sk-your_openai_api_key
MISTRAL_API_KEY=your_mistral_api_key
GOOGLE_GENERATIVE_AI_API_KEY=your_gemini_api_key
ANTHROPIC_API_KEY=your_anthropic_api_key
XAI_API_KEY=your_xai_api_key
PERPLEXITY_API_KEY=your_perplexity_api_key
OPENROUTER_API_KEY=your_openrouter_api_key
NEXT_PUBLIC_SUPABASE_URL=your_supabase_project_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
SUPABASE_SERVICE_ROLE=your_supabase_service_role_key
CSRF_SECRET=your_32_character_random_string
ENCRYPTION_KEY=your_generated_base64_encryption_key
```

4. Run the development server:

```bash
npm run dev
```

The application will be available at `http://localhost:3000`

## Available Scripts

- `npm run dev` - Start the development server with Turbopack
- `npm run build` - Build the application for production
- `npm run start` - Start the production server
- `npm run lint` - Run ESLint to check code quality
- `npm run type-check` - Run TypeScript type checking

## Tech Stack

- **Framework**: Next.js 15
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: Radix UI
- **State Management**: Zustand
- **Data Fetching**: TanStack Query
- **AI Integration**: Multiple AI SDK providers
- **Code Quality**: ESLint, Prettier

## Project Structure

```
clone/
├── app/              # Next.js app directory
├── components/       # React components
├── lib/             # Utility functions and configurations
├── public/          # Static assets
├── utils/           # Helper functions
└── ...config files
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.
