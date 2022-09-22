# Dom Manipulation Assignment

1. Webiste Name: [Dev To](https://dev.to/)

### Topics

    - Query Selctory, Inner HTML

### Sample Image

![Sample One](./Pic1.png)

### Tasks

        Target the Top description div and change the DEV Community to <Your_Name> and description to your passion

```javascript
//change the name
cument.querySelector(".side-bar .crayons-card .crayons-subtitle-2").innerHTML =
  "jaydev";
//change the description
document.querySelector(".side-bar .crayons-card .color-base-70").innerHTML =
  "Hi👋, I'm Jay,Front-end Developer I design and develop experiences that make people's lives simple through Web and Mobile apps. I Work with Figma, HTML5, CSS3, Javascript, React.";
```

### Output

![Output](./Pic2.png)

2. Website Name: [Apple](https://support.apple.com/en-in)

### Task

![Store](./Picture_3.png)

### Fetch all the product name and store in an array

```javascript
let val = document.querySelectorAll(".as-imagegrid-item-title");
let arr = [];
val.forEach((a) => arr.push(a.innerText.split("\n")[0]));
```

### Output

['iPhone', 'Mac', 'iPad', 'Watch', 'AirPods', 'Music', 'TV']

3. Webiste Name: [Youtube Support](https://support.google.com/youtube/)

### Topics

    - Get Element By Id, Create Element, Create Text Node, Append Child

### Sample Image

![Sample One](./Pic4.png)

### Tasks

     Add another FAQ 'My New FAQ' to the list

```javascript
//create h3 element
let h3 = document.createElement("h3");
h3.innerText = "My New FAQ";
//create section element
let section = document.createElement("section");
section.className = "parent";
section.appendChild(h3);
//append the section element inside the nav
let nav = document.querySelector(".accordion-homepage");
nav.appendChild(section);
```

### Output

![Output](./Pic5.png)

4. Webiste Name: [OnePlus](https://www.oneplus.in/support)

### Topics

     Query Selector, InnerText

### Sample Image

![Sample One](./Pic6.png)

### Tasks

      Change the contact number

```javascript
document.querySelector(".one-tel-number").innerText = "+555-505-50";
```

### Output

![Output](./Pic7.png)

5. Webiste Name: [Samsung](https://www.samsung.com/in/offer/online/samsung-fest/)

### Topics

       getElementById, createElement, InnerText, append, setAttribute

### Sample Image

![Sample One](./Pic8.png)

### Tasks

     Target the main div of card and change the Button text to Check out

```javascript
document.querySelector(".diwali-deals-product-sale-btn").innerText =
  "check out";
```

### Output

![Output](./Pic9.png)

6. Webiste Name: [Adidas](https://www.adidas.co.in/)

### Topics

    -   Query Selector, Event listeners, Changing Styles

### Sample Image

![Sample One](./Pic10.png)

### Tasks

     Target the search box and on hover change thebackground color to red.

```javascript
document
  .querySelector(".searchinput___19uW0")
  .addEventListener("mouseover", function () {
    document.querySelector(".searchinput___19uW0").style.backgroundColor =
      "red";
  });
```

### Output

![Output](./Pic11.png)

7. Webiste Name: [MDN Web Docs](https://developer.mozilla.org/en-US/)

### Topics

       Form, Value, Submit

### Sample Image

![Sample One](./Pic12.png)

### Tasks

     To Search a topic in the MDN Search bar.
     First add a text to search in the search bar and then hit the submit search button to search the docs using DOM

```javascript
document.querySelector("#hp-search-input").value = "javascript";
//it'll submit the form
document.querySelector("#hp-search-form").submit();
```

### Output

![Output](./Pic13.png)

8. Webiste Name: [Google](https://www.google.com/)

### Topics

       Remove Elements

### Sample Image

![Sample One](./Pic14.png)

### Tasks

     Remove alternate languages from the home page languages listed

```javascript
//it'll remove the first Element child
document.querySelector("#SIvCob").firstElementChild.remove();
//it'll remove the last element child
document.querySelector("#SIvCob").lastElementChild.remove();
```

### Output

![Output](./Pic15.png)

9. Webiste Name: [Code Wars](https://www.codewars.com/)

### Topics

       Change Font Family, Color of Text.

### Sample Image

![Sample One](./Pic16.png)

### Tasks

    Change the font family of the text to monospace and text color to the logo’s background color.

```javascript
//change the font family
document.querySelector('.display-heading-1').style.fontFamily = 'monospace'
//change the color of the text
document.querySelector('.display-heading-1').style.color = "green"
```

### Output

![Output](./Pic17.png)

10. Webiste Name: [Freecodecamp](https://www.freecodecamp.org/)

### Topics

       querySelector, mouseover, click eventListener,  callback function, style,

### Sample Image

![Sample One](./Pic18.png)

### Tasks

    Target the button and change background colour on mouseover
```javascript
document
  .querySelector(".login-btn-text")
  .addEventListener("mouseover", function () {
    document.querySelector(".login-btn-text").style.backgroundColor =
      "red";
  });
```
### Output

![Output](./Pic19.png)

11. Webiste Name: [realme](https://www.realme.com/in/)

### Topics

       querySelector,style,background-image

### Sample Image

![Sample One](./Pic20.png)

### Tasks

    change the realme logo to ineuron logo

### Output

![Output](./Pic21.png)

12. Webiste Name: [Github](https://github.com/)

### Topics

       querySelector,style,background-Color

### Sample Image

![Sample One](./Pic22.png)

### Tasks

     change the background colour of the button to blue.
```javascript
document.querySelector('.js-repos-container .btn').style.backgroundColor = "blue"
```
### Output

![Output](./Pic23.png)

13. Webiste Name: [Hackerrank](https://www.hackerrank.com/)

### Topics

       querySelector,innerHtml

### Sample Image

![Sample One](./Pic24.png)

### Tasks

Target the top description and change “Matching developers with great companies” to ‘JSBOOTCAMP“.

```javascript
document.querySelector('.fl-heading-text').innerText = "javascript bootcamp"
```

### Output

![Output](./Pic25.png)

14. Webiste Name: [Asus](https://www.asus.com/in/)

### Topics

      querySelector,style,font-size

### Sample Image

![Sample One](./Pic26.png)

### Tasks

       change the fontsize of “Hot Deals” to 80px

```javascript
document.querySelector('.HotDealsAll__Heading__2fIbe').style.fontSize = "80px"
```
### Output

![Output](./Pic27.png)

15. Webiste Name: [Dell](https://www.dell.com/en-in/shop/deals/laptop-deals?gacd=10415953-9016-5761040-285981356-0&dgc=ST&gclid=Cj0KCQjwguGYBhDRARIsAHgRm4-XUDMhhVNyHXb3s1gY4ZBzORr_d9Se-buhJwy7asyUe7YdqEA11eEaAt6UEALw_wcB&gclsrc=aw.ds&nclid=BxjBlpBQsX6pjSHh-L8YYSU77EpfXRkG1AGMB5Wbeu386ykspfrPDnfx_DdFau20)

### Topics

      querySelector,style.textAlign

### Sample Image

![Sample One](./Pic28.png)

### Tasks

       Convert the text “G15 Gaming Laptop” from left to right

```javascript
document.querySelector('.ps-title').style.textAlign = "right"
```
### Output

![Output](./Pic29.png)

16. Webiste Name: [Vercel](https://vercel.com/)

### Topics

     querySelector,innerHTMl

### Sample Image

![Sample One](./Pic30.png)

### Tasks

      change the heading “Start with the developer” to “Start with Scratch”

```javascript
document.querySelector('.section-title_title__VEDfK').innerHTML = "Start With Scratch"
```

### Output

![Output](./Pic31.png)

17. Webiste Name: [Sony](https://www.sony.co.in/)

### Topics

    querySelector,innerHTMl

### Sample Image

![Sample One](./Pic33.png)

### Tasks

     change the button text To current Date.

```javascript
document.querySelector('.buy').innerHTML = new Date()
```
### Output

![Output](./Pic32.png)

18. Webiste Name: [Philips](https://www.philips.co.in/)

### Topics

     querySelector,style,backgroundcolor

### Sample Image

![Sample One](./Pic34.png)

### Tasks

    change the background colour blue to orange

```javascript
document.querySelector('.p-footer').style.backgroundColor = "Orange"
```

### Output

![Output](./Pic35.png)

19. Webiste Name: [Canon](https://in.canon/)

### Topics

          querySelector,src

### Sample Image

![Sample One](./Pic36.png)

### Tasks

    extract the canon logo

```javascript
document.querySelector('.logo').src
```

### Output

![Output](./Pic37.png)

20. Webiste Name: [Oppo](https://www.oppo.com/in/)

### Topics

          querySelector,style,color

### Sample Image

![Sample One](./Pic38.png)

### Tasks

      Change the description colour black to orange
```javascript
document.querySelector('.desc').style.color = "Orange"
```
### Output

![Output](./Pic39.png)
