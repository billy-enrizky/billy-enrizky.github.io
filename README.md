<<<<<<< HEAD
# OpenBrowser Frontend

A modern chat interface for OpenBrowser AI, similar to Manus AI.

## Features

- Real-time chat interface with WebSocket communication
- Sidebar navigation with projects and task history
- Support for both Browser Agent and Code Agent
- Screenshot display for browser automation tasks
- Responsive design with dark theme

## Tech Stack

- **Next.js 16** - React framework with App Router
- **TypeScript** - Type safety
- **Tailwind CSS 4** - Styling
- **Framer Motion** - Animations
- **Zustand** - State management
- **Lucide React** - Icons

## Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Export static files for GitHub Pages
npm run export
```

## Deployment

This frontend is deployed to GitHub Pages at [openbrowser.me](https://openbrowser.me).

### GitHub Pages Deployment

1. Build and export static files:
   ```bash
   npm run export
   ```

2. The `out/` directory contains the static files

3. Push to the `gh-pages` branch or configure GitHub Actions

### Environment Variables

Create a `.env.local` file:

```env
NEXT_PUBLIC_API_URL=https://api.openbrowser.me
NEXT_PUBLIC_WS_URL=wss://api.openbrowser.me/ws
```

For local development:
```env
NEXT_PUBLIC_API_URL=http://localhost:8000
NEXT_PUBLIC_WS_URL=ws://localhost:8000/ws
```

## Project Structure

```
src/
  app/
    globals.css       # Global styles
    layout.tsx        # Root layout
    page.tsx          # Main chat page
  components/
    chat/
      ChatInput.tsx   # Message input with quick actions
      ChatMessage.tsx # Individual message display
      ChatMessages.tsx # Message list container
    layout/
      Header.tsx      # Top navigation bar
      Sidebar.tsx     # Left sidebar navigation
    ui/
      Button.tsx      # Button component
      Input.tsx       # Input component
      Textarea.tsx    # Textarea component
  hooks/
    useWebSocket.ts   # WebSocket connection hook
  lib/
    config.ts         # Configuration constants
    utils.ts          # Utility functions
  store/
    index.ts          # Zustand store
  types/
    index.ts          # TypeScript types
```

## Connecting to Backend

The frontend connects to the OpenBrowser backend via WebSocket for real-time communication.

1. Start the backend server (see `/backend/README.md`)
2. Update environment variables to point to your backend
3. The WebSocket connection will be established automatically

## License

MIT

## Deployment

This frontend is deployed to GitHub Pages at [openbrowser.me](https://openbrowser.me).

### GitHub Pages Deployment

1. Build and export static files:
   ```bash
   npm run export
   ```

2. The `out/` directory contains the static files

3. Push to the `gh-pages` branch or configure GitHub Actions

### Environment Variables

Create a `.env.local` file:

```env
NEXT_PUBLIC_API_URL=https://api.openbrowser.me
NEXT_PUBLIC_WS_URL=wss://api.openbrowser.me/ws
```

For local development:
```env
NEXT_PUBLIC_API_URL=http://localhost:8000
NEXT_PUBLIC_WS_URL=ws://localhost:8000/ws
```

## Project Structure

```
src/
  app/
    globals.css       # Global styles
    layout.tsx        # Root layout
    page.tsx          # Main chat page
  components/
    chat/
      ChatInput.tsx   # Message input with quick actions
      ChatMessage.tsx # Individual message display
      ChatMessages.tsx # Message list container
    layout/
      Header.tsx      # Top navigation bar
      Sidebar.tsx     # Left sidebar navigation
    ui/
      Button.tsx      # Button component
      Input.tsx       # Input component
      Textarea.tsx    # Textarea component
  hooks/
    useWebSocket.ts   # WebSocket connection hook
  lib/
    config.ts         # Configuration constants
    utils.ts          # Utility functions
  store/
    index.ts          # Zustand store
  types/
    index.ts          # TypeScript types
```

## Connecting to Backend

The frontend connects to the OpenBrowser backend via WebSocket for real-time communication.

1. Start the backend server (see `/backend/README.md`)
2. Update environment variables to point to your backend
3. The WebSocket connection will be established automatically

## License

MIT
=======
# billy-enrizky.github.io
>>>>>>> ea5a3a07c0dce3eb0c6fe0c9708789eaca070ef4
