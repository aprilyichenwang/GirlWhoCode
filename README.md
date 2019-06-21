To bootstrap a new machine:

```
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
sudo python get-pip.py
sudo pip install virtualenv
python -m virtualenv gwc_ds
cd gwc_ds
git clone https://github.com/aprilyichenwang/GirlWhoCode

source bin/activate
pip install -r GirlWhoCode/requirements.txt
cd GirlWhoCode/
jupyter notebook


# clean up the cell 
```
