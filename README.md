# Office 3D Walkthrough

An interactive 3D model of an office building with a covered private driveway, garage, security systems and step-free access. It runs entirely in the browser from a single HTML file, built with [three.js](https://threejs.org/) and no build step.

**Live demo:** `https://surya-consultancy-service.github.io/office-3D-walkthrough/

## Features

**Layout**
- Entrance lobby with guard desk and main rolling shutter
- Proprietor cabin, billing and payments desk, meeting cabin (4 to 6 person table)
- Customer waiting area with a tea and coffee machine
- Locked record room, pantry with Aquaguard, accessible bathroom with basin
- Common walkway (2.5 m wide) connecting the left and right sections
- Garage behind the office for 2 cars and 5 bikes, with a covered private driveway
- Public side road with sidewalk and kerb ramp

**Security**
- 19 CCTV domes covering every room, the garage and the gate
- Fingerprint sensors at the main entrance and the garage gate
- Padlock on every door, so employees with a key can still get in
- Desk buttons that let staff unlock their own cabin doors without getting up
- Guard desk buttons:
  - Red: close the main shutter instantly
  - Amber: open or close the garage gate
  - Blue: unlock the garage-to-office door for customers

**Accessibility**
- One floor level throughout, with no steps between rooms
- Front entrance ramp (1:15) with handrails and a dropped-kerb ramp on the garage side
- Doors 1.2 m wide or more, a 1.5 m turning circle and grab bars in the bathroom
- Accessible parking bay with a transfer aisle

## Controls

| Action | How |
| --- | --- |
| Rotate | Drag |
| Zoom | Scroll or pinch |
| Automatic tour | **Tour** button (slow 2.5 minute loop around the building) |
| Free camera | **Orbit** button |
| Plan view | **Top view** button |
| Main shutter | **Shutter** button |
| Unlock a door | Tap a green desk button, a fingerprint pad, a padlock or a guard button |

Doors close again by themselves after 6 seconds. The garage gate stays open when opened from the guard desk until the guard taps the button again.

## Run locally

Open `index.html` in any modern browser. An internet connection is needed to load three.js (r128) from cdnjs.

## Publish with GitHub Pages

1. Upload the file as `index.html` to the repository.
2. Go to **Settings → Pages**, choose the `main` branch and save.
3. Your site will be live at the link above within a minute or two.

## Tech

Plain HTML, CSS and JavaScript with [three.js r128](https://cdnjs.com/libraries/three.js/r128). Everything in the scene is built from boxes and cylinders in code, so there are no 3D model files to download.
