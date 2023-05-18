# SRS_RAN

### Pre-requisite
```
sudo apt-get install cmake make gcc g++ pkg-config libfftw3-dev libmbedtls-dev libsctp-dev libyaml-cpp-dev libgtest-dev
```

### Using binaries provided by Ettus Research
```
# This will install UHD software as well as allow you to receive package updates.

sudo add-apt-repository ppa:ettusresearch/uhd
sudo apt-get update
sudo apt-get install libuhd-dev uhd-host
```
