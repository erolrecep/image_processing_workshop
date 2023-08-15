# Image Processing Workshop


This is a workshop repository that walks you through from getting an image from a webcam or camera 
then using this image on various purposes including extracting features 
for building histogram and applying histogram equalization to change the light of the image for brighter view. Then it
introduces you to necessary ingredients to build a mini document scanner application for you.

## Python Environment Setup
_requirements.txt_ is provided. You can use "virtualenv" or "conda or miniconda" to create a virtual environment to run the project on it.

with virtualenv, 

```shell
      $ mkvirtualenv workshop
      $ pip install -r requirements.txt
```

or

with conda or miniconda,

```shell
    $ conda create -n workshop
    $ conda activate workshop
    $ pip install -r requirements.txt
```

Once you have virtual environment is accessible,

```shell
    (workshop) $ jupyter notebook
```

You can start a Jupyter notebook session.


## Topics to Discuss
The presentation starts with the history of imaging and image processing 
then takes you to today and show you some projects that you may use in the near future. 
For the audience who is new to image processing, 
it would be great for them to learn the historical development of imaging and image processing. 
There are a lot of applications, tools, processes we use every day and almost everywhere, 
but we do not know image processing is the heart of them or a big part of them. 
I just introduce them with these for their image processing understanding.

## Notebooks
 1. Imaging.ipynb
 2. Color Schemes and Color Conversions.ipynb
 3. Histogram & Convolution operations.ipynb 
 4. Drawing on an image with OpenCV.ipynb
 5. Project.ipynb


## Scripts

 1. record_video.py

```shell
    (workshop) $ python record_video.py
```

 2. webcam_stream.py

```shell
    (workshop) $ python webcam_stream.py
```


## Motivation
Document [digitization](https://en.wikipedia.org/wiki/Digitization) is a very, very popular technique to make handwritten or computer produced physical documents available
in computer environment. From medical records to government documents, old books in libraries to historical documents 
that may help us to understand history clearer to make better decisions about today and future.
As you've seen, we have a lot of reasons that makes document digitization is very crucial. Almost every FAANG or most Forbes companies
have their own document scanner tool. Moreover, you can scan a document with your iPhone or 
with some third-party applications on Android, you can easily digitize a document for search or other purposes.



## Future Steps
It would be great to have OCR to read the content of the document and extract to a txt or docx file for further process.

