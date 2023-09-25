# README
To get this up and running, make sure to follow these steps:
* Clone this repository recursively to also checkout the submodules
* Place any fonts you want to train on in the `fonts` directory at the root of this repository. Make sure to use the actual font name in the code, not the file name.
* Create a `data` directory inside the `tesstrain` directory
* Open the Jupyter notebook and read it carefully. Make adjustments where needed.

### Note:
This was originally used to train a model to reliably recognize the slashed zeros of the "Consolas" font. They were almost always mixed up with 6's, 8's or 9's. You may use this for any kind of finetuning though.
