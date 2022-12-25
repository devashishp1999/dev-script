<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">

<h3 align="center">Instant Functions to use</h3>

  <p align="center">
    Plain JavaScript function so you can focus on your project.
    <br />
    <span><strong>Relaxx! </strong>I got you!</span>
    <br />
    <br />
    <a href="https://github.com/devashishp1999/funkyfunctions/issues">Request a Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS 
<details open>
  <summary>List of FunkyFunctions 👇</summary>
  <ul>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ul>
</details>
-->

<!-- ABOUT THE PROJECT -->

## About The Project

Every website need some common elements to be implemented for a consistent UI/UX. Here are some simple UI components and funtionalities just a function call away. These all functions are a solution to the problems that I faced while developing various websites, I bundled them together and now these funkyFunctions are waiting to get called:

Use these function because:
* Your time should be focused on creating something amazing. A project that solves a problem and helps others
* You shouldn't be writing the same code over and over again.
* You should implement DRY principles to the rest of your life :smile:


### Built With

- [![JavaScript][javascript.com]][javascript-url]
- [![HTML][html.com]][html-url]
- [![CSS][css.com]][css-url]

<!-- GETTING STARTED -->

## How To Get Started

Just Call the *** Function! 😁

### Installation/ Usage

•  Use the source code as is in your project Or include the following CDN link in your HTML.

   ```sh
   https://devashishp1999.github.io/funkyfunctions/main.min.js
   ```

<!-- USAGE EXAMPLES -->

<details close>
  <summary><h2>List of FunkyFunctions 👇</h2></summary>
  <ol>
    <li><a href="#showtoast">showToast()</a></li>
  </ol>
</details>

<span id="showtoast" ></span>

<ol>
  <li><strong>showToast()</strong> : Takes a config. object as an argument and displays a toast on the screen.</li>
  <br />
  
  ```js
  
  // Currently availabe customizations ( Shown values are defaults ) :-
  
  {
    text: "Lorem Ipsum Text",   // Text to display on toast
    posi: 3,                    // Position of toast on the screen.
    time: 4,                    // Display for N seconds.
    fontSize: "1.1rem",         // Text size
    backgroundColor: "#353a40", // Toast BG color
    borderRadius: "4px",        // Border radius
    color: "#fefefe",           // Text color
    fontWeight: "600",          // Font weight
    padding: "1.4vh 3vh",       // Padding
    fontFamily: "Arial",        // Font
  }
  
  ```
<br />

For Position of toast, choose a number between 0-8 to show the toast on various poistions of screen.

  ```js
  // Valid values for "posi" with thier placements on the screen
  
  1---------2---------3
  |         |         |
  8---------0---------4
  |         |         |
  7---------6---------5
  
  ```
  
<br />

Useage : 

```js

// a simple config object
let config = {
  text: "Did you know cats cannot taste sweetness!",
  posi: 7
}

// Shows a simple toast with provided string 
showToast ( config );

```
</ol>

<br />

See the <a href="https://github.com/devashishp1999/funkyfunctions/issues">Open Issues</a> for a full list of proposed features (and known issues).

<!-- CONTRIBUTING -->

## Contributing

Any contributions you make are **greatly appreciated**.

Don't forget to give the project a star!🌟 Thanks again!

<!-- CONTACT -->

## Contact

[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- ACKNOWLEDGMENTS 

## Acknowledgments

- []()
- []()
- []()
-->

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/devashishpujari
[product-screenshot]: images/screenshot.png
[next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[next-url]: https://nextjs.org/
[react.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[react-url]: https://reactjs.org/
[vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[vue-url]: https://vuejs.org/
[angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[angular-url]: https://angular.io/
[svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[svelte-url]: https://svelte.dev/
[laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[laravel-url]: https://laravel.com
[bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[bootstrap-url]: https://getbootstrap.com
[jquery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[jquery-url]: https://jquery.com
[javascript.com]: https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo&logoColor=black
[javascript-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript
[html.com]: https://img.shields.io/badge/HTML-E96228?style=for-the-badge&logo=html
[html-url]: https://developer.mozilla.org/en-US/docs/Web/HTML
[css.com]: https://img.shields.io/badge/CSS-2965F1?style=for-the-badge&logo=CSS&logoColor=black
[css-url]: https://developer.mozilla.org/en-US/docs/Web/CSS


Thank You 😇
  
