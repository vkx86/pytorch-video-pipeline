# pytorch-video-pipeline

gst-launch-1.0 filesrc location=/home/vadim/Videos/ktbm-03.mp4 ! decodebin ! progressreport update-freq=1 ! autovideosink

python3 -m venv --system-site-packages .venv