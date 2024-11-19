# Instagram Clone

A beautiful, responsive Instagram clone built with React, TypeScript, and Tailwind CSS. This project demonstrates modern web development practices with a focus on UI/UX and component reusability.

![Instagram Clone](https://images.unsplash.com/photo-1682687220742-aba13b6e50ba?auto=format&fit=crop&w=600&q=80)

## Features

- 📱 Fully responsive design
- 💫 Stories with gradient borders
- ❤️ Like and save posts
- 💬 Comments section
- 🔍 Search functionality
- 👥 User suggestions
- 🎨 Modern UI with Tailwind CSS
- 📦 Component-based architecture

## Tech Stack

- React 18
- TypeScript
- Tailwind CSS
- Lucide Icons
- Vite

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/instagram-clone.git
cd instagram-clone
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and visit `http://localhost:5173`

## Project Structure

```
src/
├── components/
│   ├── Header.tsx
│   ├── Post.tsx
│   ├── Stories.tsx
│   ├── Suggestions.tsx
│   └── ui/
│       └── Link.tsx
├── App.tsx
├── main.tsx
└── index.css
```

## Components

- `Header`: Navigation bar with search and action buttons
- `Stories`: Horizontal scrollable stories section
- `Post`: Individual post component with like/comment functionality
- `Suggestions`: Sidebar with suggested users
- `Link`: Reusable link component with hover effects

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Design inspired by Instagram
- Icons from [Lucide](https://lucide.dev)
- Images from [Unsplash](https://unsplash.com)
