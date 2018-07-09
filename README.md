# AI Camp - Reinforcement Learning - Project2  

## Installation   
1. Install anaconda3
2. Open a new terminal: $ conda create --name rl_p2 python=3.5
3. $ source activate rl_p2
4. $ git clone https://github.com/IanCyc/RL_P2.git
5. $ cd RL_P1
6. $ pip install -r requirements.txt
7. $ pip install gym[atari]
8. Install ffmpeg      
    Mac OS - : brew install ffmpeg         
             If you have not installed brew in Mac OS，please run follwing command(reference)(https://brew.sh/)):    
             `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`            
    Linux - : $sudo apt-get install ffmpeg            
9. testing: python dqn_atari.py        
Note: If you saw following Error, the environment is good to go. This is caused by incomplete model.
```
ValueError: ('Expected `model` argument to be a `Model` instance, got ', None)
```
