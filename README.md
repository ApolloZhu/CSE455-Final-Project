# CSE455-Final-Project

## Development Setup

1. clone [https://github.com/ApolloZhu/hagrid](https://github.com/ApolloZhu/hagrid) to some folder `X`
2. Download [`ResNeXt101`](https://n-usr-2uzac.s3pd12.sbercloud.ru/b-usr-2uzac-mv4/models/ResNext101FF.pth) linked in the `Full Frame Classifiers` section of the README file in the above repo, and move the `ResNext101FF.pth` file to the same folder `X` as above
3. Run the `convert_resnet_to_coreml.py` script inside folder `X` using Python 3 to obtain `ResNext101FF.mlmodel`
4. Move `ResNext101FF.mlmodel` from folder `X` to be inside the `BreakfastFinder` folder here (adjacent to e.g. `ViewController.swift`)
