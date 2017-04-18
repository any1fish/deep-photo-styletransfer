# This readme is for personal project use. It's referring to other projects in my local hard drive.


1. Prepare input images in ~/test/deep-photo-styletransfer/examples/input and .../style folder.
1a. Make sure photos are in png format, and both are scaled to 700px width.
2. Use ~/project/crfasrnn/python-scripts/seg.sh
2a. Make sure segmentations are correctly generated.
3. Use ~/test/deep-photo-styletransfer/gen_laplacian/gen_laplacian.m to generate laplacian arrays.
4. use python gen_all.py to generate the transformed images.
