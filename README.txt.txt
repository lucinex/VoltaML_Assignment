
VIT_BERT Model for Image Captioning.

Dataset Used: Flicker8K
(Link to dataset is inside the notebook, and will be approprietly downloaded in the 
specified location)

Directive:  1. Open the notebook in colab
--------    2. Run cells sequentially. 

Footnotes:
---------
	The directory of the downloaded dataset is structured and utalised as per
authors of Flicker8K

Dataset Github link: https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip
		     https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip

//
Does not include trained_weights
//


Library Versions:
-----------------
pandas == 1.3.5
numpy == 1.21.6
pillow == 7.1.2
transformers == 4.25.1
torch == 1.13.0+cu116
nltk =~ 3.7
CUDA Version: 11.2

Metrics Used:
-------------
	1. CrossEntropy
	2. Average Word Accuracy 


Remarks: Bleu Score is not evaluated as the performance is not well.
-------  The performance obtained is worse than baseline and needs to be re-evaluated but 
	increasing datasize may do the trick. 

