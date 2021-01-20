# Dog_Classifier
Implements an algorithm to detect humans, dogs and a Dog breed classifier
---

 In this project, I built a pipeline to process real-world, user-supplied images. Given an image of a dog, the algorithm `run_app` will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.
 
## Project Instructions
---

1. Clone the repository and navigate to the downloaded folder.

2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/data/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/data/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 
4. Installed the necessary Python packages according to the README in the program repository.
5. Open the notebook and run the notebook.
	
## Packages
---
| Package | Version |
|---|---|
| numpy |  1.12.1|
| PIL | 5.2.0 |
| cv2 (opencv) | 3.3.1 |         
| matplotlib | 2.1.0 |
| tqdm | 4.11.2 |
| torch | 0.4.0 |
| torchvision | 0.2.1 |
| pytorch_model_summary |
