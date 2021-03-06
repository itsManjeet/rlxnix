<!--
*** Thanks for checking out this README Template. If you have a suggestion that would
*** make this better, please fork the repo and create a pull request or simply open
*** an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
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
[![GPL License][license-shield]][license-url]
![Rust](https://github.com/itsManjeet/rlxnix/workflows/Rust/badge.svg)

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/itsmanjeet/rlxnix.git">
    <img src=".data/logo.png" alt="Logo">
  </a>
  <p align="center">
    An experimental monolithic kernel in rust
    <br />
    <!--a href="https://github.com/itsmanjeet/rlxnix"><strong>Explore the docs »</strong></a-->
    <br />
    <br />
    <!--a href="https://github.com/itsmanjeet/rlxnix">View Demo</a-->
    ·
    <a href="https://github.com/itsmanjeet/rlxnix/issues">Report Bug</a>
    ·
    <a href="https://github.com/itsmanjeet/rlxnix/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Getting Started](#getting-started)
  * [Requirements](#requirements)
  * [Installation and Testing](#installation-and-testing)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)



<!-- GETTING STARTED -->
## Getting Started

rlxnix is a experimental monolithic kernel written in rust for analyzing and learning the internals of operating system in a memory safe language.

### Requirements

- rust, cargo (testing)
- qemu

### Installation and Testing
```bash
    cargo run
```


<!-- ROADMAP -->
## Roadmap

- [x] Target x86_64
- [x] Setup std macros via vga memory (print!,println!)
- [x] Unit testing framework
- [x] Descriptor tables
- [x] IRQ and ISRS
- [x] Implement basic Paging
- [x] Allocator Framework
  - [ ] Buddy allocator ??
- [ ] Multitask Await/Async
- [ ] Virtual filesystem
  - [ ] Initrd Support
- [ ] Usermode
  - [ ] Switch to ring 0 -> 3
  - [ ] Basic syscall support
  - [ ] C runtime libraries
- [ ] Modules Support


See the [open issues](https://github.com/itsmanjeet/rlxnix/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b 0.1.0`)
3. Commit your Changes (`git commit -m '[my-id] my awesome Feature'`)
4. Push to the Branch (`git push origin 0.1.0`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the GPL3 License. See `license` for more information.



<!-- CONTACT -->
## Contact
Manjeet Singh - [@releaxos](https://twitter.com/releaxos) - itsmanjeet@releax.in <br />

[Join](https://discord.gg/TXTxDTYcdg) our discord server for any query


## Acknowledgement

- [https://os.phil-opp.com/](https://os.phil-opp.com/)
- [blog os](https://github.com/phil-opp/blog_os)
- [osdev](https://osdev.org)
- [JamesM's kernel development](http://www.jamesmolloy.co.uk/tutorial_html/)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/itsmanjeet/rlxnix.svg?style=flat-square
[contributors-url]: https://github.com/itsmanjeet/rlxnix/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/itsmanjeet/rlxnix.svg?style=flat-square
[forks-url]: https://github.com/itsmanjeet/rlxnix/network/members
[stars-shield]: https://img.shields.io/github/stars/itsmanjeet/rlxnix.svg?style=flat-square
[stars-url]: https://github.com/itsmanjeet/rlxnix/stargazers
[issues-shield]: https://img.shields.io/github/issues/itsmanjeet/rlxnix.svg?style=flat-square
[issues-url]: https://github.com/itsmanjeet/rlxnix/issues
[license-shield]: https://img.shields.io/github/license/itsmanjeet/rlxnix.svg?style=flat-square
[license-url]: https://github.com/itsmanjeet/rlxnix/blob/master/license
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
