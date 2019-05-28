# HTS-Project
HTS-demo project with blank data, expecially extended for Mandarin Chinese SPSS system.  

2019.04.11  
---create dir 'logs' in the project dir, so you can find most of the logs of step, you can find details in them. Also, it create a log file in the project dir as befrore..  

2019.05.28  
---add option that can use encoder WORLD
------extract 250 utterances with WORLD: 3 minutes  
------extract 250 utterances with WORLD and REAPER: 8 minutes  
---you can use multiprocess with Python in ../project/data/scripts/extract_features_world.py  
---[python scripts/extract_features_world.py /home/shaopf/study/HTS_Demo/HTS-Project00/data 48000 /home/shaopf/study/merlin_Mandarin/tools/bin/WORLD /home/shaopf/study/merlin_Mandarin/tools/bin/REAPER /usr/local/SPTK]  
---then,   
---cd data  
---make cmp  
---make labels  
---cd ..  
---make voice  
------extract 250 utterances with WORLD by multiprocess: 50 seconds  
------extract 250 utterances with WORLD and REAPER: 3 minutes 40 seconds  

