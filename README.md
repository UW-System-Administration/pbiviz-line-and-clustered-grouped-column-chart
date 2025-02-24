<a id="readme-top"></a>

<br />
<div align="center">
<h1 align="center">pbiviz-line-and-clustered-grouped-column-chart</h1>
  <p>
    Custom Power BI Visual - Line and clustered group column chart
  </p>

</div>

## About The Project
<div style="background:white;">
<img src="https://www.wisconsin.edu/uwsa/wp-content/themes/_tk-uwsa-theme/images/UniversitiesLogoColor.svg" alt="contrib.rocks image" style="display:block;max-width:520px; margin: 0 auto;" />
</div>
<p style="background:red; padding:1em">
THIS REPOSITORY IS MAINTAINED BY UNIVERSITIES OF WISCONSIN-SYSTEM ADMINISTRATION. DO NOT INCLUDE PII, SERVER KEYS, CERTIFICATES, OR ANY SERVER COMPROMISING DATA.
</p>

This is a repository for archival purposes, but could be useful if you want to create your own Power BI visual.

## Getting Started
To get started just clone/fork this repository.

From my experience you will need to debug any Power BI visual using the **web version** of the Power BI service as the Power BI desktop at the moment does not allow for debugging.

After you clone the repository and have the prerequisites installed run `npm install` inside the directory to install the node modules.
<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Prerequisites
Follow current setup at Microsoft's site: https://learn.microsoft.com/en-us/power-bi/developer/visuals/environment-setup

Make sure the following are done:
- Have a Power BI Pro license
- Install IDE (VSCode)
- Have PowerShell 4.0+ installed
- Install Node.js
- Install pbiviz
- Enable Power BI developer mode (web only at the time of creation)
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Debugging
You can debug the Power BI visual using `pbiviz` commands specifically the `pbiviz start` to initiate the communication between your PC and the Power BI web client.

Follow this guide from Microsoft for additional help: https://learn.microsoft.com/en-us/power-bi/developer/visuals/environment-setup
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing
If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>
