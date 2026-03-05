# ID42 - Bicycle Messenger App

App for bicycle messengers and urban cyclists.

## Features

### Map & Location
- Show friends on map
- Get map coordinates
- List friends

### Safety
- Request help in emergencies

### Coming Soon
- Route planning

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/CaravanaCloud/id42.git
cd id42

# Install dependencies
npm install

# Start development server
npm run dev
```

### Environment Variables

Configure the following environment variables:

| Variable | Description | Required |
|----------|-------------|----------|
| `MAP_API_KEY` | API key for map services | Yes |
| `DATABASE_URL` | Connection string for database | Yes |
| `API_SECRET` | Secret for API authentication | Yes |

### Building

```bash
# Production build
npm run build
```

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /get-map | Get map coordinates |
| GET | /list-friends | List all friends |
| POST | /request-help | Request emergency help |

## Contributing

Contributions are welcome! Please read our contributing guidelines first.

## License

MIT
