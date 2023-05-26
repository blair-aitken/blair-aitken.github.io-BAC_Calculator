# BAC Calculator

## Overview

The BAC calculator serves as a tool for determining alcohol dosing based on an adjusted Widmark formula. It's designed to assist in estimating the amount of alcohol required to reach a target BAC.

## Table of Contents

- [Overview](#overview)
- [How it Works](#how-it-works)
- [Setup](#setup)
  - [Web-based version](#web-based-version)
  - [Local version](#local-version)
- [How to use](#how-to-use)
- [Disclaimer](#disclaimer)
- [Contact information](#contact-information)

## How it Works

The calculator is based on the Widmark formula, using calculations for estimated total body water (TBW) in men and women. The formulas used are as follows:

**For Men**: `TBW (L)=2.447-(0.09516 × age)+(0.1074 × height)+(0.3362 × weight)`

**For Women**: `TBW (L)=- 2.097+(0.1069 × height)+(0.2466 × weight)`

The tool assumes (1) a 40% alcohol by volume (ABV); (2) a 0.2 elimination rate; (3) a 1:2300 blood to breath ratio, (4) a drinking duration of 10 minutes for 0.05% BAC and 15 minutes for 0.08% BAC; (5) and an expected peak of 30 minutes for .05% BAC and 45 minutes for .08% BAC. These parameters can be modified in the `script.js` JavaScript file.

## Setup

### Web-based version

For the web-based version, go to: https://blair-aitken.github.io/BAC_Calculator

### Local version 

For a local version: 

1. Clone the repository: `git clone https://github.com/YOUR_GITHUB_USERNAME/BAC-Calculator.git`
2. Navigate to the repository's directory: `cd BAC-Calculator`
3. Open the `index.html` file in your browser to use the calculator.

## How to use

After setting up, simply input your details into the calculator fields and it will estimate the amount of alcohol required to reach your desired BAC.

Reccomended dose of alcohol (and mixer) for a `21` year old `male` who is `180` cm tall and weighs `70` kg to reach a BAC of `0.05`.

<br><img src="https://github.com/blair-aitken/BAC_Calculator/assets/131508862/a0fff901-81a3-4945-b7c6-b5541eaadf68" width="400" alt="Sample BAC calculation"><br><br>


## Disclaimer

This calculator is intended for informational purposes only. Please remember that the actual BAC achieved can vary with individual metabolic rates, health status, and other factors. This calculator should not be used to determine whether it is safe to drive or perform other tasks. Always drink responsibly and never drink and drive.

## Contact information
For questions or additional information about this repository, please contact baitken@swin.edu.au.
