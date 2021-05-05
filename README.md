<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/gspetillo/pythagorean-calculator-desktop.svg?style=for-the-badge
[contributors-url]: https://github.com/gspetillo/pythagorean-calculator-desktop/graphs/contributors

[forks-shield]: https://img.shields.io/github/forks/gspetillo/pythagorean-calculator-desktop.svg?style=for-the-badge
[forks-url]: https://github.com/gspetillo/pythagorean-calculator-desktop/network/members

[stars-shield]: https://img.shields.io/github/stars/gspetillo/pythagorean-calculator-desktop.svg?style=for-the-badge
[stars-url]: https://github.com/gspetillo/pythagorean-calculator-desktop/stargazers

[issues-shield]: https://img.shields.io/github/issues/gspetillo/pythagorean-calculator-desktop.svg?style=for-the-badge
[issues-url]: https://github.com/gspetillo/pythagorean-calculator-desktop/issues

[license-shield]: https://img.shields.io/github/license/gspetillo/pythagorean-calculator-desktop.svg?style=for-the-badge
[license-url]: https://github.com/gspetillo/pythagorean-calculator-desktop/blob/master/LICENSE

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555

[linkedin-url]: https://linkedin.com/in/gabrielpetillo
[product-screenshot]: ./assets/app-print.png


[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/gspetillo/pythagorean-calculator-desktop">
    <img src="./assets/icons/png/32x32.png" alt="Logo">
  </a>

  <h3 align="center">Pythagorean Calculator</h3>

  <p align="center">
    Simple Pythagorean Theorem Calculator Native Desktop Application
    <br />
    <a href="https://github.com/gspetillo/pythagorean-calculator-desktop"><strong>Explore the docs »</strong></a>
    <br />
    <a href="https://github.com/gspetillo/pythagorean-calculator-desktop/issues">Report Bug</a>
    ·
    <a href="https://github.com/gspetillo/pythagorean-calculator-desktop/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#related-repositories">Related Repositories</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![Product Name Screen Shot][product-screenshot]

Development of a simple calculator desktop application for a job interview test.

The main features of this application are:
* Calculation of the hypotenuse from the two sides;
* Calculation of the side from the hypotenuse and the other side;
* Button to copy the result to the device's clipboard;
* Button to clear form fields;


### Built With

The main technologies used for the development of this project are:

* [Electron](https://www.electronjs.org/)

### Related Repositories

Other repositories related to the development of this project:

* [pythagorean-calculator](https://github.com/gspetillo/pythagorean-calculator)
* [pythagorean-calculator-api](https://github.com/gspetillo/pythagorean-calculator-api)



<!-- GETTING STARTED -->
## Getting Started

To clone and run this project locally, follow these simple example steps:

### Prerequisites

To run this project, you need to install:
* [Node JS](https://nodejs.org/en/download/)

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/gspetillo/pythagorean-calculator-desktop.git
   ```
2. Install the dependencies
   ```sh
   npm install
   ```
3. Run project
    ```sh
    npm start
    ```
### Build Application

1. Pull `electron-packager` dependency from `npm`
   ```sh
   npm install electron-packager -g
   ```
2. Run packager and generate `/release-builds` directory
    ```sh
    electron-packager . --overwrite --platform=win32 --arch=ia32 --prune=true --out=release-builds --version-string.CompanyName=CE --version-string.FileDescription=CE --version-string.ProductName="Pythagorean Calculator"
    ```
3. Run application by executing `pythagorean-calculator.exe` file on project directory
    ```sh
    start ./release-builds/pythagorean-calculator-win32-ia32/pythagorean-calculator.exe
    ```


<!-- USAGE EXAMPLES -->
## Usage

This website can be used to perform simple calculations involving the Pythagorean theorem. The main formulas of this theorem used in this project are:

<img src="https://uploads-cdn.omnicalculator.com/images/geometry/area/right-triangle.svg">
<br><br>

```c = √(a² + b²)```

```a = √(c² - b²)``` or ```b = √(c² - a²)```

_For examples, please acess [Khan Academy](https://www.khanacademy.org/math/cc-eighth-grade-math/cc-8th-geometry/cc-8th-pythagorean-theorem/v/the-pythagorean-theorem#:~:text=The%20Pythagorean%20theorem%20consists%20of%20a%20formula%20a%5E2%2Bb,triangle%20(Opposite%20and%20Adjacent).)_.



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project _(Fork button on Github)_
```sh
start https://github.com/gspetillo/pythagorean-calculator-desktop
```
2. Create your Feature Branch 
```sh
git checkout -b feature/AmazingFeature
```
3. Commit your Changes 
```sh
git commit -m 'Add some AmazingFeature'
```
4. Push to the Branch 
```sh
git push origin feature/AmazingFeature
```
5. Open a Pull Request _(Pull Request page on Github)_

```sh
start https://github.com/gspetillo/pythagorean-calculator-desktop/pulls
```

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Gabriel Petillo - [Linkedin](https://www.linkedin.com/in/gabrielpetillo) - [Github](https://github.com/gspetillo/) - [Medium](https://medium.com/@gspetillo) - [Email](gspetillo@gmail.com)

Project Link: [https://github.com/gspetillo/pythagorean-calculator-desktop](https://github.com/gspetillo/pythagorean-calculator-desktop)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Favicon Generator](https://www.favicon-generator.org/)


