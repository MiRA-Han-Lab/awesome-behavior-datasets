# Awesome Behavior Datasets
Open-source datasets for animal behavioral video analysis.


[![Awesome](https://awesome.re/badge.svg)](https://github.com/topics/awesome)
[![Commit](https://img.shields.io/github/last-commit/JackieZhai/awesome-behavior-datasets)](https://github.com/JackieZhai/awesome-behavior-datasets/commits)
[![RepoSize](https://img.shields.io/github/repo-size/JackieZhai/awesome-behavior-datasets)](https://github.com/JackieZhai/awesome-behavior-datasets/archive/refs/heads/master.zip)


## Contents

* [Overview](https://github.com/JackieZhai/awesome-behavior-datasets#overview)
* [Contribution](https://github.com/JackieZhai/awesome-behavior-datasets#contribution)


## Overview

We are mainly focusing connectomics datasets generated by the volume electron microscopy.

<table>
    <tr>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Reference&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br><i>first author/year</i></th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;Name&nbsp;&nbsp;&nbsp;&nbsp;<br><i>for short</i></th>
        <th>Species</th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;Experiment&nbsp;&nbsp;&nbsp;&nbsp;</th>
        <th>Size<br><i>pixel<sup>2</sup></i></th>
        <th>Resolution<br><i>pixel/mm</i></th>
        <th>Length<br><i>d/h/min/s</i></th>
        <th>Rate<br><i>frame/s</i></th>
        <th>Link</th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Note&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</th>
    </tr>
    <tr>
        <td rowspan="2">Pereira <i>et al.</i> 2022</td>
        <td>flies13</td>
        <td>fly</td>
        <td>freely interacting pairs of virgin male and female</td>
        <td>1024x1024</td>
        <td>30.3</td>
        <td>30min</td>
        <td>200</td>
        <td rowspan="2"><a href="https://doi.org/10.17605/OSF.IO/36HAR">data</a><br><a href="https://sleap.ai/datasets">demo</a></td>
        <td>labeled 2,000 frames with a 13 node skeleton</td>
    </tr>
    <tr>
        <td>mice_hc</td>
        <td>mouse</td>
        <td>pairs of male and female in a home cage with bedding</td>
        <td>1280x1024</td>
        <td>1.9</td>
        <td>5min</td>
        <td>40</td>
        <td>labeled 1,474 frames with a 5 node skeleton</td>
    </tr>
    <tr>
        <td>Lauer <i>et al.</i> 2022</td>
        <td>marmosets</td>
        <td>marmoset</td>
        <td>pairs of male and female (one had light blue dye)</td>
        <td>1080x1080</td>
        <td></td>
        <td>9h</td>
        <td>30</td>
        <td><a href="https://benchmark.deeplabcut.org/">data</a></td>
        <td>used 7,600 labeled frames from 40 individuals with 15 body points</td>
    </tr>
    <tr>
        <td rowspan="3">Sturman <i>et al.</i> 2020</td>
        <td>OFT</td>
        <td rowspan="3">mouse</td>
        <td>open field arena (45×45×40 cm)</td>
        <td></td>
        <td></td>
        <td rowspan="2">10min</td>
        <td></td>
        <td rowspan="3"><a href="https://zenodo.org/record/3608658">data</a><br><a href="https://github.com/ETHZ-INS/DLCAnalyzer">labels</a></td>
        <td>distance, time in center, supported rears and unsupported rears were recorded</td>
    </tr>
    <tr>
        <td>EPM</td>
        <td>arms (65.5×5.5 cm) elevated 61.5 cm</td>
        <td></td>
        <td></td>
        <td></td>
        <td>distance, velocity, time in zone (open/closed arms + center) and head dips were recorded</td>
    </tr>
    <tr>
        <td>FST</td>
        <td>beaker (20 cm diameter, 25 cm deep) filled to 17 cm water</td>
        <td></td>
        <td></td>
        <td>6min</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Liu <i>et al.</i> 2020</td>
        <td>a_common_hub</td>
        <td>mouse</td>
        <td></td>
        <td></td>
        <td>30</td>
        <td></td>
        <td></td>
        <td></td>
        <td>labeled ~3,000 random and 5,000 continuous masks, also with EEG and EMG recorded</td>
    </tr>
    <tr>
        <td>Salem <i>et al.</i> 2016</td>
        <td>fisheye_3d</td>
        <td>mouse</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>labeled 6,500 frames with 4 key-points</td>
    </tr>
</table>


## Contribution

* [Hao Zhai](https://github.com/JackieZhai)
* [Haiyang Yan](https://github.com/Qingjia0226)

Please [**contribute**](https://github.com/JackieZhai/awesome-em-datasets/pulls) if you think a new dataset or a relevant paper is missing.
