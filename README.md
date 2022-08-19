# Sea Ice
This app displays the monthly mean sea ice extent for the [Arctic](https://rajansingh5264.maps.arcgis.com/home/item.html?id=3cf443035c7049ec91ad214e656a279c) and [Antarctic](https://rajansingh5264.maps.arcgis.com/home/item.html?id=8d65aee3762c4cc1bff6f6e34d766894) along with the historical median extent.

[View it live](https://experience.arcgis.com/experience/7ea2ca77e22144ff9da18a7af20259e6/page/Sea-Ice-Aware/)

![App](./screenshot.png)

## Features

This app displays the monthly mean sea ice extent for the Arctic and Antarctic along with the historical median extent. Additionally, graphs are used to visualize the minimum and maximum extent for each year (top), and the monthly time series for each year (bottom). Use the top graph to select specific years to display in the map.

## Instructions

- Before we begin, make sure you have a fresh version of [Node.js](https://nodejs.org/en/) and NPM installed. The current Long Term Support (LTS) release is an ideal starting point. 

- To begin, clone this repository to your computer:

    ```sh
    https://github.com/vannizhang/sea-ice.git
    ```

- From the project's root directory, install the required packages (dependencies):

    ```sh
    npm install
    ```

 - Now you can start the webpack dev server to test the app on your local machine:

    ```sh
    # it will start a server instance and begin listening for connections from localhost on port 8080
    npm run start
    ```

 - To build/deploye the app, you can simply run:

    ```sh
    # it will place all files needed for deployment into the /dist directory 
    npm run build
    ```

## Resources
- [ArcGIS API for JavaScript (version 4.21)](https://developers.arcgis.com/javascript/index.html)
- [National Snow and Ice Data Center](https://nsidc.org/)
- [D3.js](https://d3js.org/)

## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an issue.

## Disclaimer

This demo application is for illustrative purposes only and it is not maintained. There is no support available for deployment or development of the application.


## Licensing
Copyright 2022 Rajan Kumar Singh

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [LICENSE](license) file.
