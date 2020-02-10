# Invisibility Cloak


Being a harry potter fan I always had a childhood fantasy of using an invisibility cloak. Well, it turns out that you can create this magical experience using an image processing technique called color detection and segmentation. And the good news is, you don’t need to be part of **Hogwarts for that!** All you need is a Red colored cloth and follow this repository.
This [code] turns a `red` colour cloth into an invisibility cloak.

>- It's a fun application which you will enjoy using.
>- You can learn some key functions of opencv from this project. 

---
## How does it work ?

The algorithm is very similar in principle to green screening. But unlike green screening where we remove the background, in this application, we remove the foreground!
We are using a red colored cloth as our cloak. Why red? Why not green? Sure, we could have used green, isn’t red the magician’s color? Jokes aside, colors like green or blue will also work fine with a little bit of tweaking.

> The basic idea is given below:

> - Capture and store the background frame.
> - Detect the red colored cloth using color detection algorithm.
> - Segment out the red colored cloth by generating a mask.
> - Generate the final augmented output to create the magical effect.


## Installation

#### Clone

- Clone this repo to your local machine using `https://github.com/SatYu26/Invisibility-Cloak`

#### Setup/Requirements

> The code is written in Python (`Python3`)
> You need the following libraries
> - numpy
> - OpenCV
> - time
---

## Acknowledgement

https://www.learnopencv.com/invisibility-cloak-using-color-detection-and-segmentation-with-opencv/

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
