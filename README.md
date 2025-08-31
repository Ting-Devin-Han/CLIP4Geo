# Towards A New Era of Geo-Foundation Models: Expert-Guided Multimodal Alignment and Geospatial Context Awareness

* Ting Han, Huan Chen, Chaolei Wang, Yilan Ren, Meiliu Wu

## CLIP4Geo

### Installation

* Install Pytorch following instructions from the official website (We tested in torch 2.0.1 with CUDA 11.8 and 2.1.0 with CUDA 12.1)
 
## GeoRSCLIP Model

### Requirements
<ul>
<li>Python 3.8.0 or above</li>
<li>Pytorch 2.0.1 or above</li>
<li>CUDA 11.3 or above</li>
</ul>

### Installation

````
source install.sh
````


### Quick Start

* Clone this repo

```bash
git clone 
cd CLIP4Geo
```

* Download and Unzip the data

* Google Drive
  * https://

* Baidu Disk
  * https://
  * Password: 

```bash
unzip data/CityVerse.zip
```

* Put the data in the corresponding folders, which are organized as follows.
````
data
|--CityVerse
|  |--train
|  |  |--0000.tar
|  |  |--0001.tar
|  |  |--0002.tar
|  |  |--0003.tar
|  |  |--0004.tar
|  |  |--......
|  |--val
|  |  |--0000.tar
|  |  |--0001.tar
|  |  |--0002.tar
|  |  |--0003.tar
|  |  |--0004.tar
|  |  |--......
...
````

* Download the pretrained model
* Google Drive
  * https://
```bash

```

* Run the script:
```bash
  python inference.py --ckpt-path /your/local/path/to/CLIP4Geo.pt --test-dataset-dir /your/local/path/to/CityVerse
```



## BibTeX Citation

If you use CityVerse or CLIP4Geo in a research paper, we would appreciate using the following citations:

```

```


