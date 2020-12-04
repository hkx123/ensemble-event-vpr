# Event-Based Visual Place Recognition With Ensembles of Temporal Windows

<p align="center">
  <a href="https://qcr.github.io" alt="QUT Centre for Robotics Open Source"><img src="https://github.com/qcr/qcr.github.io/blob/master/misc/badge.svg" /></a>
</p>

We are still preparing the code for public release. In the meantime, please contact tobias.fischer@qut.edu.au if you are interested in the code.

Paper: [10.1109/LRA.2020.3025505](http://doi.org/10.1109/LRA.2020.3025505)

Preprint and additional material: [https://arxiv.org/abs/2006.02826](https://arxiv.org/abs/2006.02826)

Dataset: https://zenodo.org/record/4302805

The [correspondence-event-camera-frame-camera.py](./correspondence-event-camera-frame-camera.py) file contains the mapping between the rosbag names and the consumer camera video names. The variable `video_beginning` indicates the ROS timestamp within the bag file that corresponds to the first frame of the consumer camera video file.
