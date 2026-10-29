# Laundry Service Landing Page

A responsive Laundry Service Landing Page built using HTML and CSS, featuring CSS keyframe animations, button hover effects, and a responsive hamburger menu.

## Features

- Responsive navigation bar
- Hamburger menu for mobile screens
- Hero section with laundry image
- CSS `@keyframes` animation for image movement and rotation
- Smooth button hover effect using `transform`
- Responsive layout for desktop, tablet, and mobile devices

## Animation Details

### 1. CSS `@keyframes`

The `@keyframes` rule defines the different stages of an animation.

- `orbitMove`: Moves the hero image forward, backward, and vertically.
- `imageRotate`: Rotates the image slightly clockwise and counterclockwise.

### 2. Button Hover Animation

The `transform` property adds a smooth scaling and rotation effect when the user hovers over a button.

```css
button:hover {
    transform: scale(1.06) rotate(2deg);
}
```

### 3. Animation Properties

- `animation-duration`: Controls how long one animation cycle takes.
- `animation-timing-function`: Controls the speed progression.
- `animation-iteration-count`: Repeats the animation infinitely with `infinite`.

## Technologies Used

- HTML5
- CSS3
- Flexbox
- CSS Media Queries
- CSS Transforms
- CSS Keyframe Animations

## Project Structure

```text
Laundry-Service/
├── index.html
├── style.css
└── images/
    └── Hero Img.jpg
```

## How to Run

1. Clone or download this repository.
2. Open the project folder in VS Code.
3. Make sure the image is available inside the `images` folder.
4. Open `index.html` in your browser.

## Learning Outcomes

- Understanding CSS `@keyframes`
- Applying `transform` and `transition`
- Creating hover animations
- Building responsive layouts using media queries
- Implementing a mobile hamburger menu using CSS

## Author

Arshdeep Kaur