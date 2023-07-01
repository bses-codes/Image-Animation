# Video Captioning

## Problem Statement
Video captioning is a challenging task for automatically generating descriptive captions for videos by integrating computer vision and natural language processing techniques. This task involves addressing several key challenges, including handling variable-length videos, capturing temporal dynamics, and ensuring the generation of contextually relevant captions. Variable-length videos require models to adapt to variations in video duration and frame count, necessitating robust strategies to handle this variability effectively. Furthermore, temporal dynamics pose complexities in capturing the evolving actions and events throughout the video. To generate contextually relevant captions, models must accurately identify objects, actions, and maintain coherence in the generated text.

The applications of video captioning span across various domains, such as enhancing accessibility for visually impaired individuals, facilitating efficient video search and retrieval, and enabling effective video summarization. To tackle these challenges and improve the performance of video captioning systems, researchers employ advanced techniques including deep learning architectures and multimodal fusion approaches. These techniques enable the extraction and fusion of visual and textual features, attention mechanisms for emphasising relevant information, and language generation models for generating fluent and coherent captions. By advancing the field of video captioning, researchers strive to enhance the understanding and interpretation of video content, ultimately contributing to advancements in related domains

## Dataset

The MSVD (Microsoft Research Video Description) dataset is a widely used benchmark dataset for video captioning tasks. It was developed by Microsoft Research and consists of video clips collected from YouTube. The dataset is designed to provide video-caption pairs, where each video is associated with multiple human-generated textual descriptions.

### Source of the Dataset:
The MSVD dataset was created by crawling and downloading YouTube videos that met specific criteria, such as having English captions available. The video clips were then annotated with descriptive captions by human annotators. The dataset was released for research purposes to facilitate advancements in video captioning and related fields.

## Possible Approaches
Where different pre-trained CNN models (ResNet101, Inception-v3, etc) can be used as feature extractor along with translation with DNN models.
1. CNN+LSTM (Our Approach)
2. CNN+Transformer
3. CNN+RNN

## Experimentation Tracking Process
1. Spreadsheet
2. NeptuneAI : With Neptune AI, we can store all experimental data, including datasets, model architectures, hyperparameters, and evaluation metrics in one centralised location, making it easier for us to access and share experiment results with our team members.

## Evaluation Metric
Doi: 10.1109/ICIIBMS.2017.8279760 studied different evaluation metrics and suggested four evaluation metrics: BLEU, ROUGE, CIDEr, METEOR.


## Expected Outcome
1. Caption giving information of the video.
2. Evaluation of different approaches in video captioning.
