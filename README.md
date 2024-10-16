# WEB102 Prework - *Video Game Hub*

Submitted by: **Kayla Thornton**

This website displays information about Sea Monster Crowdfunding, a ficticious company that funds video games. The site displays the stats for the company including total amount of individual contributions, total amount raised for all games, how many games the company funds, and the top two most funded games. All games are then displayed at the bottom of the screen and can be filtered by 'All games', 'All funded games', and 'All unfunded games'. 

Time spent: **28** hours spent in total

## Required Features

The following **required** functionality is completed:

* [X] The introduction section explains the background of the company and how many games remain unfunded.
* [X] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [X] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [X] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [x] Changed the appearance of the Stats section to display a background image of a bar graph 

## Video Walkthrough

Here's a walkthrough of implemented features:

<a href='https://www.dropbox.com/scl/fi/89scgfwj0p32vidpgxenp/Kayla_Thornton_Web102_Walkthrough.mp4?rlkey=frt7ku3cf3gy17tstv6xwzi08&st=w9atpbqw&dl=0'>Video Walkthrough</a>

<!-- Replace this with whatever GIF tool you used! -->
GIF created with ... Zoom 
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

Some challenges I encountered while building the app were:
* Issues counting how many unfunded games there are
* * I thought the .reduce() function would work best, but I first thought I had to use it outside the finterUnfundedOnly() function.
  * I didn't know how to access the unfundedGamesArray array outside the function, so the .reduce() was called on the array within the function
* I faced issues implementing the ternary operator in challenge 6 as I was unsure how to save the strings to a variable    

## License

    Copyright [2024] [Kayla Thornton]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
