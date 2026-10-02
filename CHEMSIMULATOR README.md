# ⚗️ ChemSimulator — Chemical Process Analysis & Simulation Platform

A lightweight web app that performs core chemical engineering calculations with live charts and animated process schematics. Built for students who need fast, visual answers without installing simulation software.

## 🚩 Problem

Chemical engineering students repeat the same hand calculations for pressure drop, heat exchangers, reactors and material balances. Industrial simulators are expensive and heavy, and spreadsheets show no visual feedback.

## 💡 Solution

Pick a unit operation, enter your inputs, and get instant results with an interactive chart and a process schematic that responds to your numbers.

- 🔹 **Fluid Flow:** velocity, Reynolds number, flow regime, friction factor, pressure drop
- 🔥 **Heat Transfer:** duty, LMTD, required area (counter-current)
- 🧪 **Reactor Analysis:** CSTR vs PFR conversion, residence time
- ⚖️ **Material Balance:** product and bottoms flows, composition, balance check

## ✨ Key Features

- Clickable process-flow diagram (Feed → Pipe → Heater → Reactor → Separator → Product)
- Live results and charts that update as you type
- Hover values, axis labels and units on every chart
- Animated schematics linked to calculated values
- Input validation with clear error messages
- Light/dark theme, mobile responsive
- Zero friction: no login, no install, runs entirely in the browser

## 🛠️ Tech Stack

HTML, CSS, vanilla JavaScript, inline SVG. Single self-contained file, no dependencies.

## 📐 Equations Used

- Darcy–Weisbach with Swamee–Jain friction factor
- LMTD method: Q = U·A·LMTD
- First-order ideal CSTR and PFR
- Steady-state component balance

## 🚀 Running Locally

Open `index.html` in any browser.

## 🔗 Live Demo

[Try it here](https://atulk773955-crypto.github.io/chemsimulator/)

> Animations are educational schematics, not CFD or plant simulation.
