# Resnet 101 Model
This repo contains the original resnet-101 model.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Training ResNet-101](#training-resnet-101)
- [License](#license)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset (if applicable) and update paths in the code accordingly.

## Usage

Describe how to use your project or provide examples of key functionalities.

```bash
python main.py --option value
```

## Training ResNet-101

If your project involves training a ResNet-101 model, provide instructions on how to do so.

### PyTorch

1. Install PyTorch:

   ```bash
   pip install torch torchvision
   ```

2. Run the training script:

   ```bash
   python train_pytorch_resnet101.py
   ```

### Caffe

1. Install Caffe (follow Caffe installation instructions).

2. Prepare the dataset in LMDB or leveldb format.

3. Run the training command:

   ```bash
   caffe train -solver path/to/solver.prototxt -gpu 0
   ```

Make sure to customize paths and parameters based on your setup.

## License

This project is licensed under the [MIT] License - see the [LICENSE](LICENSE) file for details.
```

