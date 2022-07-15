# Automating initial processes
```bash
touch init_setup.sh
```
## Now paste the following code into init_setup.sh
```bash
conda create --prefix ./env python=3.7 -y
conda activate ./env
```
## Now Run the Following command in terminal
```bash
bash init_setup.sh
```