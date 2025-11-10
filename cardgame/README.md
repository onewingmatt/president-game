# President Card Game

A web-based card game implementation with Flask and SocketIO.

## Features

- Real-time multiplayer gameplay using WebSockets
- Customizable game options (2s wild, Black 3s wild, Jack of Diamonds wild, max run length)
- CPU opponents with intelligent card play
- Game state persistence
- Responsive web design
- Support for 2-4 players

## Deployment on Fly.io

This app is configured for deployment on Fly.io. To deploy:

1. Create account at https://fly.io
2. Install flyctl CLI
3. Run `flyctl launch` in your project directory
4. Deploy with `flyctl deploy`

## Local Development

```bash
pip install -r requirements.txt
python app.py
```

Visit http://localhost:5000

## Game Rules

- President Card Game with customizable wild card rules
- 2-4 players (mix of human and CPU)
- Adjustable run lengths (3-5 cards)
- Customizable wild card options via options menu
