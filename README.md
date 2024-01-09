# Automated Video Summarization for Suspicious Event Detection

## Abstract

The increasing use of surveillance cameras to mitigate anomalous events has necessitated the development of automated methods for efficient video analysis and prompt detection of suspicious events. This paper presents a novel approach for automated video summarization utilizing the multi-stage Pipeline technique to identify suspicious events effectively. The proposed method extracts visual features from the input video as discrete events and subsequently classifies these events. Traditional surveillance systems rely on manual monitoring, which is labor-intensive and prone to human error. The paper’s approach focuses on using the OpenCV library to summarize the video. The model created for suspicious activity detection is created using the ConvLSTM and LRCN. The frames are divided into 14 subclasses divided into normal and then thirteen other anomalous events. This classification process enables identifying suspicious events from normal occurrences, contributing to an accurate and reliable detection system. The model was trained using the publicly available DCSASS dataset and then tested on a custom-created dataset consisting of local videos from Pakistan to test its effectiveness in the local context. The results demonstrate that our method provides higher accuracy for both summarization quality and accuracy in detecting anomalous events. By reducing manual efforts and enhancing event detection capabilities, our approach can contribute to the proactive prevention and swift response to security threats, ultimately creating safer environments for society.

## Methodology

The model developed for suspicious activity detection employs ConvLSTM and LRCN to classify frames into 14 subclasses, distinguishing normal events from thirteen other anomalous activities. This classification process aids in identifying suspicious events accurately, contributing to a reliable detection system. The training utilized the publicly available DCSASS dataset and testing on a locally created dataset from Pakistan to ensure effectiveness in the regional context.

## Results

The results demonstrate that our method achieves higher accuracy in both summarization quality and anomalous event detection compared to traditional methods. By reducing manual efforts and enhancing event detection capabilities, our approach plays a vital role in proactive prevention and swift response to security threats, ultimately creating safer environments for society.

## Conclusion

This research presents an automated video summarization approach using advanced deep learning models for effective suspicious event detection. The integration of ConvLSTM, LRCN, and the OpenCV library showcases improved accuracy and reliability in identifying anomalous activities. The application of this method not only reduces manual efforts in surveillance but also contributes to creating safer environments by enabling proactive threat prevention and rapid response to security incidents.
