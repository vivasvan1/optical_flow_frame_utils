This repo contains code for reading and writing .flo, .pfm, .png, .bin, .raw, .ppm and .jpg

All the credits for the code goes to https://github.com/princeton-vl/RAFT/blob/master/core/utils/frame_utils.py

Thank you so much.

I am simply uploading as a python package for easier use for visualizing for my IPython.

Installation:
pip3 install optical-flow-frame-utils

Usage:
from optical_flow_frame_utils import frame_utils
frame_utils.readFlow('/path/to/flow_file.flo')
