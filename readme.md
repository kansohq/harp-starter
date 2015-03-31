## Development

After installing Harp and BrowserSync, you can run Harp and BrowserSync seperately
like this:

* inside the project folder, run:

    harp server

* in another terminal, run:

    browser-sync start --no-notify  --proxy "localhost:9000" --files "public/**/*.*"

To run both you can run:

    npm start

## Build

To build a static version of the site, run:

    harp compile . ./build

A static version of the site will then be available in the build folder. The
contents of the build folder can then be moved to the production environment.
