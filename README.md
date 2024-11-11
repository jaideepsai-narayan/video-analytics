## Video Analytics:

- **Description:** This notebook enables an interactive chat experience with video input. Using advanced multimodal models like [Video-LLaMA](https://github.com/DAMO-NLP-SG/Video-LLaMA), it allows users to ask questions or interact with the content of a video.

## Verified Environment:
[Intel® Tiber™ Developer Cloud](https://www.intel.com/content/www/us/en/developer/tools/devcloud/services.html)

[Intel® Data Center GPU Max Series](https://www.intel.com/content/www/us/en/products/details/discrete-gpus/data-center-gpu/max-series.html)

## Environment Setup:
Install the required packages:

```pip install -r requirements.txt```

Install [IPEX](https://intel.github.io/intel-extension-for-pytorch/index.html#installation?platform=gpu&version=v2.1.30%2bxpu&os=linux%2fwsl2&package=pip) with the below commands:

```
python -m pip install torch==2.1.0.post2 torchvision==0.16.0.post2 torchaudio==2.1.0.post2 intel-extension-for-pytorch==2.1.30.post0 oneccl_bind_pt==2.1.300+xpu --extra-index-url https://pytorch-extension.intel.com/release-whl/stable/xpu/us/
```
```
python -m pip install setuptools==69.5.1 numpy==1.26.4
```
