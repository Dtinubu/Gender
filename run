import matplotlib.pyplot as plt
import numpy as np
import argparse
import cv2
import os
import cvlib as cv
import statistics
import math
import argparse
import detect.py


Races =  ('Caucasian','Indian','Asian','African')
for race in Races:
            images_root = os.path.join('/cmlscratch','dtinubu','datasets','RFW','Balancedface','race_per_7000', race)
            temp=[]
            names = os.listdir(images_root)
            for klass, name in enumerate(names):
                name_path=[]
                image_path = os.path.join(images_root, name)
                images_of_person = os.listdir(os.path.join(images_root, name))
                for name in  images_of_person: 
                detect.py --image name
                 if 
            count= count + 1
            data=temp
            data=np.sort(data)
            plt.plot(data,label = race)
            plt.legend()
            plt.savefig('data.png')
            
