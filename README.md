# Monte_Carlo_Simulation
![image](https://github.com/ironman850722/Monte_Carlo_Simulation/blob/main/Figures/Result_Form.jpg)
![image](https://github.com/ironman850722/Monte_Carlo_Simulation/blob/main/Figures/Performance_Threads.jpg)
![image](https://github.com/ironman850722/Monte_Carlo_Simulation/blob/main/Figures/Performance_Trials.jpg)

## Introduction
Monte Carlo is a method to estimate probability. The core idea of Monte Carlo Method is based on tons of trials. For example, we know that when we roll a fair dice, the probability of each number shows up is equal to 1/6. If we only do 10 trials or 1000 trials, the real probability may not equal to 1/6. However, if we do 1,000,000 trials, the probability will get closer to its actual probability. Due to the large amount of calculations and trials, Multi-Threads can speedup the performance.  

![image](https://github.com/ironman850722/Monte_Carlo_Simulation/blob/main/Figures/Sample_figure.jpg)

In this project, I simulate that a cannon is going to hit a house on the cliff, and we want to estimate the probability of the cannonball hitting the building. However, we don't know the actual value of the variables but a brief ranges. In order to accurately calculate the probability of the success rate. I utilized those variables, such as the distance of the cannon to the cliff, the height of the cliff, and the building to the cliff. All the variables have been mentioned in the above figure. Calculating the correct probability need lots of trials, so I modified 2 factors "Number of Trials" and "Number of Threads" to see its performance.  
  
## Results  
When using 8 threads under 50 million trials, we can notice that its performance is 730% better than only using 1 thread to run Monte Carlo Simulation. The figure below presents the running result of the program.  
![image](https://github.com/ironman850722/Monte_Carlo_Simulation/blob/main/Figures/Multi_Threads_performance.jpg)  

## How to run the code
1. Install linux environment. Ex. Ubuntu
2. In Ubuntu, type "sudo apt update"
3. Type "sudo apt install build-essential"
4. Type "gcc --version" to check gcc version
5. Go to Codes file and type "./myscript.sh"
