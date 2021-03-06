# CaffeGeo

**This is repository contains a modified version of [Caffe](https://github.com/BVLC/caffe) which supports the HSN, FCN-WeightedBalanced and SegNet(http://mi.eng.cam.ac.uk/projects/segnet/)**

Unpooling layer and weighted balancing are integrated in the original caffe.

The HSN is described in **Hourglass-ShapeNetwork Based Semantic Segmentation for High Resolution Aerial Imagery**, Yu Liu, Duc Minh Nguyen, Nikos Deligiannis, Wenrui Ding, Adrian Munteanu. (http://www.mdpi.com/2072-4292/9/6/522)

## HSN net Specification
HSN network protofile is made available at (https://github.com/Walkerlikesfish/HSNRS.git)

## HSN example
The network trained model is made available at (https://github.com/Walkerlikesfish/HSNRS.git)

## Dataset
The mentioned remote sensing dataset Vaihingen and Potsdam set are available from ISPRS:
http://www2.isprs.org/commissions/comm3/wg4/tests.html

## License and Citation

This extension to the Caffe library is released under a creative commons license which allows for personal and research use only. For a commercial license please contact the authors. You can view a license summary here:
http://creativecommons.org/licenses/by-nc/4.0/

Please cite Caffe and CaffeGeo in your publications if it helps your research:

	@article{liu2017hourglass,
	title={Hourglass-ShapeNetwork Based Semantic Segmentation for High Resolution Aerial Imagery},
	author={Liu, Yu and Minh Nguyen, Duc and Deligiannis, Nikos and Ding, Wenrui and Munteanu, Adrian},
	journal={Remote Sensing},
	volume={9},
	number={6},
	pages={522},
	year={2017},
	publisher={Multidisciplinary Digital Publishing Institute}
	}
