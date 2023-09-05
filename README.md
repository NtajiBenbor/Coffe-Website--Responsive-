# A website for a coffee shop: "HUB CAFE"

## Content :link:

1. [Project Overview](#1-project-overview-😄)
2. [Screenshots](#2-screenshots-📷)
3. [Why I built this](#3-why-i-built-this-❓)
4. [what I learned building this project.](#4-what-i-learned-while-building-this-project)
5. [Challenges](#5-challenges-😓)
6. [Tools and resources utilized](#6-tools-and-resources-utilized-🔧)
7. [Author](#7-author-🖊️)


## 1. Project Overview :smile:
This is a website for a fictional coffee shop called **"HUB CAFE"**. The site is made up of two active pages; the Homepage and the About page. This project is not responsive on smaller screens; I'll update that someday.

***
check it out [here](https://hubcafe.netlify.app/)
***

## 2. Screenshots :camera:
### Screenshot 1
![Home page](/img/Hub%20Cafe-Home%20page.png)
*A screenshot of HUB CAFE's Homepage*

### Screenshot 2
![About Page](/img/Hub%20Cafe-About%20page.png)
*A screenshot of the HUB CAFE's About Page*

## 3. Why I built this :hammer:
Entering this project, my goals were to apply recently acquired knowledge and skills, including:

- **Color Gradients:** I was eager to put my newfound knowledge of color gradients into practice. Using gradients can add depth and visual interest to web design, and it's a great way to enhance the aesthetics of a project.

- **Flexbox for Layouts:** I aimed to practice using Flexbox for creating flexible and responsive layouts. Flexbox provides a powerful and intuitive way to design the structure of web pages, making it easier to align and distribute elements within containers.

- I also wanted to put my newly acquired knowledge of CSS color theory to practical use. Consequently, I set out to explore various methods of employing colors in CSS, including:

    - Utilizing color names, such as `red`, for straightforward color references.
    - Employing hexadecimal codes (e.g., `#ffffff`) to specify precise colors.
    - Experimenting with HSL values (Hue, Saturation, and Lightness) like `hls(260, 100%, 100%)` to gain a better grasp of color manipulation.
   - Utilizing RGB values (Red, Green, and Blue) such as `rgb(255, 255, 255)` for fine-tuned control over color components.

- Furthermore, I delved into understanding the concept of the alpha channel and its function in relation to these color systems, including:

   - Hexadecimal codes with alpha, like `#ffffffff`, to control opacity alongside color.
   - HSLA values (Hue, Saturation, Lightness, and Alpha), such as `hsla(260, 100%, 100%, 0.5)`, to create colors with varying levels of transparency.
   - RGBA values (Red, Green, Blue, and Alpha) like `rgba(255, 255, 255, 1)` to specify colors with explicit opacity settings.

## 4. what I learned building this project.
This project presented quite a challenge for me, especially given my beginner-level CSS skills. However, I persevered and ultimately gained comfort with the following CSS properties:

- **The `linear-gradient` Value:** I became proficient in using the `linear-gradient` property to create gradient backgrounds. This property allowed me to define gradient directions and color stops to achieve the desired visual effects.

- **The `box-shadow` Property:** I learned how to apply the `box-shadow` property to elements, enabling me to add shadow effects for depth and dimension. In the example below, I applied a box shadow to the `.barista-card` class when it's hovered over, along with a smooth transition effect:

```css
.barista-card:hover {
    box-shadow: -10px 10px 5px 5px rgba(0, 0, 0, 0.3);
    transition: 0.5s;
    background: linear-gradient(225deg, hsla(0, 59%, 92%, 1) 30%, hsla(30, 6%, 94%, 1) 99%);
}
```

## 5. Challenges :sweat:
- figuring out how to position my hero image properly. I was able to resolve this by writing the following styles:
```CSS
.hero {
    width: 100%;
    height: 800px;
    background: url(/img/pexels-brix-saranza-4621676.jpg);
    background-attachment: scroll;
    background-size: cover;
    background-position: center;
    object-fit: cover;
    margin-top: -37px ;
    scroll-behavior: smooth;
   
}
```

## 6. Tools and resources utilized :wrench:
The following tools and resources where utilized in building this project.
- HTML5
- CSS3
- Images from [pexels.com](https://www.pexels.com) :link:
- Color pallet from [coolors.co](https://coolors.co) :link:
- Icons from [icons8.con](https://icons8.com/) :link:
- Resources from [freecodecamp.org](https://www.freecodecamp.org) :link:

## Author :pen:
Hi I'm Benedict, I'm learning to become a frontend developer. check out my blog where I'll be sharing my learning experiences, projects, and tips. 
- Checkout it [here](https://benneythedev.hashnode.dev/) :link: 

You can also connect with me on twitter
- [Follow me](https://www.twitter.com/CodewithNtaji) :link: 


