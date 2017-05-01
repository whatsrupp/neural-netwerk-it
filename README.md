# Neural NetWerk
## It's a 2 layer neural network

I've been watching a lot of videos about neural nets for a while now and I actually wanted to investigate the code behind the magic so found a basic tutorial. Nothing earth shattering but still interesting.  The code itself is basically a cut paste of of [this](http://iamtrask.github.io/2015/07/12/basic-python-network/) walk through. I thought there would be more coding and more scope for project-esque expansion but I was wrong. (I.e I'm not sure why this justified a repository build but you live and you learn!)
Instead, spent a considerable amount of time trying to refresh myself on matrix manipulations and learn about back and forward propogations using sigmoid functions.

This particular script trains a function to guess the output of the following dataset.

![alt text](/dataset.png 'dataset')

## Getting this to (net)work
### 1) Clone this repo
```
  cd /wherever/you/want/to/clone/this/repo
  git clone https://github.com/whatsrupp/neural-netwerk-it
```
### 2) Get pip 'n' python 
I'm not going to go into this in too much detail as I'd rather be coding but a quick google for 'installing pip' and 'installing python' should do the job.
### 3) Install dependancies
In this case, only numpy which allows for multidimensional matrix manipulations
```
pip install --user numpy
```

### 4) Execute the python script
```
execfile('neural-net.py')
```
The only output will be 
```
Output After Training:
[[ 0.00966449]
 [ 0.00786506]
 [ 0.99358898]
 [ 0.99211957]]
 ```
 Which is the trained net's guesses at the correct data output.
