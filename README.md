# Fundamentals of Alternating Current for Avionics

A comprehensive interactive training system for learning AC (Alternating Current) fundamentals essential for avionics technicians and CAET (Certified Avionics Electronics Technician) preparation.

## Overview

This repository contains a complete AC fundamentals training system covering:

- **AC Basics**: Frequency, period, sine waves, RMS voltage, peak voltage
- **Oscilloscopes**: Controls, measurements, waveform analysis, triggering
- **Function/Frequency Generators**: Operation, controls, applications
- **Inductors**: Inductance, inductive reactance, phase relationships
- **Transformers**: Types, turns ratios, step-up/step-down, isolation
- **Capacitors**: Capacitance, capacitive reactance, types, safety
- **Aircraft AC Power Systems**: 400 Hz power, three-phase, rectifiers, inverters

## Training Modules

### 1. Index/Dashboard (`index.html`)
The main landing page featuring:
- Gamification system with XP, levels, and badges
- Progress tracking and analytics
- Access to all training modules
- Integration with NotebookLM AI assistant

### 2. Interactive Flashcards (`Flash Card - AC.html`)
- 50+ comprehensive AC fundamentals flashcards
- Spaced repetition SM-2 algorithm
- Three difficulty levels (Easy, Medium, Difficult)
- Tag-based filtering and search
- Progress tracking with mastery ratings

**Topics Covered:**
- AC waveforms and measurements
- Oscilloscope operation and controls
- Function generator usage
- Inductor behavior and calculations
- Transformer theory and applications
- Capacitor types and characteristics
- Impedance, phase, and resonance
- Aircraft power systems

### 3. Practice Test (`Practice Test -- AC.html`)
Comprehensive practice test with 70+ questions across 7 categories:
- AC Fundamentals (10 questions)
- Oscilloscopes (10 questions)
- Function/Frequency Generators (10 questions)
- Inductors & Inductance (10 questions)
- Transformers (10 questions)
- Capacitors & Capacitance (10 questions)
- AC Power & Advanced Concepts (10 questions)

Features:
- Flashcard-style Q&A format
- Detailed explanations for each answer
- Progress tracking
- Hangar-themed interface with animations

### 4. Jeopardy Game (`Jeopardy AC.html`)
Interactive Jeopardy-style game with Player vs AI mode:
- 6 categories (3 per round)
- 5 difficulty levels per category
- Point values: Round 1 ($100-$500), Round 2 ($200-$1000)
- Final Jeopardy question
- AI opponent with adjustable difficulty
- Buzzer system simulation

**Categories:**
- Round 1: AC Basics, Oscilloscopes, Inductors & Transformers
- Round 2: Capacitors, Test Equipment, Aircraft AC Power

## Key Concepts Covered

### AC Fundamentals
- Alternating Current vs Direct Current
- Frequency (f) and Period (T) relationships
- 400 Hz aircraft power systems
- Sine wave characteristics
- Peak, Peak-to-Peak, and RMS voltage
- Phase relationships

### Test Equipment
- Oscilloscope controls (Time Base, Vertical Scale, Trigger)
- Oscilloscope probes (10:1 attenuation)
- Function generator operation
- Waveform generation (sine, square, triangle)
- Measurement techniques

### Reactive Components
- Inductive Reactance: XL = 2πfL
- Capacitive Reactance: Xc = 1/(2πfC)
- Phase relationships (current leads/lags voltage)
- Series and parallel calculations
- Resonance: f = 1/(2π√LC)

### Transformers
- Primary and secondary windings
- Turns ratio and voltage/current relationships
- Step-up, step-down, and isolation transformers
- Transformer losses and efficiency
- Aircraft applications

### Aircraft Systems
- 400 Hz vs 60 Hz power
- Three-phase AC power
- Rectifiers (AC to DC conversion)
- Inverters (DC to AC conversion)
- Ground power requirements
- Safety considerations

## Usage

### Getting Started
1. Open `index.html` in a web browser
2. Enter your name to begin tracking progress
3. Choose a training module:
   - **Classroom**: External learning content (requires internet)
   - **Flashcards**: Interactive study cards
   - **Practice Test**: Comprehensive assessment
   - **Jeopardy**: Game-based learning

### Gamification Features
- **XP System**: Earn experience points by completing modules
- **Levels**: Progress through levels based on total XP
- **Badges**: Unlock achievements for milestones
- **Score History**: Track improvement over multiple attempts
- **Analytics**: View detailed progress metrics

### Study Tips
1. Start with **Flashcards** to build foundational knowledge
2. Use the **Easy/Medium/Difficult** rating system to focus on weak areas
3. Take the **Practice Test** to assess understanding
4. Play **Jeopardy** for fun, competitive review
5. Review score history to identify improvement areas

## Technical Details

### File Structure
```
Fund-of-Alternating-Current/
├── index.html                  # Main dashboard
├── Flash Card - AC.html        # Flashcard module
├── Practice Test -- AC.html    # Practice test module
├── Jeopardy AC.html           # Jeopardy game module
└── README.md                   # This file
```

### Technologies Used
- Pure HTML, CSS, and JavaScript (no external dependencies)
- LocalStorage for progress persistence
- CSS animations and transitions
- Responsive design for mobile/tablet compatibility

### Browser Compatibility
- Chrome/Edge (recommended)
- Firefox
- Safari
- Modern mobile browsers

## Aircraft-Specific Content

This training system emphasizes avionics applications:
- **400 Hz Power**: Why aircraft use 400 Hz instead of 60 Hz
- **Weight Savings**: Impact of frequency on transformer/motor size
- **Three-Phase Systems**: Power distribution in aircraft
- **Ground Power**: Compatibility requirements
- **Emergency Power**: Inverters for backup AC power
- **Safety**: Proper handling of electrolytic capacitors, ESD precautions

## Formulas Reference

### AC Fundamentals
- Period: T = 1/f
- RMS Voltage: Vrms = 0.707 × Vp
- Peak-to-Peak: Vp-p = 2 × Vp

### Reactance
- Inductive: XL = 2πfL
- Capacitive: Xc = 1/(2πfC)

### Transformers
- Voltage Ratio: Vs/Vp = Ns/Np
- Current Ratio: Is/Ip = Np/Ns

### Resonance
- Resonant Frequency: f = 1/(2π√LC)

### Impedance
- Series RLC: Z = √(R² + (XL - Xc)²)

## Learning Objectives

Upon completion, students will be able to:
1. Explain the difference between AC and DC
2. Calculate frequency, period, and voltage relationships
3. Operate oscilloscopes and function generators effectively
4. Understand inductor and capacitor behavior in AC circuits
5. Calculate inductive and capacitive reactance
6. Analyze transformer voltage and current ratios
7. Explain aircraft AC power system requirements
8. Apply safety practices for AC circuits and components

## Credits

Developed for avionics technician training and CAET exam preparation.

## License

Educational use only.

## Support

For issues or questions, refer to the gamification system help within the application or contact your training administrator.

---

**Note**: This training system uses 400 Hz as the standard aircraft AC frequency. Always verify actual system specifications for specific aircraft models.
