<a href="https://athome.robocup.org"><img src="https://athome.robocup.org/wp-content/uploads/2018/09/cropped-logo_RoboCupAtHome.jpg" title="RoboCup@Home logo" alt="RoboCup@Home logo"></a>

<!-- [![RoboCup@Home logo](https://athome.robocup.org/wp-content/uploads/2018/09/cropped-logo_RoboCupAtHome.jpg)](https://athome.robocup.org) -->

# 2027 Georg@Home Team Description Paper

A Team Description Paper (hereinafter referred as TDP) is an 8-pages long scientific paper, detailing information on the technical and scientific approach of the team's research.

TDPs shall use the [*Springer LNAI format*](http://www.springer.com/computer/lncs?SGWID=0-164-6-793341-0) used in the RoboCup Symposium submissions, and has a hard limit of 8 pages including references.

[![Year](https://img.shields.io/badge/Year-2027-green.svg?style=flat-square)](https://github.com/RoboCupAtHome/RuleBook)
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

## Prerequisites
A complete installation of LaTeX is all that is required to build the template.  
However, we strongly suggest to install make, git, and rubber as well to ease the building.

```bash
sudo apt install texlive-full rubber make git
```

After installing that, clone this repo to your local machine using
```bash
git clone https://github.com/snaens/athome-TDP/
```

## Use
To compile to PDF:
```bash
make
```

To clean up afterwards:
```bash
make clean
```
