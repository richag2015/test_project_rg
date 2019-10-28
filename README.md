export_fig
==========
[](https://reactjs.org/) &middot; [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/facebook/react/blob/master/LICENSE) [![npm version](https://img.shields.io/npm/v/react.svg?style=flat)](https://www.npmjs.com/package/react) [![CircleCI Status](https://circleci.com/gh/facebook/react.svg?style=shield&circle-token=:circle-token)](https://circleci.com/gh/facebook/react) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://reactjs.org/docs/how-to-contribute.html#your-first-pull-request) [![](https://img.shields.io/static/v1?label=MATLAB&message=File%20Exchange&color=0076a8&?style=flat&labelColor=d78825)](https://www.mathworks.com/matlabcentral/fileexchange/23629-export_fig) [![Codeship Status for richag2015/test_project_rg](https://app.codeship.com/projects/006a4a10-8af6-0137-8434-4a2b1c33cef4/status?branch=master)](https://app.codeship.com/projects/354960)


A toolbox for exporting figures from MATLAB to standard image and document formats nicely.

### Overview
Exporting a figure from MATLAB the way you want it (hopefully the way it looks on screen), can be a real headache for the unitiated, thanks to all the settings that are required, and also due to some eccentricities (a.k.a. features and bugs) of functions such as `print`. The first goal of export_fig is to make transferring a plot from screen to document, just the way you expect (again, assuming that's as it appears on screen), a doddle.
  
The second goal is to make the output media suitable for publication, allowing you to publish your results in the full glory that you originally intended. This includes embedding fonts, setting image compression levels (including lossless), anti-aliasing, cropping, setting the colourspace, alpha-blending and getting the right resolution.

Perhaps the best way to demonstrate what export_fig can do is with some examples.
