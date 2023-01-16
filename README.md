<div id="top"></div>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/linitio/openstack-cloud-rescue-image">
    <img src="images/logo.jpg" alt="Logo" width="150" height="150">
  </a>

<h3 align="center">OpenStack Cloud Rescue</h3>

  <p align="center">
    Simple port of Oracle Linux 9 for OpenStack environments
    <br />
    <a href="https://github.com/linitio/openstack-cloud-rescue-image"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/linitio/openstack-cloud-rescue-image/issues">Report Bug</a>
    ·
    <a href="https://github.com/linitio/openstack-cloud-rescue-image/issues">Request Feature</a>
  </p>
</div>

<!-- ABOUT THE PROJECT -->
## About The Project

This project is a simple port of Oracle Linux 9 from Oracle for OpenStack environments.  
This image is strictly the same that the original, the only change has been made is adding OpenStack datasource for cloud-init.  

This image is updated when Oracle released a new version on their public repository [here](https://yum.oracle.com/oracle-linux-templates.html "Oracle Images Repository").


<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### How to use this image

1. Set your OpenStack environment variables
2. Download the latest image from [release page](https://github.com/linitio/openstack-oracle-linux-image/releases "Release page")
3. Upload image to your OpenStack environment
   ```sh
   openstack image create --disk-format=qcow2 --container-format=bare --min-disk 40 --file OL9U0_x86_64-kvm-b142.qcow2  'Oracle Linux 9'
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the GPL-2.0 License. See `LICENSE.md` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Kevin Allioli - [@linit_io](https://twitter.com/linit_io) - kevin@linit.io

Project Link: [https://github.com/linitio/openstack-oracle-linux-image](https://github.com/linitio/openstack-oracle-linux-image)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/linitio/openstack-amazon-linux-2-image.svg?style=for-the-badge
[contributors-url]: https://github.com/linitio/openstack-oracle-linux-image/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/linitio/openstack-oracle-linux-image.svg?style=for-the-badge
[forks-url]: https://github.com/linitio/openstack-oracle-linux-image/network/members
[stars-shield]: https://img.shields.io/github/stars/linitio/openstack-oracle-linux-image.svg?style=for-the-badge
[stars-url]: https://github.com/linitio/openstack-oracle-linux-image/stargazers
[issues-shield]: https://img.shields.io/github/issues/linitio/openstack-oracle-linux-image.svg?style=for-the-badge
[issues-url]: https://github.com/linitio/openstack-oracle-linux-image/issues
[license-shield]: https://img.shields.io/github/license/linitio/openstack-oracle-linux-image.svg?style=for-the-badge
[license-url]: https://github.com/linitio/openstack-oracle-linux-image/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/kevinallioli
