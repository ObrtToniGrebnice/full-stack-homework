# Multi-Tab Workspace Interface

A sophisticated real-time collaboration platform built with Next.js and native BroadcastChannel API that enables seamless cross-tab synchronization of user presence, messaging, and shared data.

## 🎯 Demo

Watch the application in action:

https://github.com/user-attachments/assets/3495f9f0-2255-4c2d-9441-91c71d6c9a46

## ✨ Features

### Core Functionality
- **Real-time Cross-Tab Synchronization**: Seamless data synchronization across multiple browser tabs
- **Participant Status Tracking**: Live user presence monitoring with connection state indicators
- **Synchronized Messaging**: Real-time chat with message expiration and deletion capabilities
- **Numerical Operations**: Shared counter with conflict resolution and operation history

### Technical Excellence
- **Native Web APIs**: Built with BroadcastChannel API for cross-tab communication
- **TypeScript**: Full type safety and modern development experience
- **Responsive Design**: Mobile-first approach with professional terminal aesthetic
- **Performance Optimized**: Efficient state management and minimal re-renders

## 🚀 Installation

### Prerequisites
- Node.js 18+ 
- npm, yarn, or pnpm package manager

### Quick Start

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd full-stack-homework
   ```

2. **Install dependencies**
   ```bash
   pnpm install
   ```

3. **Run the development server**
   ```bash
   pnpm dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

5. **Test cross-tab functionality**
   - Open the application in multiple browser tabs
   - Watch real-time synchronization in action
   - Send messages, update the counter, and observe instant updates across tabs

## 🏗️ Project Structure

```
app/
├── components/                 # React components
│   ├── MultiTabWorkspaceInterface.tsx    # Main dashboard
│   ├── UserPresence.tsx                  # Participant status display
│   ├── SharedCounter.tsx                 # Synchronized counter
│   ├── RealTimeChat.tsx                  # Messaging interface
│   └── ui/                              # Reusable UI components
│       ├── MessageBox.tsx               # Message display
│       └── Avatar.tsx                   # User profile pictures
├── hooks/                     # Custom React hooks
│   ├── useCollaborativeSession.ts       # Main session management
│   ├── useChat.ts                        # Messaging functionality
│   ├── useUserPresence.ts               # User status tracking
│   ├── useSharedCounter.ts              # Counter synchronization
│   ├── useBroadcastChannel.ts           # Cross-tab communication
│   └── useStateRehydration.ts           # State recovery
├── types/                     # TypeScript type definitions
├── utils/                     # Utility functions
├── constants/                 # Application constants
└── globals.css               # Global styles and animations
```

## 🔧 Available Scripts

- `pnpm dev` - Start development server
- `pnpm build` - Build for production
- `pnpm start` - Start production server
- `pnpm lint` - Run ESLint
- `pnpm type-check` - Run TypeScript type checking

## 🌐 Cross-Tab Communication

The application uses the native BroadcastChannel API to enable real-time synchronization across browser tabs:

- **User Presence**: Live status updates and typing indicators
- **Messaging**: Instant message delivery and deletion across tabs
- **Counter Operations**: Synchronized increment/decrement with conflict resolution
- **State Recovery**: Automatic data synchronization for new tabs

## 🎨 UI/UX Features

- **Terminal Aesthetic**: Professional developer workspace appearance
- **Dark Theme**: Slate color palette with cyan accents
- **Real-time Indicators**: Live status updates and system monitoring
- **Responsive Design**: Optimized for all device sizes
- **Keyboard Navigation**: Full keyboard support for accessibility

## 📱 Browser Support

- **Modern Browsers**: Chrome 66+, Firefox 76+, Safari 15.4+, Edge 79+
- **Required APIs**: BroadcastChannel API support
- **Mobile**: Responsive design for mobile devices

## 🚀 Deployment

### Vercel (Recommended)
1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy automatically on every push

### Other Platforms
```bash
# Build the application
pnpm build

# Start production server
pnpm start
```

## 🔒 Security Features

- **Input Sanitization**: XSS protection for user inputs
- **Type Safety**: Full TypeScript coverage

- **API Validation**: Robust data validation and error handling
