# fellowship.ai-challenge
Food-101
The motive to create this repository is to provide the effective solution for the fellowship.ai, the challebge is present at the website (https://fellowship.ai/challenge).
The data set taken is present with the link address in the main.ipynb file and in data folder underFood-101 folder.
Recent SoTA is ~80% top-1, 90% top-5.  These approaches rely on lots of TTA, large networks and  even novel architectures.


## Layout
In the Food-101 folder there are data folder and notebook folder. The data folder contains a Bash script that downloads and unzips all of the necessary data, you can download that from the provided website. The notebook contains everything needed to load the data, train the model and ultimately test the model. The notebook is completely self-documenting and describes the process and results in depth.

## Results
Using a variety of data augmentations, progressively resizing the image data from 112->224->512 and training for 34 epochs (~14 hours) I achieved a final accuracy of 88.68%.
