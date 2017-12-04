添加 PPA：
sudo add-apt-repository ppa:fkrull/deadsnakes
sudo apt-get update
安装 Python 3.5：
sudo apt-get install python3.5
sudo apt-get install python3.5-dev


sudo pip install virtualenv
virtualenv -p python3.5 RLPython35
cd RLPython35
source ./bin/activate
deactivate

pip install gym[all](dont use sudo)
https://zhuanlan.zhihu.com/p/28109312
https://mp.weixin.qq.com/s/y1aa_nIimSv4wlprGFHR7g
