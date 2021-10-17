# Parcel v2 path problem
I need to be able to import my assets in html via "relative to final-ouput folder" using "/", as my html pages can be nested. I need this behavior because in my real project I use 11ty to generate these html files: this part with assets import is a common static snippet that is included in every page of the project.

In Parcel v1 it worked fine, by now there is a problem.

## How to run
* `yarn install`
* `yarn dev`