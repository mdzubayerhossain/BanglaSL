# BanglaSL
Preparation code and data for BanglaSL

## Setup

* download the data from https://drive.google.com/drive/folders/1sNNPkM7jqriOIr9L12f6pnUuVjZRYgJE?usp=share_link . Use data from `video_embedding` or `body_pose_skeletons`
if you want to use video embeddings or skeletons for training respectively.
* copy the `banglsl.dev`, `banglasl.test` and `banglasl.train` files to `data` directory and remove previous contents
* change directory of train, dev and test data in `config\example.yaml`
* change `feature_size` to 274 or 2048 if you want to use skeletons or embeddings respectively
* specify a directory of gloss vocabulary in `signjoey\data.py`
* remove gzip to read data files in `signjoey\dataset.py`
* continue to train using instructions from the repository
