# WEB102 Prework - *Sea Monster Crowdfunding*

Submitted by: **TESFAHUN FOLA**

**Sea Monster Crowdfunding** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **45** hours spent in total

## Required Features

The following **required** functionality is completed:

* [ ] The introduction section explains the background of the company and how many games remain unfunded.
* [ ] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [ ] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [ ] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!
* [ ]  Additional CSS animations for game cards (e.g., fade-in on load) could be implemented for visual appeal.
* [ ] A navigation bar linking to sections (e.g., Stats, Our Games) could improve site navigation.

## Video Walkthrough

Here's a walkthrough of implemented features:

```bash
  [(https://www.loom.com/share/15ec41572ef14948b7c0f65efda7ba6b?sid=4e834c3d-c220-4516-a83c-01a566717b78)]
```

<img src='http://i.imgur.com/link/to/your/gif/file.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->
GIF created with ...  
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

Describe any challenges encountered while building the app.
Challenge 3 (Game Cards): Ensuring proper DOM manipulation with template literals to display game details dynamically required careful handling of HTML structure and CSS styling.

Challenge 5 (Filtering): Implementing deleteChildElements correctly in filter functions was critical to prevent duplicate game cards from accumulating.

Challenge 6 (Company Description): Using the ternary operator for grammatical correctness (e.g., “1 game remains” vs. “7 games remain”) needed precise logic to handle edge cases.

Challenge 7 (Top Games): Sorting and destructuring the games array to display the top two funded games required verifying the sort order and handling game names accurately.

Bonus Feature (Search Bar): Integrating a search function involved adding new HTML elements, styling them consistently with the existing design, and ensuring case-insensitive filtering worked robustly.

General: Debugging CSS flexbox layouts and hover effects to achieve a responsive and visually appealing design was iterative, especially for the game card grid.

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
