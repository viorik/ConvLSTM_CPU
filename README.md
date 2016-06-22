### ConvLSTM demo for CPU

A simple demo for using ConvLSTM (CPU version) to generate next frame in a sequence. This demo uses a simple MNIST moving dataset that can be found [here](http://mi.eng.cam.ac.uk/~vp344/).

## Steps to run this code:
* clone this repository on your machine `git clone https://github.com/viorik/ConvLSTM_CPU.git`
* download training and test datasets from [here](http://mi.eng.cam.ac.uk/~vp344/): dataset_fly_64x64_lines_train.t7 and dataset_fly_64x64_lines_train.t7
* specify the paths to the datasets in `opts-mnist.lua`, line 30-31
* run the code using `qlua main-demo-ConvLSTM.lua`

Note that this will run very slowly since it runs on the CPU. Go to [ConvLSTM](https://github.com/viorik/ConvLSTM) for the GPU version.  
