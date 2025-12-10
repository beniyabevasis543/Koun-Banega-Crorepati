# Kaun Banega Crorepati - Console Edition

A fully functional console-based implementation of the popular Indian quiz show Kaun Banega Crorepati? (Who Wants to Be a Millionaire?) written in C. Players answer 12 progressively difficult questions to win up to ₹1,000,000 with realistic lifelines and gameplay mechanics.[file:1][file:2]

## Features
- *12 Questions*: Increasing difficulty and prize money from ₹1,000 to ₹1,000,000.
- *Lifelines* (usable once each):
  - 50:50 - Removes two incorrect options randomly.
  - Phone-a-Friend - 70% chance of correct suggestion.
  - Ask the Audience - Poll with bias toward correct answer.
- Walk away anytime with current winnings; guaranteed money at milestones (₹10,000 & ₹320,000).
- Robust input handling and random elements for replayability.

## Compilation & Usage
1. Save the code as kaunbanegacrorepati.c.
2. Compile: gcc kaunbanegacrorepati.c -o kaunbanegacrorepati
3. Run: ./kaunbanegacrorepati

*Controls*:
- A, B, C, D - Select answer.
- L - Use lifeline (select 1-3).
- Q - Quit and take winnings.

## Questions & Prizes
| Question # | Prize (₹) | Sample Topics |
|------------|-----------|---------------|
| 1-3       | 1,000-3,000 | Geography, Literature |
| 4-6       | 5,000-10,000 | Science, Programming |
| 7-9       | 20,000-80,000 | Chemistry, Tech History |
| 10-12     | 160k-1M | Math, Physics, OOP |

## Author
Beniya Devasis

## License
MIT License - Feel free to use, modify, and distribute.[file:1]
