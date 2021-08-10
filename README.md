# AnimeInterp Quickstart

This is a repository to help developers quickly setup AnimeInterp in more recent Python and pytorch versions. For the full implementation, in-depth explanation, as well as the original paper, please visit the original AnimeInterp repository.

## Specs
This tutorial was tested on an environment with the following setup:
* Python 3.6.9
* CUDA 11.2
* torch 1.9.0

## Steps
### Install requirements
```
$ pip3 install -r requirements.txt
```
Aside from the requirements specified in the `requirements.txt` file, it is also necessary to install cupy and torch-scatter. Their versions must support the CUDA and torch versions currently installed.
```
$ pip3 install cupy-cuda112
$ pip3 install --no-index torch-scatter -f https://pytorch-geometric.com/whl/torch-1.9.0+cu102.html
```

## License

AnimeInterp was released under MIT License.
