# Towards A New Era of Geo-Foundation Models: Expert-Guided Multimodal Alignment and Geospatial Context Awareness

* Ting Han, Huan Chen, Chaolei Wang, Yilan Ren, Meiliu Wu

## CLIP4Geo

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
git clone https://github.com/Ting-Devin-Han/CLIP4Geo.git
cd CLIP4Geo
```

* Download and Unzip the data

* Google Drive
  * https://drive.google.com/drive/folders/1g2xrnr8b_Kr1FQqhiISEmebjiUAqXEwg?usp=drive_link

* Baidu Disk
  * https://pan.baidu.com/s/1-ubSV02Fke4ATN_QiaqFeQ
  * Password: ggwm

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
* Baidu Disk
  * https://pan.baidu.com/s/1xIOxPhIn5eWUQIMHKZTFqQ
  * Password: vw76

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


