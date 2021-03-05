<!--
*** Based on the Best ReadMe Template
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]




<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h3 align="center">League Voice Sync</h3>

  <p align="center">
    An easy VLC based tool to Sync your Voice Com Recordings with a League Replay
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>




<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

* VLC Mediaplayer
  ```sh
  install VLC Mediaplayer from VideoLAN
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/duden/VoiceSync.git
   ```
2. Install dependencies
   ```sh
   pip3 install requests
   pip3 install wxPython
   pip3 install python-vlc
   ```




<!-- USAGE EXAMPLES -->
## Usage

1. Start the Python Project.

2. Start the League Replay and pause it.

3. Use the Media Controls to get the Mediaplayer to a synced position with the Replay.

4. Select the Sync Button to disable MediaControl

5. Control the replay and the Recording stays synced. 







<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/duden/VoiceSync.svg?style=for-the-badge
[contributors-url]: https://github.com/duden/VoiceSync/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/duden/VoiceSync.svg?style=for-the-badge
[forks-url]: https://github.com/duden/VoiceSync/network/members
[stars-shield]: https://img.shields.io/github/stars/duden/VoiceSync.svg?style=for-the-badge
[stars-url]: https://github.com/duden/VoiceSync/stargazers
[issues-shield]: https://img.shields.io/github/issues/duden/VoiceSync.svg?style=for-the-badge
[issues-url]: https://github.com/duden/VoiceSync/issues
[license-shield]: https://img.shields.io/github/license/duden/VoiceSync.svg?style=for-the-badge
[license-url]: https://github.com/duden/VoiceSync/blob/master/LICENSE.txt