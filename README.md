# Modern RPN Keystroke Programming

I write program suites for the [SwissMicros DM32](https://www.swissmicros.com/product/dm32), a modern calculator modelled after the legendary HP-32SII. Most of my repos are DM32 statefiles that turn a pocket RPN calculator into a specialised tool for finance, navigation, orbital mechanics, math exploration, transit operations, and more. I also tinker with RPN on the TI-84 Plus CE.

![DM32](https://img.shields.io/badge/SwissMicros-DM32-1f6feb?style=flat-square)
![RPN](https://img.shields.io/badge/Keystroke-RPN-555?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-Z80%2FeZ80-6e4c13?style=flat-square)

---

## 🚀 Getting started with a DM32 statefile

1. Download the `.d32` statefile from the repo you want.
2. Connect your DM32 over USB and copy the file into the `STATE` folder.
3. On the calculator, load it from the state file menu and the programs are ready to run.

Each repo's README documents its labels, inputs, and worked examples.

---

## 🧮 DM32 Program Suites

### 💰 Finance & Dates
| Repo | What it does |
|---|---|
| [**finance32**](https://github.com/jacober-calc/finance32) | Time value of money — solve for any one of N, I, PV, PMT, or FV. |
| [**datetime32**](https://github.com/jacober-calc/datetime32) | Date arithmetic that replicates and extends the HP-12C's date functions. |
| [**sportsbook32**](https://github.com/jacober-calc/sportsbook32) | Two-way market odds: strips the bookmaker's margin to find fair probabilities. |

### 🧭 Navigation, Earth & Space
| Repo | What it does |
|---|---|
| [**navigation32**](https://github.com/jacober-calc/navigation32) | Celestial and marine navigation — sunrise/sunset, sun position, closest point of approach. |
| [**geodetics32**](https://github.com/jacober-calc/geodetics32) | WGS 84 geodesy — Earth's radius, parallel circumference, rotational speed at latitude. |
| [**orbitcalc32**](https://github.com/jacober-calc/orbitcalc32) | Circular orbits — from height, velocity, circumference, period, or revs per sidereal day. |
| [**conversion32**](https://github.com/jacober-calc/conversion32) | One-key unit conversions between imperial, nautical, astronomical, and metric units. |

### 📐 Math & Probability
| Repo | What it does |
|---|---|
| [**gaussian32**](https://github.com/jacober-calc/gaussian32) | Normal distribution and error function, adapted from the HP-15C Advanced Functions Handbook. |
| [**logistic32**](https://github.com/jacober-calc/logistic32) | Explore the logistic map — iterate any growth rate and compute the Lyapunov exponent. |
| [**collatz32**](https://github.com/jacober-calc/collatz32) | The 3n + 1 problem — step counts and peak values for any starting number. |

### 🚌 Transit & Operations
| Repo | What it does |
|---|---|
| [**safedrive32**](https://github.com/jacober-calc/safedrive32) | Bus safety and route planning — braking, stopping distance, and reaction time. |
| [**layover32**](https://github.com/jacober-calc/layover32) | Scores scheduled layovers and runs Monte Carlo simulations on their reliability. |
| [**clearance32**](https://github.com/jacober-calc/clearance32) | Mine countermeasures planning — passes needed to reach a target clearance confidence. |

### ♟️ Games
| Repo | What it does |
|---|---|
| [**freechess32**](https://github.com/jacober-calc/freechess32) | Chess960 / Freestyle Chess starting positions from Scharnagl numbers 0–959. |

---

## 📟 TI-84 Plus CE

| Repo | What it does |
|---|---|
| [**rpnce**](https://github.com/jacober-calc/rpnce) | An RPN calculator program for the TI-84 Plus CE, written in C. |
| [**rpn84pce**](https://github.com/jacober-calc/rpn84pce) | TI-84 Plus CE port of [bxparks/rpn83p](https://github.com/bxparks/rpn83p) (fork). |

---
