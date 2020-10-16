### Spacy challenge

You are given a video stream, many UFO's  are visible on each frame with a different number ranging from 0 - 9 written on them.

Your task is to find the location of those UFO's on each frame, sort them from top to bottom by their position and return numbers written on them.

### Illustration

![](frame.jpg)

In the photo above, if you sort UFO's from top to bottom the numbers written on them will be `[1, 8, 7, 5]`.

while reading frames from the generator, you will also get the answers i.e., numbers sorted from top to bottom, but that's just for validation purpose, you need to find it yourself.

Once you find the location of the UFO's, you need to crop that part and pass it through a classifier to find the number that UFO contains. The classifier is trained on 5000 images. If it doesn't works well, you are welcome to train your own classifier.

**Install requirements**

````
pip3 install -r requirements.txt
````

**To run the application**

````
python3 run.py
````

Rest of the instructions are commented in the files.