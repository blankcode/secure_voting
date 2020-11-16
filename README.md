# Secure Voting in the Modern Age

Brian Blankenship<br>November 15, 2020

---

## Current Electronic Methods

Current methods are using PCs running either Windows or perhaps Linux. These machines are vulnerable to all of the problems PCs have and somtimes more due to the interfaces employed.

---

## Problems Classification

| Problem Class     | Paper | Electronic |
| ----------------- | ----- | ---------- |
| Vote Interception | X     | X          |
| Vote Alteration   | X     | X          |
| Vote Fabrication  | X     | X          |

---

## MUSTs and MUST NOTs

- MUST Avoid the internet and all of it's pitfalls.
- Electronic voting MUST ensure true anonominity.
- Votes MUST be detached from the Voter.
- MUST ensure accountablility of tallied voters.
- MUST Avoid human intervention where ever possible.
- SHOULD Avoid mechanical buttons/indicators.
  - They where out and.
  - May need to be manually reset.
- MUST Accomodate write-in selections
- MUST have a way to identify a voter is allowed to vote
  - So a Vote Fabrictor cannot just stand there pressing a button for the presidential candidate and committing them.

---

## Possible Implimentations

- An embeded system (black box [armored])
  - Use extreemly simple systems
    - Example: An Arduoino and buttons to select the candidate, with a final commit button with an "Are you sure?"
    - Clear mark out the process on the voting unit.
  - LED Indicators
  - Condutive Pads for "Switches"
  -
