# Automating initial processes
```bash
touch init_setup.sh
```
## Now paste the following code into init_setup.sh
```bash
conda create --prefix ./env python=3.7 -y
conda activate ./env
#pip install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu116
conda install pytorch torchvision torchaudio cudatoolkit=11.3 -c pytorch
pip install -r requirements.txt
```
## Now Run the Following command in terminal
```bash
bash init_setup.sh
```