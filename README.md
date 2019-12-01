# Transfer learning

I had a presentation to prepare about a deep learning technique :  Transfer Learning.

With my group, we created a pdf document about TL and how it works.
I created a Python notebook with an example of TL, applied to binary images classification : I used the **horses_or_humans** dataset, one of 
tensorflow's public datasets.

I used tensorflow's hub in order to load a **MobileNet V2** model, which I use as my base model for Transfer learning.

I used this base as a feature extractor
and stacked 2 classifications layers on top to create a three layer model to classify images of horses and humans.

