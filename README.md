# ML_cybersecurity_lab3
'''bash
├── data 
    └── cl
        └── valid.h5        # this is clean validation data used to design the defense
        └── test.h5         # this is clean test data used to evaluate the BadNet
    └── bd
        └── bd_valid.h5     # this is sunglasses poisoned validation data
        └── bd_test.h5      # this is sunglasses poisoned test data
├── models
    └── bd_net.h5
    └── bd_weights.h5
    └── repaired_2.h5       # B' for X = 2%
    └── repaired_4.h5       # B' for X = 4%
    └── repaired_10.h5      # B' for X = 10%
├── architecture.py
├── ML_Security_Report.pdf  # pdf version of main.ipynb
├── eval.py                 # this is the original evaluation script
├── main.ipynb              # this is colab notebook for lab3
└── myEval.py               # this is my evaluation script
'''

Lab3 for SEL_TOPIC Machine Learning for Cyber Security

Data used in the lab can be downloaded according to the instructioins from the ./Data/data.txt.

You can run the code with the weight w.r.t different rate X={2%, 4%, 10%} from Weight file.
