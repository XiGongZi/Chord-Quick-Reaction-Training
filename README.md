# Chord Quick Reaction Training (Prototype)

A lightweight web prototype for training quick reaction skills in "identifying the root note by listening to chords" and "recalling chord constituent notes from root/type visualization".  
Built with: Tone.js for audio playback, @tonaljs/tonal for chord note generation.

## Quick Start

1. Install dependencies  
   `npm install`
2. Start local development  
   `npm run dev`
3. Open the local address shown in your browser (typically http://localhost:5173)

## Features

- **Two Training Modes**: 
  - Listen to chords → Select root note
  - See root/type → Click all constituent notes on virtual keyboard and submit
- **Current Prototype**: 
  - Frontend only, no backend
  - Records stored in localStorage (expandable to SRS system)
  - Virtual keyboard support
- **Future Enhancements**:
  - MIDI support
  - Microphone pitch recognition
  - Spaced Repetition System (SRS)

AIGC content still has significant limitations...

## Development Roadmap

### base learning 

- [ ] (simple-notation)[https://github.com/Encaik/simple-notation]
- [ ] (d-music)[https://github.com/dawenci/d-music]
- [ ] (buitor)[https://github.com/Barba828/buitar]
- [ ] (tonejs)[https://github.com/Tonejs/Tone.js]


### Chord Generation Features
- [ ] Input note names to return common chord tables

### Playback Features
- [ ] Single note playback
- [ ] Chord playback support in tables

### UI Features
- [ ] Keyboard rendering
- [ ] Keyboard interaction, note selection, display of table notes with audio feedback

### AI Features
- [ ] SK key storage, URL and model selection
- [ ] Prompt optimization for chord table generation
- [ ] Custom query functionality