# CartPole Policy Gradient Sandbox

This single-page web app trains a tiny policy-gradient controller for the CartPole environment entirely in the browser. Open `index.html` in any modern browser to start experimenting—no build tools or servers required.

## Features
- Real-time training loop that improves a neural policy directly in the page.
- Canvas-based CartPole visualization with live state updates.
- Episode metrics: reward, step count, last/best survival times, and recent history plot.
- Lightweight network visualization (SVG) plus activation and weight inspectors.
- Controls to start/pause training, run one episode at a time, or reset progress.

## Usage
1. Open `index.html` in your browser.
2. Click **Start Training** to watch the policy learn; pause anytime.
3. Inspect activations/weights and episode charts to observe how learning evolves.
