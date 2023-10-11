# **My Python Project**

This is a simple implementation of imageBind on a subset of the kinetics400 dataset.

## **Files Description**

### **embeddings.py**
Generates the audio and visual embeddings and saves model to a file called saved_embeddings.pth

### **analysis.py**
Saves the concatenated visual and audio embeddings to a file called concatenated_embeddings.txt. Uses saved_embeddings.pth model.

### **audio_text.py**
Createds audio and text embeddings for the kinetics400 dataset and saved a model called text_audio_embeddings.pth

### **downloads.py**
Downloads videos from kinetics400.
