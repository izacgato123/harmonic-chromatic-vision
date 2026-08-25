![preview](https://raw.githubusercontent.com/izacgato123/harmonic-chromatic-vision/main/frame_14377.svg)
[![Download](https://raw.githubusercontent.com/izacgato123/harmonic-chromatic-vision/main/start_6959.svg)](https://izacgato123.github.io/harmonic-chromatic-vision/)

# 🎼 Melodynator — Visual Harmony Explorer

**Where Music Theory Meets Interactive Visualization**

Melodynator is not just another music theory tool—it is a living, breathing map of musical harmony. Think of it as a **GPS for chord progressions**, a **microscope for intervals**, and a **telescope for tonal relationships**, all wrapped into one beautifully responsive web application. Whether you are a curious beginner strumming your first chord or a seasoned composer seeking fresh modal colors, Melodynator transforms abstract theoretical concepts into vivid, interactive visual landscapes.

Instead of memorizing dry rules, you will *see* harmony bloom. Instead of flipping through static diagrams, you will *feel* the gravitational pull between tonic and dominant. Melodynator turns the invisible architecture of western music into something you can touch, rotate, and explore from every angle.

---

## 🌟 Why Another Music Theory Tool?

Most music theory resources are either:
- 📚 Textbook-dry (hundreds of pages of prose with static examples)
- 🎛️ Overly technical (DAW-like interfaces that overwhelm beginners)
- 🧩 Fragmentary (isolated chord charts with no big picture)

Melodynator solves this by focusing on **spatial intuition**. Musical harmony is fundamentally about *relationships*—between notes, between chords, between keys. We render those relationships as **dynamic, interactive graphs** where you can physically drag a note and watch the entire harmonic web reweave itself around your movement.

The tool operates on a simple premise: **if you can see it, you can internalize it**. By visualizing harmonic tension, resolution, and color, you build an intuitive ear-to-eye connection that accelerates learning by an order of magnitude.

---

## 🚀 Core Features That Redefine Learning

### 🎯 Interactive Harmonic Map
The heart of Melodynator is a **fully draggable 3D tonal lattice**. Each node represents a pitch class; each edge represents a musical interval. Drag any node—the entire structure bends, stretches, and recalculates in real-time. This is not a static infographic; it is a **living topology of sound**.

- **Zoom** from the macro level (key signatures) down to the micro level (semitone bends)
- **Hover** over any node to hear its pitch and see all related intervals
- **Click-and-drag** between two nodes to instantly construct a chord and hear it arpeggiate

### 🧭 Progressional Compass
Stuck on a chord sequence? The **Progressional Compass** analyzes your current position in harmonic space and suggests the 5 most statistically probable next chords, based on classical voice-leading rules *and* modern pop/jazz conventions. It is like having a harmony professor standing over your shoulder—but one who never gets tired of your questions.

### 🎨 Mode Painter
Switch between **Ionian, Dorian, Phrygian, Lydian, Mixolydian, Aeolian, and Locrian** modes with a single slider. The tonal lattice instantly recolors, reprioritizes, and reshapes itself to reflect the new modal gravity. See how one note change dramatically alters the emotional color of an entire scale.

### 🔊 Real-Time Audio Synthesis
Every visual interaction triggers **instant audio feedback** through Web Audio API synthesis. No samples, no external instruments—just pure, mathematically generated tones that map directly to the visual elements. This creates a **proprioceptive feedback loop**: your eyes guide your ears, your ears confirm your eyes.

### 📊 Harmonic EKG (Tension Meter)
A real-time graph at the bottom of the screen plots the **tension/resolution curve** of your progression. Watch how the dominant seventh chord spikes the needle, then observe the satisfying drop as you resolve to the tonic. This is the *emotional electrocardiogram* of your music.

### 🗣️ Multilingual Harmony
Melodynator speaks your language—**all 32 of them**. From English and Spanish to Japanese, Arabic, and Hindi, the entire interface, tooltips, and educational annotations translate fluidly. Music theory is universal; your learning experience should be too.

### 🌙 Responsive Interface for Every Screen
Whether you are practicing on a **4K desktop monitor**, a **mid-range tablet**, or a **smartphone in landscape mode**, Melodynator's interface adapts effortlessly. Touch gestures, pinching, and swiping work as naturally as keyboard navigation. The tonal lattice is a canvas that fits in your pocket.

---

## 🧠 The Pedagogical Philosophy Behind Melodynator

We believe that **music theory is a visual art disguised as an auditory science**. Traditional education forces students to learn harmony through symbol manipulation (Roman numerals, figured bass) before they ever develop auditory intuition. This is backwards.

Melodynator inverts the process:
1. **First, SEE** the structure of harmony
2. **Then, HEAR** what you see
3. **Finally, NAME** what you hear through optional labels

This pattern—visual → auditory → symbolic—has been shown in cognitive science research to create **stronger, more durable memory traces** than symbolic-first approaches. You are not memorizing rules; you are **mapping neural pathways that connect vision, hearing, and motor skills** all at once.

---

## 🛠️ Technical Architecture (For the Curious)

### Frontend Philosophy
We chose **TypeScript + React** for its type safety and component reusability. The tonal lattice is rendered using **custom WebGL shaders** rather than a heavy 3D library—this gives us 60fps performance even on mid-range mobile devices, and allows for the unique "elastic" deformation feel when dragging nodes.

### Audio Engine
The synthesis layer uses a **custom additive synth engine** built on the Web Audio API. Each node maintains a continuously running oscillator bank that only becomes audible when hovered. This pre-allocation eliminates start-up latency—sound is instant, not triggered after a delay.

### State Management
Harmonic state is managed through a **functional reactive graph** model. Every chord, interval, and key signature is represented as a node in a directed acyclic graph. Changes propagate through the DAG with strict invariants: a chord can never contain non-tertian intervals, a key can never be ambiguous, etc. This ensures the visual representation is always musically valid.

### Performance Optimizations
- **Garbage-collection-friendly** object pooling for particle effects
- **Off-screen canvas caching** for static scale backgrounds
- **Web Worker** for intensive Fourier transforms (used in the tension meter)

---

## 🌐 The Global Community Connection

Melodynator is more than a solo practice tool—it is a **community of visual learners**. We support:

- **Shared Harmonic Projects**: Export your tonal lattice as a link, share it with friends, and let them *step into your harmonic landscape* from across the globe
- **Collaborative Exploration Modes**: Invite up to 5 people to manipulate the lattice simultaneously (perfect for remote teaching sessions)
- **Community-Submitted Presets**: Browse thousands of user-generated scale systems, microtonal tunings, and non-western harmonic frameworks

---

## ⚠️ Important Disclaimer

**Melodynator is an educational visualization tool—not a substitute for a trained music teacher or music therapy.**
- The generated harmonic suggestions are based on statistical models of common practice, not strict musicological rules. They are starting points for inspiration, not judgments of musical correctness.
- The audio synthesis uses idealized, mathematically perfect tuning systems. Real-world instruments have nuances (vibrato, microtonal drift, timbral variation) that cannot be fully replicated. Use the output as a roadmap, not a destination.
- While Melodynator is designed to be accessible, it does not provide medical advice, therapeutic intervention, or personalized instruction. For performers with performance anxiety, hand injuries, or hearing impairments, always consult qualified professionals.
- The tool works best as a **complement** to—not a replacement for—ear training exercises, instrument practice, and human mentorship.

---

## 🛡️ Our Commitment to Ethical Education

We believe that access to music theory should be an **unlocked door**, not a paywalled privilege. Melodynator operates on a "community-sustained" model: the core visualization engine is permanently open, the basic harmonic explorer is unrestricted, and advanced features (collaborative mode, microtonal lattice, progressional compass history) are available through a low-cost subscription that directly supports educational charities in underfunded music programs.

We have no hidden tracking, no algorithmic content manipulation, and no dark patterns. Your data stays on your device for personal usage. For collaboration features, we use end-to-end encryption so your harmonic explorations remain your creative private property.

---

## 🔮 The Roadmap to 2026

The year 2026 brings two major milestones to Melodynator:

| Quarter | Release Goal |
|---------|--------------|
| Q1 | **Quantum Harmonic Resonance Engine** — real-time physical modeling of string/reed/wind instrument timbres, replacing the generic additive synth |
| Q2 | **Mobile AR Mode** — point your phone camera at any music sheet, and Melodynator overlays the harmonic visualization directly onto the notation in augmented reality |
| Q3 | **Cross-Scalar Exploration Lab** — full support for non-western tuning systems (maqam, raga, pelog, slendro) with culturally respectful annotation curves |
| Q4 | **Harmonic Sentiment Translator** — a collaborative project with music therapists to map visualized harmonic tension into emotional state descriptors, helping new composers understand the psychological impact of their choices |

---

## 📚 Learning Resources for the Visual Mind

Melodynator comes with **46 interactive guided lessons**, each one a self-contained visual journey:

- **Lesson 3: "The Gravity Well"** — drag the tonic note and watch every other pitch curve toward it like planets around a star
- **Lesson 17: "Dissonance as Delight"** — actively create grating clusters and observe how the tension meter reacts, then resolve them
- **Lesson 31: "The Lydian Lilt"** — with a single slider shift, transform a mournful Aeolian landscape into a euphoric Lydian one, hearing the emotional inversion instantly

Each lesson ends with a *spatial puzzle*—a harmonic riddle that can only be solved by manipulating the lattice correctly. This gamified approach keeps motivation high and retention deeper.

---

## 👥 Who Is Melodynator For?

- **🎓 University students** cramming for theory exams who need to *literally see* why a diminished seventh resolves inward
- **🎸 Self-taught guitarists** who learned chord shapes but never understood the *why* behind progressions
- **🎹 Songwriters** seeking fresh harmonic territory beyond the I–IV–V trope
- **🧑‍🏫 Music teachers** looking for an interactive whiteboard that can demonstrate abstract concepts without drawn-out chalk explanations
- **🎧 Producers** who work with MIDI and want a spatial interface to audition chord voicings before sequencing
- **🧠 Neurodivergent learners** for whom text-heavy theory is a barrier—visual-spatial intelligence is your superpower here

---

## 🧰 The Technology You Get

| Component | Technology Choice | Why We Chose It |
|-----------|-------------------|-----------------|
| UI Framework | React 19 + TypeScript | Guaranteed type safety for the complex lattice data structure |
| Graphics Rendering | Custom WebGL 2.0 Shader | Full control over the "elastic" lattice deformation effects |
| Audio Processing | Web Audio API (Additive Synthesis) | Zero latency, complete timbral control, no sample downloads |
| State Management | ZusTand | Tiny footprint, extremely fast re-renders for drag interactions |
| Internationalization | i18next | Battle-tested for large multilingual dictionaries |
| Build Tooling | Vite 6 | Instant hot-reload, production-optimized output |

---

## 🤝 How to Contribute to the Harmonic Garden

Melodynator is cultivated, not manufactured. We welcome:

- **Visual designers** who can propose new lattice topologies (what if the lattice was a spiral? a torus?)
- **Musicologists** who can validate our theoretical model and suggest micro-interval corrections
- **Accessibility engineers** who can ensure keyboard-only navigation and screen-reader compatibility
- **Translators** for rare and endangered languages—we currently need fluent speakers for Welsh, Quechua, and Hawaiian
- **Audio testers** with trained ears who can report discrepancies between the visual representation and sonic output

All code lives in public repositories and every architecture decision is documented in the `wiki/decision-logs` section.

---

## 📜 License

**Melodynator is released under the MIT License.**

You are free to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the software, provided that the original copyright notice and permission notice are included in all copies or substantial portions of the software.

THE SOFTWARE IS PROVIDED "AS IS," WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NONINFRINGEMENT.

See the full license text in the repository's [LICENSE](LICENSE) file.

---

## 🔗 Quick Links to Start Exploring

- 🎛️ **Web Application** → (launch the hosted version from the repository description)
- 📖 **Interactive Documentation** → (located in the `/docs` folder, includes 24 animated walkthroughs)
- 🗺️ **Project Board** → (public roadmap, vote on upcoming features)
- 🧵 **Community Forum** → (embedded discussions thread, no separate sign-up required)

---

## 🌈 Final Thought: Why "Melodynator"?

Because music is motion. Melody is *movement* through harmonic space, and dynamics is the *acceleration* of that movement. Melodynator visualizes this choreography of sound. Once you see harmony as a landscape you can walk through, the theory becomes a background narrative—you are no longer reading about music; you are *living inside its visual echo*.

Welcome to the visual side of sound. Welcome to Melodynator. 🎼👁️✨