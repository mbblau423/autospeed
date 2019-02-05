# autospeed
Trying to get results for this competition, https://github.com/commaai/speedchallenge


### Preprocessing Ideas
optical flow:
- https://docs.opencv.org/3.3.1/d7/d8b/tutorial_py_lucas_kanade.html
- https://github.com/dlpbc/comma.ai-speed-challenge

kinetics network:
- https://github.com/deepmind/kinetics-i3d
- https://github.com/djnugent/SpeedNet

Just downsampling and making it black and white? 

### Architecture ideas:
Autoencoder with input of precious frame(s)/speed(s), outputting next frame and speed.
