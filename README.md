<a name="readme-top"></a>



<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/P-DennyGamingYT/PD-Editor">
    <img src="assets/images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">PD Editor</h3>

  <p align="center">
    The #1 Free Lua Editor.
    <br />
    <a href="https://github.com/P-DennyGamingYT/PD-Editor"><strong>Read »</strong></a>
    <br />
    <br />
    <a href="https://github.com/P-DennyGamingYT/PD-Editor/issues">Report Bug</a>
    ·
        <a href="https://p-dennygamingyt.github.io/PD-Editor/Editor.html">Preview</a>
    ·
    <a href="https://dsc.gg/PDennSploit">Discord Server</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#config"></a>Config</li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Credits</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Preview][product-screenshot]](https://p-dennygamingyt.github.io/PD-Editor)

PD-Editor is the #1 choice for a free Lua editor. Whether you are using it for a Lua IDE or an exploit, PD-Editor should be the first choice for your app. PD-Editor not only looks good and is modern, but it's completely free! Visit our [website](https://p-dennygamingyt.github.io/PD-Editor) for a video installation tutorial.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![HTML][Next.js]][Next-url]
* [![JS][React.js]][React-url]
* [![CSS][Vue.js]][Vue-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Getting Started with PD-Editor is easy! Just go to our [website](https://p-dennygamingyt.github.io/PD-Editor) and find the code and video tutorialon how to add PD-Editor to your C# application!

### Installation

1. Download this repo as a .ZIP file.
2. Extract the download .ZIP file.
3. You now have PD-Editor!

To learn how to add PD-Editor into your C# Application, please refer to our [website](https://p-dennygamingyt.github.io/PD-Editor)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

PD-Editor is one of the best choices for a lua text editor, to learn how to add PD-Editor into your C# Application, please refer to our [website](https://p-dennygamingyt.github.io/PD-Editor)

Here are some previews of what the editor looks like.

![Preview](/assets/images/preview.png "Preview")
![Preview w/ minimap](/assets/images/preview-minimap.png "Preview w/ Minimap")
[Video Preview](https://cdn.discordapp.com/attachments/909454431035228181/1007706860238950511/PD-Editor_Preview.mp4?size=4096)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONFIG EXAMPLES -->

PD-Editor is extremely customizable and you can change plenty of settings. Below you can find some examples on how to change or configure PD Editor
to your liking!

```html5
9: --url: url(""); - Displays linked image as the background of the editor.

Example: 

9: --url: url("https://c.tenor.com/LEnMt_4nwEYAAAAC/abstract-astronauts.gif");
```
```html5
95-201: ( big code ) - Allows you to change the colors or other variables in the theme presets (in rgb color settings).

Example:

113: { token: 'comment', foreground: '3517635' }, - Changes the comment color to green.
```
```html5
214: value: '-- PD Editor Made By Payson Holmes' - The default or startup text of the editor.

Example:

214: value: '-- Startup text here\n\n-- Made By Payson Holmes' - Use \n as linebreaks.
```
```html5
216-239: 				theme: "PDark", - The current editor theme (from theme list).
					fontSize: "14px", - The font size of the editor.
					fontFamily: "'JetBrains Mono', Consolas, 'Courier New', monospace", - The current editor font.
					folding: true, - Toggles whether folding is enabled or not.
					dragAndDrop: true, - Toggles whether you can drag and drop files into the editor.
					links: true, - Toggles whether link highlighting is enabled.
					minimap: {
						enabled: false, - Toggles whether to show the minimap.
					},
					showFoldingControls: "always", - Toggles whether to show folding controls
					smoothScrolling: true, - Toggles smooth scrolling.
					stopRenderingLineAfter: 6500, - The number of lines to render when a file is opened.
					cursorBlinking: "smooth", - Cursor blinking animation.
					cursorSmoothCaretAnimation: true, - Toggles smooth cursor animations.
					foldingHighlight: false, - Toggles folding highlighting.
					fontLigatures: true, - Toggles font ligatures.
					formatOnPaste: true, - Toggles whether to format code when pasted or opened.
					showDeprecated: true, - Toggles whether to show depreciated code.
					suggest: {
						snippetsPreventQuickSuggestions: false, - Toggles whether to prevent quick suggestions.
					},
					padding: {
						top: 24, - The editor top padding value.
					}
```
```html5
324-334:		SetTheme = function (themeName) { - If you created a custom theme make sure to add it here so that you can use it!
				if (themeName == 'PDark') {
					monaco.editor.setTheme('PDark') - Custom PD Editor theme
				}
				if (themeName == "Dark") {
					monaco.editor.setTheme("net-theme-dark"); - Dark Theme
				}
				if (themeName == "Light") {
					monaco.editor.setTheme("net-theme-light"); - Light Theme
				}
			}
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [X] Smooth Scrolling
- [X] Smooth Cursor Animations
- [X] Custom Themes
- [X] Ease of Access

See the [open issues](https://github.com/P-DennyGamingYT/PD-Editor/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request.
Don't forget to give the project a star! Thanks!

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Alternatively (faster), you can make a fork of the project, add your feature or changes, then DM me on discord with the format below.

Title: PD Editor - (Proposed Change)
Description: (description of your changes)
GitHub: (link to your version)

Make sure to mention me (@[YT]P-Denny) so I see it faster!

Discord: [@[YT]P-Denny#7313](https://discord.gg/users/820680923887566868) 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Copyright &copy; 2022 - PDennSploit Softworks

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Credits

[Payson Holmes](https://github.com/P-DennyGamingYT) - [@[YT]P-Denny#7313](https://discord.gg/users/820680923887566868) - [paysonholmes@gmail.com](mailto:paysonholmes@gmail.com)

Project Link: [https://github.com/P-DennyGamingYT/PD-Editor](https://github.com/P-DennyGamingYT/PD-Editor)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Thanks to all of you that helped me during the development of PD-Editor.
* [Roblox Developer Forums](https://devforum.roblox.com/)
* [Microsoft](https://microsoft.github.io/monaco-editor/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/P-DennyGamingYT/PD-Editor.svg
[contributors-url]: https://github.com/P-DennyGamingYT/PD-Editor/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/P-DennyGamingYT/PD-Editor.svg
[forks-url]: https://github.com/P-DennyGamingYT/PD-Editor/network/members
[stars-shield]: https://img.shields.io/github/stars/P-DennyGamingYT/PD-Editor.svg
[stars-url]: https://github.com/P-DennyGamingYT/PD-Editor/stargazers
[issues-shield]: https://img.shields.io/github/issues/P-DennyGamingYT/PD-Editor.svg
[issues-url]: https://github.com/P-DennyGamingYT/PD-Editor/issues
[license-shield]: https://img.shields.io/github/license/P-DennyGamingYT/PD-Editor.svg
[license-url]: https://github.com/P-DennyGamingYT/PD-Editor/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: assets/images/preview.png
[Next.js]: https://img.shields.io/badge/html5-%23E34F26.svg?logo=html5&logoColor=white
[Next-url]: https://en.wikipedia.org/wiki/HTML5
[React.js]: https://img.shields.io/badge/javascript-%23323330.svg?logo=javascript&logoColor=yellow
[React-url]: https://en.wikipedia.org/wiki/JavaScript
[Vue.js]: https://img.shields.io/badge/css3-%231572B6.svg?logo=css3&logoColor=white
[Vue-url]: https://en.wikipedia.org/wiki/CSS
[Angular.io]: https://img.shields.io/badge/Angular-DD0031&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
