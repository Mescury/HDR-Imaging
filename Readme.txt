pip install -r requirement.txt
python hdr.py -j data\sanctuary\info.json
python alignment.py -j data\exposures\info.json
python tone.py -j data\sanctuary\info.json