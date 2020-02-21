.
├── appearance
│   ├── backbones
│   │   ├── __init__.py
│   │   ├── __pycache__
│   │   │   ├── __init__.cpython-37.pyc
│   │   │   └── resnet.cpython-37.pyc
│   │   ├── resnet.py
│   │   └── vgg.py
│   ├── eval_appearance.py
│   ├── facenet
│   │   └── __init__.py
│   ├── __init__.py
│   ├── loss
│   │   └── __init__.py
│   ├── __pycache__
│   │   └── __init__.cpython-37.pyc
│   ├── train_appearance.py
│   └── utils
│       ├── __init__.py
│       ├── __pycache__
│       │   ├── __init__.cpython-37.pyc
│       │   └── resnet_load_pkl.cpython-37.pyc
│       └── resnet_load_pkl.py
├── configs
│   ├── default.py
│   ├── fcos_detector.yaml
│   ├── __init__.py
│   └── __pycache__
│       ├── default.cpython-37.pyc
│       └── __init__.cpython-37.pyc
├── data
│   ├── eval
│   │   └── objtrack
│   │       ├── images
│   │       │   ├── 0012
│   │       │   │   ├── 000000.png
│   │       │   │   ├── 000001.png
│   │       │   │   ├── 000002.png
│   │       │   │   ├── 000003.png
│   │       │   │   ├── 000004.png
│   │       │   │   ├── 000005.png
│   │       │   │   ├── 000006.png
│   │       │   │   ├── 000007.png
│   │       │   │   ├── 000008.png
│   │       │   │   ├── 000009.png
│   │       │   │   ├── 000010.png
│   │       │   │   ├── 000011.png
│   │       │   │   ├── 000012.png
│   │       │   │   ├── 000013.png
│   │       │   │   ├── 000014.png
│   │       │   │   ├── 000015.png
│   │       │   │   ├── 000016.png
│   │       │   │   ├── 000017.png
│   │       │   │   ├── 000018.png
│   │       │   │   ├── 000019.png
│   │       │   │   ├── 000020.png
│   │       │   │   ├── 000021.png
│   │       │   │   ├── 000022.png
│   │       │   │   ├── 000023.png
│   │       │   │   ├── 000024.png
│   │       │   │   ├── 000025.png
│   │       │   │   ├── 000026.png
│   │       │   │   ├── 000027.png
│   │       │   │   ├── 000028.png
│   │       │   │   ├── 000029.png
│   │       │   │   ├── 000030.png
│   │       │   │   ├── 000031.png
│   │       │   │   ├── 000032.png
│   │       │   │   ├── 000033.png
│   │       │   │   ├── 000034.png
│   │       │   │   ├── 000035.png
│   │       │   │   ├── 000036.png
│   │       │   │   ├── 000037.png
│   │       │   │   ├── 000038.png
│   │       │   │   ├── 000039.png
│   │       │   │   ├── 000040.png
│   │       │   │   ├── 000041.png
│   │       │   │   ├── 000042.png
│   │       │   │   ├── 000043.png
│   │       │   │   ├── 000044.png
│   │       │   │   ├── 000045.png
│   │       │   │   ├── 000046.png
│   │       │   │   ├── 000047.png
│   │       │   │   ├── 000048.png
│   │       │   │   ├── 000049.png
│   │       │   │   ├── 000050.png
│   │       │   │   ├── 000051.png
│   │       │   │   ├── 000052.png
│   │       │   │   ├── 000053.png
│   │       │   │   ├── 000054.png
│   │       │   │   ├── 000055.png
│   │       │   │   ├── 000056.png
│   │       │   │   ├── 000057.png
│   │       │   │   ├── 000058.png
│   │       │   │   ├── 000059.png
│   │       │   │   ├── 000060.png
│   │       │   │   ├── 000061.png
│   │       │   │   ├── 000062.png
│   │       │   │   ├── 000063.png
│   │       │   │   ├── 000064.png
│   │       │   │   ├── 000065.png
│   │       │   │   ├── 000066.png
│   │       │   │   ├── 000067.png
│   │       │   │   ├── 000068.png
│   │       │   │   ├── 000069.png
│   │       │   │   ├── 000070.png
│   │       │   │   ├── 000071.png
│   │       │   │   ├── 000072.png
│   │       │   │   ├── 000073.png
│   │       │   │   ├── 000074.png
│   │       │   │   ├── 000075.png
│   │       │   │   ├── 000076.png
│   │       │   │   └── 000077.png
│   │       │   └── 0012_1
│   │       │       ├── 000000.png
│   │       │       ├── 000001.png
│   │       │       ├── 000002.png
│   │       │       ├── 000003.png
│   │       │       ├── 000004.png
│   │       │       ├── 000005.png
│   │       │       ├── 000006.png
│   │       │       ├── 000007.png
│   │       │       ├── 000008.png
│   │       │       ├── 000009.png
│   │       │       ├── 000010.png
│   │       │       ├── 000011.png
│   │       │       ├── 000012.png
│   │       │       ├── 000013.png
│   │       │       ├── 000014.png
│   │       │       ├── 000015.png
│   │       │       ├── 000016.png
│   │       │       ├── 000017.png
│   │       │       ├── 000018.png
│   │       │       ├── 000019.png
│   │       │       ├── 000020.png
│   │       │       ├── 000021.png
│   │       │       ├── 000022.png
│   │       │       ├── 000023.png
│   │       │       ├── 000024.png
│   │       │       ├── 000025.png
│   │       │       ├── 000026.png
│   │       │       ├── 000027.png
│   │       │       ├── 000028.png
│   │       │       ├── 000029.png
│   │       │       ├── 000030.png
│   │       │       ├── 000031.png
│   │       │       ├── 000032.png
│   │       │       ├── 000033.png
│   │       │       ├── 000034.png
│   │       │       ├── 000035.png
│   │       │       ├── 000036.png
│   │       │       ├── 000037.png
│   │       │       ├── 000038.png
│   │       │       ├── 000039.png
│   │       │       ├── 000040.png
│   │       │       ├── 000041.png
│   │       │       ├── 000042.png
│   │       │       ├── 000043.png
│   │       │       ├── 000044.png
│   │       │       ├── 000045.png
│   │       │       ├── 000046.png
│   │       │       ├── 000047.png
│   │       │       ├── 000048.png
│   │       │       ├── 000049.png
│   │       │       ├── 000050.png
│   │       │       ├── 000051.png
│   │       │       ├── 000052.png
│   │       │       ├── 000053.png
│   │       │       ├── 000054.png
│   │       │       ├── 000055.png
│   │       │       ├── 000056.png
│   │       │       ├── 000057.png
│   │       │       ├── 000058.png
│   │       │       ├── 000059.png
│   │       │       ├── 000060.png
│   │       │       ├── 000061.png
│   │       │       ├── 000062.png
│   │       │       ├── 000063.png
│   │       │       ├── 000064.png
│   │       │       ├── 000065.png
│   │       │       ├── 000066.png
│   │       │       ├── 000067.png
│   │       │       ├── 000068.png
│   │       │       ├── 000069.png
│   │       │       ├── 000070.png
│   │       │       ├── 000071.png
│   │       │       ├── 000072.png
│   │       │       ├── 000073.png
│   │       │       ├── 000074.png
│   │       │       ├── 000075.png
│   │       │       ├── 000076.png
│   │       │       └── 000077.png
│   │       └── labels
│   │           ├── 0000.txt
│   │           ├── 0001.txt
│   │           ├── 0002.txt
│   │           ├── 0003.txt
│   │           ├── 0004.txt
│   │           ├── 0005.txt
│   │           ├── 0006.txt
│   │           ├── 0007.txt
│   │           ├── 0008.txt
│   │           ├── 0009.txt
│   │           ├── 0010.txt
│   │           ├── 0011.txt
│   │           ├── 0012_1.txt
│   │           ├── 0012.txt
│   │           ├── 0013.txt
│   │           ├── 0014.txt
│   │           ├── 0015.txt
│   │           ├── 0016.txt
│   │           ├── 0017.txt
│   │           ├── 0018.txt
│   │           ├── 0019.txt
│   │           └── 0020.txt
│   ├── fcos_res50_checkpoint.pth
│   ├── R-50.pkl
│   └── training
│       ├── objtrack
│       │   ├── images
│       │   │   ├── 0012
│       │   │   │   ├── 000000.png
│       │   │   │   ├── 000001.png
│       │   │   │   ├── 000002.png
│       │   │   │   ├── 000003.png
│       │   │   │   ├── 000004.png
│       │   │   │   ├── 000005.png
│       │   │   │   ├── 000006.png
│       │   │   │   ├── 000007.png
│       │   │   │   ├── 000008.png
│       │   │   │   ├── 000009.png
│       │   │   │   ├── 000010.png
│       │   │   │   ├── 000011.png
│       │   │   │   ├── 000012.png
│       │   │   │   ├── 000013.png
│       │   │   │   ├── 000014.png
│       │   │   │   ├── 000015.png
│       │   │   │   ├── 000016.png
│       │   │   │   ├── 000017.png
│       │   │   │   ├── 000018.png
│       │   │   │   ├── 000019.png
│       │   │   │   ├── 000020.png
│       │   │   │   ├── 000021.png
│       │   │   │   ├── 000022.png
│       │   │   │   ├── 000023.png
│       │   │   │   ├── 000024.png
│       │   │   │   ├── 000025.png
│       │   │   │   ├── 000026.png
│       │   │   │   ├── 000027.png
│       │   │   │   ├── 000028.png
│       │   │   │   ├── 000029.png
│       │   │   │   ├── 000030.png
│       │   │   │   ├── 000031.png
│       │   │   │   ├── 000032.png
│       │   │   │   ├── 000033.png
│       │   │   │   ├── 000034.png
│       │   │   │   ├── 000035.png
│       │   │   │   ├── 000036.png
│       │   │   │   ├── 000037.png
│       │   │   │   ├── 000038.png
│       │   │   │   ├── 000039.png
│       │   │   │   ├── 000040.png
│       │   │   │   ├── 000041.png
│       │   │   │   ├── 000042.png
│       │   │   │   ├── 000043.png
│       │   │   │   ├── 000044.png
│       │   │   │   ├── 000045.png
│       │   │   │   ├── 000046.png
│       │   │   │   ├── 000047.png
│       │   │   │   ├── 000048.png
│       │   │   │   ├── 000049.png
│       │   │   │   ├── 000050.png
│       │   │   │   ├── 000051.png
│       │   │   │   ├── 000052.png
│       │   │   │   ├── 000053.png
│       │   │   │   ├── 000054.png
│       │   │   │   ├── 000055.png
│       │   │   │   ├── 000056.png
│       │   │   │   ├── 000057.png
│       │   │   │   ├── 000058.png
│       │   │   │   ├── 000059.png
│       │   │   │   ├── 000060.png
│       │   │   │   ├── 000061.png
│       │   │   │   ├── 000062.png
│       │   │   │   ├── 000063.png
│       │   │   │   ├── 000064.png
│       │   │   │   ├── 000065.png
│       │   │   │   ├── 000066.png
│       │   │   │   ├── 000067.png
│       │   │   │   ├── 000068.png
│       │   │   │   ├── 000069.png
│       │   │   │   ├── 000070.png
│       │   │   │   ├── 000071.png
│       │   │   │   ├── 000072.png
│       │   │   │   ├── 000073.png
│       │   │   │   ├── 000074.png
│       │   │   │   ├── 000075.png
│       │   │   │   ├── 000076.png
│       │   │   │   └── 000077.png
│       │   │   └── 0012_1
│       │   │       ├── 000000.png
│       │   │       ├── 000001.png
│       │   │       ├── 000002.png
│       │   │       ├── 000003.png
│       │   │       ├── 000004.png
│       │   │       ├── 000005.png
│       │   │       ├── 000006.png
│       │   │       ├── 000007.png
│       │   │       ├── 000008.png
│       │   │       ├── 000009.png
│       │   │       ├── 000010.png
│       │   │       ├── 000011.png
│       │   │       ├── 000012.png
│       │   │       ├── 000013.png
│       │   │       ├── 000014.png
│       │   │       ├── 000015.png
│       │   │       ├── 000016.png
│       │   │       ├── 000017.png
│       │   │       ├── 000018.png
│       │   │       ├── 000019.png
│       │   │       ├── 000020.png
│       │   │       ├── 000021.png
│       │   │       ├── 000022.png
│       │   │       ├── 000023.png
│       │   │       ├── 000024.png
│       │   │       ├── 000025.png
│       │   │       ├── 000026.png
│       │   │       ├── 000027.png
│       │   │       ├── 000028.png
│       │   │       ├── 000029.png
│       │   │       ├── 000030.png
│       │   │       ├── 000031.png
│       │   │       ├── 000032.png
│       │   │       ├── 000033.png
│       │   │       ├── 000034.png
│       │   │       ├── 000035.png
│       │   │       ├── 000036.png
│       │   │       ├── 000037.png
│       │   │       ├── 000038.png
│       │   │       ├── 000039.png
│       │   │       ├── 000040.png
│       │   │       ├── 000041.png
│       │   │       ├── 000042.png
│       │   │       ├── 000043.png
│       │   │       ├── 000044.png
│       │   │       ├── 000045.png
│       │   │       ├── 000046.png
│       │   │       ├── 000047.png
│       │   │       ├── 000048.png
│       │   │       ├── 000049.png
│       │   │       ├── 000050.png
│       │   │       ├── 000051.png
│       │   │       ├── 000052.png
│       │   │       ├── 000053.png
│       │   │       ├── 000054.png
│       │   │       ├── 000055.png
│       │   │       ├── 000056.png
│       │   │       ├── 000057.png
│       │   │       ├── 000058.png
│       │   │       ├── 000059.png
│       │   │       ├── 000060.png
│       │   │       ├── 000061.png
│       │   │       ├── 000062.png
│       │   │       ├── 000063.png
│       │   │       ├── 000064.png
│       │   │       ├── 000065.png
│       │   │       ├── 000066.png
│       │   │       ├── 000067.png
│       │   │       ├── 000068.png
│       │   │       ├── 000069.png
│       │   │       ├── 000070.png
│       │   │       ├── 000071.png
│       │   │       ├── 000072.png
│       │   │       ├── 000073.png
│       │   │       ├── 000074.png
│       │   │       ├── 000075.png
│       │   │       ├── 000076.png
│       │   │       └── 000077.png
│       │   └── labels
│       │       ├── 0000.txt
│       │       ├── 0001.txt
│       │       ├── 0002.txt
│       │       ├── 0003.txt
│       │       ├── 0004.txt
│       │       ├── 0005.txt
│       │       ├── 0006.txt
│       │       ├── 0007.txt
│       │       ├── 0008.txt
│       │       ├── 0009.txt
│       │       ├── 0010.txt
│       │       ├── 0011.txt
│       │       ├── 0012_1.txt
│       │       ├── 0012.txt
│       │       ├── 0013.txt
│       │       ├── 0014.txt
│       │       ├── 0015.txt
│       │       ├── 0016.txt
│       │       ├── 0017.txt
│       │       ├── 0018.txt
│       │       ├── 0019.txt
│       │       └── 0020.txt
│       └── objtrack1
│           ├── images
│           │   ├── 0012
│           │   │   ├── 000000.png
│           │   │   ├── 000001.png
│           │   │   ├── 000002.png
│           │   │   ├── 000003.png
│           │   │   ├── 000004.png
│           │   │   ├── 000005.png
│           │   │   ├── 000006.png
│           │   │   ├── 000007.png
│           │   │   ├── 000008.png
│           │   │   ├── 000009.png
│           │   │   ├── 000010.png
│           │   │   ├── 000011.png
│           │   │   ├── 000012.png
│           │   │   ├── 000013.png
│           │   │   ├── 000014.png
│           │   │   ├── 000015.png
│           │   │   ├── 000016.png
│           │   │   ├── 000017.png
│           │   │   ├── 000018.png
│           │   │   ├── 000019.png
│           │   │   ├── 000020.png
│           │   │   ├── 000021.png
│           │   │   ├── 000022.png
│           │   │   ├── 000023.png
│           │   │   ├── 000024.png
│           │   │   ├── 000025.png
│           │   │   ├── 000026.png
│           │   │   ├── 000027.png
│           │   │   ├── 000028.png
│           │   │   ├── 000029.png
│           │   │   ├── 000030.png
│           │   │   ├── 000031.png
│           │   │   ├── 000032.png
│           │   │   ├── 000033.png
│           │   │   ├── 000034.png
│           │   │   ├── 000035.png
│           │   │   ├── 000036.png
│           │   │   ├── 000037.png
│           │   │   ├── 000038.png
│           │   │   ├── 000039.png
│           │   │   ├── 000040.png
│           │   │   ├── 000041.png
│           │   │   ├── 000042.png
│           │   │   ├── 000043.png
│           │   │   ├── 000044.png
│           │   │   ├── 000045.png
│           │   │   ├── 000046.png
│           │   │   ├── 000047.png
│           │   │   ├── 000048.png
│           │   │   ├── 000049.png
│           │   │   ├── 000050.png
│           │   │   ├── 000051.png
│           │   │   ├── 000052.png
│           │   │   ├── 000053.png
│           │   │   ├── 000054.png
│           │   │   ├── 000055.png
│           │   │   ├── 000056.png
│           │   │   ├── 000057.png
│           │   │   ├── 000058.png
│           │   │   ├── 000059.png
│           │   │   ├── 000060.png
│           │   │   ├── 000061.png
│           │   │   ├── 000062.png
│           │   │   ├── 000063.png
│           │   │   ├── 000064.png
│           │   │   ├── 000065.png
│           │   │   ├── 000066.png
│           │   │   ├── 000067.png
│           │   │   ├── 000068.png
│           │   │   ├── 000069.png
│           │   │   ├── 000070.png
│           │   │   ├── 000071.png
│           │   │   ├── 000072.png
│           │   │   ├── 000073.png
│           │   │   ├── 000074.png
│           │   │   ├── 000075.png
│           │   │   ├── 000076.png
│           │   │   └── 000077.png
│           │   └── 0012_1
│           │       ├── 000000.png
│           │       ├── 000001.png
│           │       ├── 000002.png
│           │       ├── 000003.png
│           │       ├── 000004.png
│           │       ├── 000005.png
│           │       ├── 000006.png
│           │       ├── 000007.png
│           │       ├── 000008.png
│           │       ├── 000009.png
│           │       ├── 000010.png
│           │       ├── 000011.png
│           │       ├── 000012.png
│           │       ├── 000013.png
│           │       ├── 000014.png
│           │       ├── 000015.png
│           │       ├── 000016.png
│           │       ├── 000017.png
│           │       ├── 000018.png
│           │       ├── 000019.png
│           │       ├── 000020.png
│           │       ├── 000021.png
│           │       ├── 000022.png
│           │       ├── 000023.png
│           │       ├── 000024.png
│           │       ├── 000025.png
│           │       ├── 000026.png
│           │       ├── 000027.png
│           │       ├── 000028.png
│           │       ├── 000029.png
│           │       ├── 000030.png
│           │       ├── 000031.png
│           │       ├── 000032.png
│           │       ├── 000033.png
│           │       ├── 000034.png
│           │       ├── 000035.png
│           │       ├── 000036.png
│           │       ├── 000037.png
│           │       ├── 000038.png
│           │       ├── 000039.png
│           │       ├── 000040.png
│           │       ├── 000041.png
│           │       ├── 000042.png
│           │       ├── 000043.png
│           │       ├── 000044.png
│           │       ├── 000045.png
│           │       ├── 000046.png
│           │       ├── 000047.png
│           │       ├── 000048.png
│           │       ├── 000049.png
│           │       ├── 000050.png
│           │       ├── 000051.png
│           │       ├── 000052.png
│           │       ├── 000053.png
│           │       ├── 000054.png
│           │       ├── 000055.png
│           │       ├── 000056.png
│           │       ├── 000057.png
│           │       ├── 000058.png
│           │       ├── 000059.png
│           │       ├── 000060.png
│           │       ├── 000061.png
│           │       ├── 000062.png
│           │       ├── 000063.png
│           │       ├── 000064.png
│           │       ├── 000065.png
│           │       ├── 000066.png
│           │       ├── 000067.png
│           │       ├── 000068.png
│           │       ├── 000069.png
│           │       ├── 000070.png
│           │       ├── 000071.png
│           │       ├── 000072.png
│           │       ├── 000073.png
│           │       ├── 000074.png
│           │       ├── 000075.png
│           │       ├── 000076.png
│           │       └── 000077.png
│           └── labels
│               ├── 0000.txt
│               ├── 0001.txt
│               ├── 0002.txt
│               ├── 0003.txt
│               ├── 0004.txt
│               ├── 0005.txt
│               ├── 0006.txt
│               ├── 0007.txt
│               ├── 0008.txt
│               ├── 0009.txt
│               ├── 0010.txt
│               ├── 0011.txt
│               ├── 0012_1.txt
│               ├── 0012.txt
│               ├── 0013.txt
│               ├── 0014.txt
│               ├── 0015.txt
│               ├── 0016.txt
│               ├── 0017.txt
│               ├── 0018.txt
│               ├── 0019.txt
│               └── 0020.txt
├── datasets
│   ├── data_collect.py
│   ├── FacenetTripletDataset.py
│   ├── __init__.py
│   ├── ObjtrackDataset.py
│   ├── __pycache__
│   │   ├── data_collect.cpython-37.pyc
│   │   ├── __init__.cpython-37.pyc
│   │   ├── ObjtrackDataset.cpython-37.pyc
│   │   └── transform.cpython-37.pyc
│   └── transform.py
├── detection
│   ├── detect.sh
│   ├── eval_det.py
│   ├── heads
│   │   ├── fcos_head.py
│   │   ├── __init__.py
│   │   └── __pycache__
│   │       ├── fcos_head.cpython-37.pyc
│   │       └── __init__.cpython-37.pyc
│   ├── _init_paths.py
│   ├── __init__.py
│   ├── loss
│   │   ├── fcos_loss.py
│   │   ├── __init__.py
│   │   └── __pycache__
│   │       └── fcos_loss.cpython-37.pyc
│   ├── models
│   │   ├── fcos.py
│   │   ├── __init__.py
│   │   └── __pycache__
│   │       └── fcos.cpython-37.pyc
│   ├── necks
│   │   ├── FPN.py
│   │   ├── __init__.py
│   │   └── __pycache__
│   │       ├── FPN.cpython-37.pyc
│   │       └── __init__.cpython-37.pyc
│   ├── __pycache__
│   │   ├── __init__.cpython-37.pyc
│   │   └── _init_paths.cpython-37.pyc
│   ├── test_det.py
│   ├── train_det.py
│   ├── trainer
│   │   ├── FCOStrainer.py
│   │   ├── __init__.py
│   │   ├── __pycache__
│   │   │   ├── FCOStrainer.cpython-37.pyc
│   │   │   ├── __init__.cpython-37.pyc
│   │   │   └── trainer.cpython-37.pyc
│   │   └── trainer.py
│   └── utils
│       ├── box_utils.py
│       ├── __init__.py
│       ├── metrics.py
│       └── __pycache__
│           ├── box_utils.cpython-37.pyc
│           ├── __init__.cpython-37.pyc
│           └── metrics.cpython-37.pyc
├── evaluate.py
├── extensions
│   └── __init__.py
├── inference.py
├── metrics
│   └── __init__.py
├── __pycache__
│   └── _init_paths.cpython-37.pyc
├── README.md
├── requirements.txt
├── TC_tracker.py
├── TNT
│   ├── clusters
│   │   ├── cluster_optimize
│   │   │   ├── cluster_assign.py
│   │   │   ├── cluster_break.py
│   │   │   ├── cluster_merge.py
│   │   │   ├── cluster_split.py
│   │   │   ├── cluster_switch.py
│   │   │   └── __init__.py
│   │   ├── generate_optimal_cluster.py
│   │   ├── init_cluster.py
│   │   ├── __init__.py
│   │   └── utils
│   │       └── __init__.py
│   ├── __init__.py
│   ├── tracklets
│   │   ├── eval_pair_fushion.py
│   │   ├── generate_tracklets.py
│   │   ├── __init__.py
│   │   ├── loss
│   │   │   ├── appearance_change_loss.py
│   │   │   ├── __init__.py
│   │   │   ├── interval_loss.py
│   │   │   ├── smoothness_loss.py
│   │   │   └── velocity_loss.py
│   │   ├── pair_fushion
│   │   │   └── __init__.py
│   │   ├── train_pair_fushion.py
│   │   └── utils
│   │       └── __init__.py
│   └── utils
│       └── __init__.py
├── tree.md
├── units
│   ├── losses.py
│   ├── __pycache__
│   │   ├── losses.cpython-37.pyc
│   │   └── units.cpython-37.pyc
│   └── units.py
├── utils
│   ├── __init__.py
│   ├── pred_loc.py
│   ├── __pycache__
│   │   ├── __init__.cpython-37.pyc
│   │   ├── registry.cpython-37.pyc
│   │   └── utils.cpython-37.pyc
│   ├── registry.py
│   └── utils.py
└── work_dirs
    └── fcos_detector
        └── 2020-02-21-22-54
            ├── events.out.tfevents.1582296891.n224-022-185
            └── train_2020-02-21-22-54_rank0.log

63 directories, 644 files