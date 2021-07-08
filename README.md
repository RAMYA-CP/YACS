# YACS
## Final BD Project
Yet Another Centralized Scheduler(YACS) is a multithreaded centralized scheduler that follows master worker architecture.

### Libraries required
Numpy,
Matplotlib,
json,
socket,
time,
sys,
random,
threading,
os,
datetime,
seaborn,
glob

### Instructions for execution

worker.py, master.py and analysis.py need to be in the same directory. 

python3 master.py config_file_path scheduling_algo_type
scheduling_algo_type RR, LL Or RANDOM

make sure requests.py is sending in requests to port 5000

python3 requests.py no_of_requests

After running the master for all algorithms Run

python3 analysis.py

For visualization
