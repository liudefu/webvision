# Functions to verify and evaluate WebVision dataset

* Dataset Specification is in config.py.
* Commandline is util.py.
  1. The following command will verify the integrity of the downloaded dataset according to path specified in config.py

     ```$ python util.py --validate```
  2. The following command will evaluate a validation result with top-k accurarcy.

     ```$ python util.py --eval_val /path/to/val.txt --top_k 5```
