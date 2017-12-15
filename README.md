# keras-reinforcement-learning-notebook
# Prerequisites
1. Your preferred iPython notebook system (I like [Jupyter](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwju05ie6YvYAhWCyyYKHWBXAIgQFggpMAA&url=http%3A%2F%2Fjupyter.org%2F&usg=AOvVaw2BGkfjMHm2Y7GNO_mDEeDH), which I installed on windows via [Anaconda](https://www.anaconda.com/download/))
2. Key `pip install`:
   * tensorflow (recommend gpu build)
   * keras
   * tqdm
3. Recommended: CuDNN 8.0 from NVidia to get GPU performance.  
# Installation
```
git clone rhdeck/keras-reinforcement-learning-notebook
cd keras-reinforcement-learning-notebook
jupyter notebook
```
And:
* (from browser) Run all Cells

Key things to watch:
1. The training process shows its overall accuracy. Watch it get better over time. 
2. The testing process shows the game being played. This is slow, but very cool.

All credit to @EderSantana for his [article](http://edersantana.github.io/articles/keras_rl/) and useful [gist](https://gist.github.com/EderSantana/c7222daa328f0e885093). This repository reflects my investigations and cleanup to make iPython-based investigation of his findings just a little easier. 


