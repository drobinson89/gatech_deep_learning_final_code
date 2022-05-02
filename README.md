# gatech_deep_learning_final_code
Repo for the code used in the final project of Deep Learning Class

This code is intended to be used in tandem with the project paper and code for using transformers to conduct style transfer linked below.

Paper: https://arxiv.org/pdf/2105.14576.pdf
Supporting code: https://github.com/diyiiyiii/StyTR-2

In the original work, they list the wrong version of torch to be imported. Use 1.8.1. Below are the commands for setting up environement.

sudo update-alternatives --config python3
change to version3.6
install pip: sudo apt-get install python3-pip
upgrade pip: python -m pip install --upgrade
had to install pytorch version 1.8.1
pip install torch==1.8.1+cpu torchvision==0.9.1+cpu torchaudio==0.8.1 -f https://download.pytorch.org/whl/torch_stable.html
upgrade Pil
python3 -m pip install --upgrade Pillow
python3 -m pip install scipy
python3 -m pip install tqdm
python3 -m pip install numpy
python3 -m pip install matplotlib
