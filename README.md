# React Fancy Confetti!

This README is a draft. Nothing will work yet.

## Install

`npm install --save react-fancy-confetti`

## Demo

react-fancy-confetti.github.io

## Usage

This component can be used as a background of any given div in the ReactDOM.

## Features and Customization

The `FancyConfetti` component takes the following two props (not required - but be warned, the default colors from the original source will otherwise be taken!):

colors: An array of RGB value arrays, ex for black and white [[0,0,0],[255,255,255]]

numConfetti: An integer, the total number of confetti

Example:

<FancyConfetti colors={['my', 'tasty', 'colors']}/>

## Known Issues

## Credits

This repository originated as an npm react component boilerplate project from Markus England (https://github.com/markusenglund/react-npm-component-starter)[https://github.com/markusenglund/react-npm-component-starter]

All credit for the fantastic code for the confetti comes from Linmiao Xu's codepen at (https://codepen.io/linrock/pen/Amdhr)[https://codepen.io/linrock/pen/Amdhr]. I only added the required reactification of the code to get this into a component.
