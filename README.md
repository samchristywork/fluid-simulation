![Banner](https://s-christy.com/sbs/status-banner.svg?icon=content/biotech&hue=200&title=Fluid%20Simulation&description=Interactive%20real-time%20fluid%20dynamics%20in%20the%20browser)

## Overview

<p align="center">
  <img src="./res/example.gif" width=500 />
</p>

A real-time interactive fluid simulation running entirely in the browser. Based
on Jos Stam's "Real-Time Fluid Dynamics for Games" algorithm, it simulates
density and velocity fields on a 128×128 grid with solid rectangular obstacles.
Fluid is rendered with a fire-like color gradient and can be exported as a GIF.

## Features

- Real-time Navier-Stokes fluid simulation (diffusion, advection, projection)
- Interactive mouse input: click and drag to inject fluid and impart velocity
- Automatic wind source that continuously pushes fluid from the left edge
- Solid rectangular obstacles that fluid flows around
- Fire-like color mapping (black → red → orange → white)
- Built-in GIF recorder — capture and download animations directly from the page
- No build step or dependencies — single self-contained HTML file

## Usage

Open `index.html` in any modern web browser. No server or installation required.

- **Click and drag** on the canvas to inject fluid and add velocity
- **Mouse movement** (without clicking) adds velocity to nearby fluid
- Click **Record GIF** to start capturing frames, then **Stop & Save GIF** to
  download the animation

## License

This work is licensed under the GNU General Public License version 3 (GPLv3).

[<img src="https://s-christy.com/status-banner-service/GPLv3_Logo.svg" width="150" />](https://www.gnu.org/licenses/gpl-3.0.en.html)
