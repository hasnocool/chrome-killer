**README.md**
========================================


# Chrome Killer
========================================


**Project Title:** Chrome Killer


## Description
--------

I built this to create a simple script that kills all running instances of Chrome and Chromedriver processes. As a developer, I often find myself struggling with these pesky background processes cluttering up my system's resource utilization.

This project aims to provide an easy-to-use solution for those situations where you just need to clean house.


## Features
--------

* Kills all running instances of Chromedriver.exe
* Kills all running instances of chrome.exe


One cool feature is that it uses the `psutil` library, which provides a cross-platform interface for accessing process and system information. This allows us to write portable code that works on Windows, macOS, and Linux.


## Installation
------------

To get started with Chrome Killer, you'll need to install the required libraries:

```bash
pip install psutil
```

**Note:** Make sure you have Python installed (preferably the latest version) before proceeding.


## Usage
-----

1. Clone this repository: `git clone https://github.com/hasnocool/chrome-killer.git`
2. Navigate to the project directory: `cd chrome-killer`
3. Run the script using Python: `python chrome_killer.py`

That's it! You should see a list of killed processes in your console.


## Contributing
------------

If you'd like to contribute to this project, I'm all ears (or rather, eyes)! Feel free to submit pull requests or issues on GitHub. Some areas where I'm thinking about adding improvements include:


* Supporting multiple Chrome profiles
* Implementing a GUI for easier process selection
* Adding more logging and debug functionality


## License
-------

Chrome Killer is licensed under the MIT License.

**See the LICENSE file** for details.


## Tags/Keywords
--------------

chrome, chromedriver, kill processes, psutil, python, system cleanup