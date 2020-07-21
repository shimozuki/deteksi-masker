<h1 align="center">Deteksi Masker</h1>


<img src= "https://github.com/shimozuki/deteksi-masker/blob/master/images/2.png" height=500 width=500>

## 🚀&nbsp; Installation
1. Clone the repo
```
$ git clone https://github.com/chandrikadeb7/Face-Mask-Detection.git
```

2. Change your directory to the cloned repo and create a Python virtual environment named 'test'
```
$ mkvirtualenv test
```

3. Now, run the following command in your Terminal/Command Prompt to install the libraries required
```
$ pip3 install -r requirements.txt
```

## :bulb: Working

1. Open terminal. Go into the cloned project directory folder and type the following command:
```
$ python3 train_mask_detector.py --dataset dataset
```

2. Now detect the face masks in images 
```
$ python3 detect_mask_image.py --image images/pic1.jpeg
```

3. Detection in real-time video streams
```
$ python3 detect_mask_video.py 
```
## :key: Results

#### Our model gave 93% accuracy for Face Mask Detection after training via <code>tensorflow-gpu==2.0.0</code>

![](https://github.com/chandrikadeb7/Face-Mask-Detection/blob/master/Readme_images/Screenshot%202020-06-01%20at%209.48.27%20PM.png)

#### We got the following accuracy/loss training curve plot
![](https://github.com/chandrikadeb7/Face-Mask-Detection/blob/master/plot.png)

## :clap: And it's done!
Feel free to mail me for any doubts/query 
:email: chandrikadeb7@gmail.com

## :handshake: Contribution
Feel free to **file a new issue** with a respective title and description on the the [Face-Mask-Detection](https://github.com/chandrikadeb7/Face-Mask-Detection/issues) repository. If you already found a solution to your problem, **I would love to review your pull request**! 

## :heart: Owner
Made with :heart:&nbsp;  by [Chandrika Deb](https://github.com/chandrikadeb7)

## :+1: Credits
* [https://www.pyimagesearch.com/](https://www.pyimagesearch.com/)
* [https://www.tensorflow.org/tutorials/images/transfer_learning](https://www.tensorflow.org/tutorials/images/transfer_learning)

## :eyes: License
MIT © [Robi](https://github.com/shimozuki)
