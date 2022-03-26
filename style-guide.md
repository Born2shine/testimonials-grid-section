# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

Moderate violet: hsl(263, 55%, 52%)
Very dark grayish blue: hsl(217, 19%, 35%)
Very dark blackish blue: hsl(219, 29%, 14%)
White: hsl(0, 0%, 100%)

### Neutral

Light gray: hsl(0, 0%, 81%)
Light grayish blue: hsl(210, 46%, 95%)

Note for text colors:

1. "Verified Graduate" has the same color as the person's name with 50% opacity
2. Review paragraphs inside the quotations have the same color as well, but are at 70% opacity

## Typography

### Body Copy

- Font size: 13px

### Font

- Family: [Barlow Semi Condensed](https://fonts.google.com/specimen/Barlow+Semi+Condensed)
- Weights: 500, 600



<div class="circle"></div>
<div class="circle-1"></div>
<div class="big-circle"></div>
<div class="red-circle">
	
</div>
<div class="circle-2"></div>
<div class="circle-3"></div>

<style>
  body{
    background: #161616
  }
  .circle {
    width: 50px;
    height:50px;
    background: #000000;
    position: absolute;
    top:50%;
    left:50%;
    transform: translate(-50%, -50%);
    border-radius: 50%;
  }
  .circle-1{
    width: 70px;
    height:70px;
    background: #E96A23;
    position: absolute;
    top:50%;
    left:50%;
    transform: translate(-50%, -50%);
    border-radius: 50%;
      z-index: -1
  }
  .big-circle{
     width: 200px;
    height:200px;
    background: #000000;
    position: absolute;
    top:50%;
    left:50%;
    transform: translate(-50%, -50%);
    border-radius: 50%;
      z-index: -2;
    border: 1px solid #161616
  }
  .red-circle{
    width: 190px;
    height:190px;
    background: #A22015;
    position: absolute;
    top:50%;
    left:50%;
    transform: translate(-50%, -50%);
    border-radius: 50%;
      z-index: -2;
    border: 1px solid #161616;
    overflow: hidden;
  }
  .circle-2{
    width: 100px;
    height:100px;
    background: #000000;
    position: absolute;
    top:50%;
    left:50%;
    transform: translate(-50%, -50%);
    border-radius: 50%;
      z-index: -2;
    border: 1px solid #161616
  }
  .circle-3{
    width: 80px;
    height:80px;
    background: #A22015;
    position: absolute;
    top:16.2%;
    right:15.5%;
    border-radius: 50%;
      z-index: -2;
    border: 15px solid #000000;
  }
</style>
