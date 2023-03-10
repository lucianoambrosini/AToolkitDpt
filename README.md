# Midas modules for Ambrosinus-Toolkit

[![GitHub release](https://img.shields.io/badge/release-v0.0.1-blue)](https://github.com/lucianoambrosini/Ambrosinus-Toolkit/blob/main/latest_version.txt)
[![GitHub PyPI repo](https://img.shields.io/badge/PyPI-repo-yellow)](https://pypi.org/project/atoolkitdpt/)
[![GitHub release date](https://img.shields.io/badge/last%20release%20date-January_2023-green)](https://bit.ly/Ambrosinus-Toolkit)
[![GitHub support forum](https://img.shields.io/badge/Support%20forum-Help-critical)](https://discourse.mcneel.com/t/ambrosinus-toolkit/147124?u=ambrosinus)
[![GitHub license](https://img.shields.io/github/license/lucianoambrosini/Ambrosinus-Toolkit?color=orange)](https://github.com/lucianoambrosini/Ambrosinus-Toolkit/blob/main/LICENSE)

**This Module will be part of Ambrosinus-Toolkit v1.1.9/1.2.0**

This is a Python package for the ["DPTto3D" component](https://github.com/lucianoambrosini/Ambrosinus-Toolkit/tree/main/AI_components/DPT-tools) included in the **Ambrosinus-Toolkit a Grasshopper Plugin**. 

*All credit to each author that developed these Midas scripts.*

I have packaged them and modified some strings of code in order to run them inside Grasshopper. <br /> 
Every file is under the MIT licence.

<br>

<div align="center">
<img src="https://ambrosinus.altervista.org/blog/wp-content/uploads/2022/11/logo_AT-AD-02.png" width="30%" height="30%">
</div>
<br>

## Requirements

In order to run the DPTto3D component (subcategory AI) some python libraries are necessary as the other AI tools, for this reason, I have shared a ["requirements.txt"](https://raw.githubusercontent.com/lucianoambrosini/AToolkitDpt/main/requirements.txt)(right click "Save as") file allowing the designer in this step in a unique command line from cmd.exe (Windows OS side). After downloading the file to a custom folder (I suggest in C:/CustomFolder or something like that) run the following command from cmd.exe after logging in the "CustomFolder": *pip install -r requirements.txt*
<br>

<div align="center">
<img src="https://ambrosinus.altervista.org/blog/wp-content/uploads/2023/02/cmd_installation.jpg" width="90%" height="90%">
</div>

<br>

## Download at least one of these "weights models" a pre-trained datasets by [Intel Labs Research Team](https://github.com/isl-org) 

**MiDaS 3.1**

For highest quality [dpt_beit_large_512](https://github.com/isl-org/MiDaS/releases/download/v3_1/dpt_beit_large_512.pt)

For moderately less quality, but better speed-performance trade-off: [dpt_swin2_large_384](https://github.com/isl-org/MiDaS/releases/download/v3_1/dpt_swin2_large_384.pt)

For embedded devices: [dpt_swin2_tiny_256](https://github.com/isl-org/MiDaS/releases/download/v3_1/dpt_swin2_tiny_256.pt), [dpt_levit_224](https://github.com/isl-org/MiDaS/releases/download/v3_1/dpt_levit_224.pt)

**MiDaS 3.0**: Legacy transformer models [dpt_large_384](https://github.com/isl-org/MiDaS/releases/download/v3/dpt_large_384.pt) and [dpt_hybrid_384](https://github.com/isl-org/MiDaS/releases/download/v3/dpt_hybrid_384.pt)

**MiDaS 2.1**: Legacy convolutional models [midas_v21_384](https://github.com/isl-org/MiDaS/releases/download/v2_1/midas_v21_384.pt) and [midas_v21_small_256](https://github.com/isl-org/MiDaS/releases/download/v2_1/midas_v21_small_256.pt)

<br>
<br>

### Info components
[Article on my website](https://bit.ly/LA-WYSIWYTfromDPTto3D)
