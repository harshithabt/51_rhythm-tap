# Rhythm Tap

A 4-lane rhythm game built with Python and Pygame. Press the correct lane key as notes reach the hit line, maintain timing for hold notes, and track your performance through hit grades and accuracy.

Developed for **Software Engineering Lab 4 — Vibe Coding**.

---

## Features

- **Hit grading:** Scores successful hits as PERFECT, GREAT, or OK.
- **Hit sound effects:** Plays audio feedback for successful hits.
- **Hold notes:** Requires the player to sustain the corresponding lane key for one second.
- **BPM-synchronized spawning:** Schedules notes according to the configured tempo, such as 120 BPM.
- **Game-over summary:** Displays the score, PERFECT/GREAT/OK/MISS counts, accuracy percentage, and maximum combo.

---

## Tech Stack

- Python 3
- Pygame
- Git and GitHub

## Getting Started

### Prerequisites

- Python 3 installed
- pip package manager

### Installation

Clone the repository:

```bash
git clone https://github.com/harshithabt/51_rhythm-tap.git
cd 51_rhythm-tap
```

Install the dependencies:

```bash
python -m pip install -r requirements.txt
```

### Run the Game

```bash
python main.py
```

---

## Controls

| Key | Action |
|---|---|
| D | Hit Lane 1 |
| F | Hit Lane 2 |
| J | Hit Lane 3 |
| K | Hit Lane 4 |
| R | Restart the game |

For hold notes, press and sustain the corresponding lane key for the required duration.

## Scoring and Results

The game evaluates note hits using three grades:

- **PERFECT** — highest hit grade
- **GREAT** — good hit
- **OK** — acceptable hit

Missed notes are recorded as MISS. At game over, the summary displays the final score, grade counts, accuracy percentage, and maximum combo.

---

## Project Structure

```text
51_rhythm-tap/
├── game/
│   ├── __init__.py
│   ├── beat.py
│   └── game_engine.py
├── main.py
├── requirements.txt
├── .gitignore
└── README.md
```

---

## Implementation Tasks

The following tasks were specified in the starter project and implemented as part of the lab:

1. Add sound effects for PERFECT, GREAT, and OK hits.
2. Implement hold notes requiring a one-second hold.
3. Synchronize note spawning with the configured BPM.
4. Display a grade summary after game over.

---

## Testing

After installation, launch the game and verify the following:

- The game launches and accepts the lane controls.
- Successful hits produce the corresponding sound effects.
- Hold notes require the player to sustain the correct key.
- Notes spawn according to the configured BPM.
- The game-over screen displays grade counts and accuracy.

---

## Lab 4 Deliverables

The assignment submission, including the updated code, before/after gameplay videos, and chat history, is maintained in the `Lab4/` folder of the main [SE_Labs repository](https://github.com/harshithabt/SE_Labs).

---

## Author

Harshitha B.T.

## License

Created for an academic assignment. Refer to the original starter repository for applicable licensing terms.

---
