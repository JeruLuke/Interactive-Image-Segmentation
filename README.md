# Interactive-Image-Segmentation

![alt text] (https://github.com/JeruLuke/Interactive-Image-Segmentation/blob/master/ezgif.com-video-to-gif_34.gif)

When was the last time you needed to segment an image?

There are numerous image segmentation algorithms available today. This field in particular has seen numerous contributions over the years. Currently with the onset of deep learning in Computer Vision, neural networks are doing a far better job than nearly every traditional approach built to this day.

However, machines still don't perceive images the way a human eye does. Segmentation goes a long way from merely distinguishing between contrasting colors to figuring out mild differences in subtle gradients. 

With this being said a human-aided/interactive way is needed to segment images properly. This repo uses an open source computer library named OpenCV for the above mentioned purpose.

## Software and Installation

I recommend installing the latest version of OpenCV or atleast 3.0.0 or above. 

## Project Structure 

`Main Folder`
`  --> interactive_segmentation.py`
`  --> interactive_segmentation_arg.py`
`  --> zebra.jpg`
`  --> results`
`       --> Masked_image.jpg`
`       --> Mask.jpg` 

## How to run it?

Open the terminal and navigate to the location of the repo. Execute the following:

`python interactive_segmentation_arg.py --image zebra.jpg`

If you want to run this code on an editor execute the `interactive_segmentation.py` file. Before running ensure the image path is correct. Running the file will open two windows. One window containing the image you want to manually segment. Another wondow contains the segmented portions of the image. 

- If you want to clear what you have done, hit the spacebar. 
- Hit lowercase 's' if you want to save the segmented image and quit. Saved images are stored in the `results` folder. 
- Press the 'Esc' key if you want to quit the program without saving anything.

Two images are produced one is the mask and the other is the masked image. Both these images will be found in the `results` folder.


