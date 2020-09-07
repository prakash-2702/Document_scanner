# Document_Scanner  

## Table of Contents

* [About the Project](#about-the-project)
  * [File Structure](#file-structure)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Contributors](#contributors)
* [Resources](#resources)


<!-- ABOUT THE PROJECT -->
## About The Project
* 
Building a document scanner with OpenCV involves simple steps:
 Step 1: Detection of edges by canny edge detection method.
 Step 2: Use the edges in the image to find the contours representing the piece of paper being scanned.
 Step 3: Apply a four point transform to obtain the top-down view of the document.
 Step 4: Apply OTSU thresholding to obtain 'black and white' paper effect.
 
### File Structure
    .
    ├── Document_scanner        
    │      ├── doc_scan.py         # Driver code
    │      ├── images              # Images for testing the code
    │          ├── receipt.jpg     # Sample image
    ├── README.md 
<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* Python
* OpenCV
* Numpy
* Argparse
* Imutils

### Installation
1. Clone the repo
```sh
git clone https://github.com/prakash-2702/Document_Scanner.git
```
<!-- CONTRIBUTORS -->
## Contributors
* [Prakash Nadgeri](https://github.com/prakash-2702)
<!-- ACKNOWLEDGEMENTS AND REFERENCES -->
## Resources
* https://www.pyimagesearch.com/2014/09/01/build-kick-ass-mobile-document-scanner-just-5-minutes/
