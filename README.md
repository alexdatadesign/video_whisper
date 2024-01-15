# Video Whisper

## An experimental set of colab notebooks for video semantic segmentation.

[Colab Notebook Link](https://colab.research.google.com/drive/1ARD4NwI_wZ34YnqqYXx7owptbn4JJGg7?usp=sharing) 

The set of steps implemented:

- text exctraction (transcription) from the youtube video with the latest ASR model: 'openai/whisper-large-v3'
- text topic modeling with the BERTopic and HDBSCAN clustering
- video scene segmentation with PySceneDetect


Use Google Colab Notebook with GPU. 

Video timeline visualization with website text:

![video timeline](/docs/timeline.png)


Workflow diagram:

![workflow diagram](/docs/video_segmentation_diagram.svg)

