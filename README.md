# puppeteer-scalingo-buildpack

Installs dependencies needed in order to run puppeteer on Scalingo. Be sure to include `{ args: ['--no-sandbox'] }` in your call to `puppeteer.launch`

## Usage

To use the latest stable version, add the repository url to the `.buildpacks` file at the root of your project.


## Issues

If you run into any issues with this buildpack, please open an issue on this repo and/or submit a PR that resolves it. Different versions of chrome have different dependencies and so some issues can creep in without me knowing. Thanks!
