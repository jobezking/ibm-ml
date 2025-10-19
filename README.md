sudo add-apt-repository ppa:deadsnakes/ppa  
sudo apt update && sudo apt upgrade \-y  
sudo apt install python3.14 python3-pip python3.14-venv \-y  
python3.14 \--version  
which python3.14 \#presumes /usr/bin/python3.14  
rm \-rf venv .venv  
/usr/bin/python3.14 \-m venv venv  
source venv/bin/activate

pip3 install \--upgrade pip  
venv/bin/pip3.14 install mglearn openpyxl pandas numpy matplotlib seaborn scikit-learn  
venv/bin/pip3.14 install pandas-stubs  
source venv/bin/activate  
which python  
venv/bin/pip3.14 list  
venv/bin/pip3.14 freeze \> requirements.txt  
\#can be used for pip3 install \-r requirements.txt
