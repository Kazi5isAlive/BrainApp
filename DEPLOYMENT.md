# Full Audio Frequency Tuner - GitHub Deployment

This is the complete, sophisticated audio frequency tuner with all features intact.

## Features Included
- **Binaural Beats Generator** - All 5 frequency ranges (Delta, Theta, Alpha, Beta, Gamma)
- **Voice Pattern Matcher** - Real-time frequency analysis and matching
- **Sacred Geometry Visualizer** - Flower of Life, Sri Yantra, Meridian patterns
- **Advanced Audio Controls** - White noise, isochronic tones, dual beats, frequency sweeping
- **MP3 Player** - Upload and analyze your own audio files
- **4D Bubble Visualizer** - Complex frequency-responsive animations
- **Cymatics Dial** - Precision frequency control
- **Waveform Canvas** - Real-time audio waveform display
- **Control Sidebar** - Complete parameter control panel

## Deployment Options

### Option 1: Vercel (Recommended)
1. Upload all files to your GitHub repository
2. Connect repository to Vercel
3. Set environment variable: `SESSION_SECRET=your-random-string`
4. Deploy automatically

### Option 2: Local Development
```bash
npm install
npm run dev
```

### Option 3: Production Build
```bash
npm install
npm run build
npm run start
```

## Environment Variables
- `NODE_ENV=production` (for production)
- `SESSION_SECRET=` (generate random string for sessions)

## Browser Requirements
- Modern browser with Web Audio API support
- Microphone permissions for voice features
- Audio output device

## All Original Components Preserved
- React + TypeScript frontend
- Express backend with session handling
- Tailwind CSS styling
- Real-time audio processing
- Complex visualizations
- Complete UI component library