Dataset **COCO 2014** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/H/J/1a/IUgRHxaDmeicWEv4d7xNeFymUl3svXvcMHD9r1A5aiH8hlsGgKIpM80LLL4U3DxRTX1ci6mtrEZXrHeaXUVjUweyK1MER2Wwvu3Nd6Z9TvJzxE3tbjV7b5gL5X73.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='COCO 2014', dst_dir='~/dataset-ninja/')
```
The data in original format can be downloaded here:

- [2014 Train images [83K/13GB]](http://images.cocodataset.org/zips/train2014.zip)
- [2014 Val images [41K/6GB]](http://images.cocodataset.org/zips/val2014.zip)
- [2014 Test images [41K/6GB]](http://images.cocodataset.org/zips/test2014.zip)
- [2014 Train/Val annotations [241MB]](http://images.cocodataset.org/annotations/annotations_trainval2014.zip)
