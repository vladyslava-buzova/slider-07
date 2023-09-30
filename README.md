# React + Vite

## React Project "Slider"
[ProjectLink](https://vladyslava-buzova.github.io/slider-07/)

## Figma URL
[Slider](https://www.figma.com/file/DauhbBpyI8wScdzvDGwti2/Slider?type=design&node-id=0-1&mode=design&t=kvmqAjRMc6ZrRZNZ-0)

## Steps
- In App.jsx, imported the people array from data.js and set it up as a state value using the useState hook.
- In the return statement, set up a container element to hold all the slides, and iterated over the people state value to create each slide.
- Set up prev and next buttons and style the container,slides and buttons.
- Created a currentPerson state value in App.jsx and set it to initially.
- Implemented the prev and next functionality using the setCurrentPerson function to update the currentPerson state value and move the slides back and forth using the transform property with a translateX value.
- Implemented the auto slide functionality using the setInterval function to change the currentPerson state value at regular intervals.

#### Main Logic
To move the slides back and forth, use the transform property with a translateX value. 
- Move the slides to the left -> transform:translateX(-100%);
- Move the slides to the right -> transform:translateX(100%);
- For the active slide -> transform:translateX(0);

#### Extra - React Slick Library
[React Slick Docs](https://react-slick.neostack.com/)

```sh
npm install react-slick slick-carousel --save
```

## How to launch a project:
1. Clone the repo.
git clone the-link-from-your-forked-repo.
2. Check your Node.js version.
node -v
3. Run VSCode and open the project folder.
4. Open a terminal in the project folder.
5. Run 'npm install' (or just npm i) to install the dependencies.
6. Run 'npm run dev' to start the project.

