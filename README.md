# X Clone UI - Social Media Interface Components

A comprehensive collection of reusable UI components designed for building social media platforms, inspired by X (formerly Twitter) design patterns.

## Features

- 🎨 **Modern UI Components** - Ready-to-use social media interface elements
- 📱 **Responsive Design** - Optimized for all device sizes
- ♿ **Accessible** - Built with accessibility best practices
- 🎯 **Customizable** - Easy theming and styling options
- ⚡ **Performance** - Optimized for fast loading
- 🔧 **TypeScript** - Full type safety

## Components Included

### Core Components
- Post cards and timelines
- User profile components
- Navigation and sidebar elements
- Comment and interaction components

### Form Elements
- Post creation forms
- Comment input fields
- Search and filter components

### Interactive Elements
- Like, retweet, and share buttons
- Follow/unfollow functionality
- Notification components

### Layout Components
- Feed layouts
- Profile page layouts
- Modal and overlay components

## Tech Stack

- **React** - Component framework
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first styling
- **Next.js** - Framework integration
- **Lucide Icons** - Icon library

## Installation

```bash
npm install x-clone-ui
# or
yarn add x-clone-ui
# or
pnpm add x-clone-ui
```

## Usage

```tsx
import { PostCard, UserProfile, Timeline } from 'x-clone-ui'

export default function SocialFeed() {
  return (
    <div>
      <UserProfile user={currentUser} />
      <Timeline posts={posts} />
    </div>
  )
}
```

## Development

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn or pnpm

### Setup

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Build for production:
```bash
npm run build
```

## Customization

All components are highly customizable through:
- CSS classes and Tailwind utilities
- Component props and variants
- Theme configuration
- Custom styling overrides

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests to improve the component library.

## License

MIT License