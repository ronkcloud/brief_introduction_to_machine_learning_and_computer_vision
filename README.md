## Instalation


### Install CUDA
Check your GPU microarchitecture here <a> https://en.wikipedia.org/wiki/CUDA </a>

For example, RTX 3050 has "Ampere" microarchitecture so it is compatible with CUDA SDK version 11.0 onwards (>=11.0)

You can download CUDA SDK Toolkit here <a>https://developer.nvidia.com/cuda-toolkit-archive</a> and install it

Check if it is successfully installed. Open Terminal

```
nvcc --version
```

### Install application
```
pip install uv
```

```
git clone https://github.com/ronkcloud/brief_introduction_to_machine_learning_and_computer_vision.git
```
```
cd brief_introduction_to_machine_learning_and_computer_visio
```

```
uv sync
```

```
uv pip install torch==2.5.1+cu124 torchvision==0.20.1+cu124 torchaudio==2.5.1+cu124 --index-url https://download.pytorch.org/whl/cu124
 ```

Download dataset here <a>https://drive.google.com/file/d/1j4wcvYzSi9d8VKaFOPPyt_5qxk-Dr_kU/view?usp=sharing</a>

Unzip the `dataset.zip` file in the project folder

## Usage


```
uv run jupyter lab
```
Play around with `calculator.ipynb` and `mnist_train.ipynb`

Use `walthrough.pptx` to guide you 