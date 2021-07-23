# Blink-To-Speak 🦮

[![](https://img.shields.io/github/license/sourcerer-io/hall-of-fame.svg?colorB=ff0000)](https://github.com/akshaybahadur21/Autopilot/blob/master/LICENSE.txt)  [![](https://img.shields.io/badge/Akshay-Bahadur-brightgreen.svg?colorB=ff0000)](https://akshaybahadur.com)

A simple module for communicating via Morse Code.

## Code Requirements 🦄
You can install Conda for python which resolves all the dependencies for machine learning.

`pip install requirements.txt`

## Morse Code 📇

Morse Code encodes the ISO basic Latin alphabet, some extra Latin letters, the Arabic numerals and a small set of punctuation and procedural signals (prosigns) as standardized sequences of short and long signals called "dots" and "dashes", or "dits" and "dahs", as in amateur radio practice.

## Inspiration ❄️

Inspired from Google's Experiment about how they used morse code to help differently abled people to communicate efficiently. We decided to implement morse code translator using computer vision which isn't that better but a cheaper option. 

## Python  Implementation 👨‍🔬

This project translates morse code in plain english. We used webcam to read blinking of the eyes as dots and dashes which then with the use of a dictionary converts morse to english.

File `morse_converter.py` contains the python dictionary. For reference we have also included the Poster Cards to learn Morse better.

`Short Blink : Dot ' . '`

`Long Blink : Dash ' - '`

`Long Long Blink : Removes the last dot or dash`


## Execution 🐉

```
python3 morse_cv.py
```

## Results 📊

<img src="https://github.com/akshaybahadur21/BLOB/blob/master/bts.gif">

## References 🔱
 
 - [Hello Morse Google IO](https://experiments.withgoogle.com/collection/morse)

