
# Budget - Progressive Web App
## Author: WellAndGood

# Table of Contents
* [Overview](#overview)
* [Access](#appearance)
* [Function](#function)
* [Features](#features)
* [Contributors](#contributors)
* [License](#license)

# Overview

This document describes the components of the backend of a progressive web app (PWA). The front-end was created by a third-party. The code being contributed included:
- Updates to the models folder (with an index.js),
- A manifest,
- A service worker for caching the public folder's files,
- An IndexedDB for caching offline API calls, and
- Modifications to the server.js file to allow for Heroku deployment.

# Access 

You can access the `.git` files at: 
https://github.com/WellAndGood/ProgressiveWebApp.git

You can access the deployed application here on Heroku:
https://progressivebudgetpwa.herokuapp.com/

# Function

With these modifications, you can navigate this appliaction both offline and online. You can post changes to your budget by adding or removing funds for line items. All offline publications are cached in its respective IndexedDB objectStore; once online access returns, these indexes are batch-uploaded by API.

## Contributors
Daniel Pisani (WellAndGood)

# Contact
* GitHub account: WellAndGood

## License
This project is licensed under:

### MIT License

Copyright (c) 2021 Daniel Pisani (WellAndGood) 

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.