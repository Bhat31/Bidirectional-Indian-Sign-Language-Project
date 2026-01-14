# Bidirectional-Indian-Sign-Language-Project

Bidirectional ISL (Indian Sign Language) to Text involves AI systems that translate sign language gestures into text/speech and spoken/written language back into visual signs, using computer vision (MediaPipe, CNNs) for gesture capture and NLP/deep learning (LSTM, Transformers) for understanding meaning, creating two-way communication for the deaf community by capturing hand movements and converting them to understandable text/speech and vice versa, often using animated avatars or GIFs for the sign-to-visual translation.

## How it Works (Sign-to-Text)

**Gesture Capture:**  
Cameras capture hand movements and body language.

**Landmark Detection:**  
MediaPipe extracts key hand/pose landmarks in real time.

**Feature Extraction:**  
These landmarks form feature vectors, processed by deep learning models (CNNs, LSTMs).

**Classification:**  
The model identifies gestures, translating them into words or sentences.

**Output:**  
Text appears on screen, often with optional Text-to-Speech (TTS) for hearing individuals.

## How it Works (Text-to-Sign)

**Input Processing:**  
NLP techniques analyze written or spoken text (e.g., removing stop words).

**Sign Mapping:**  
Text is mapped to corresponding signs, often using a database of animations.

**Visual Output:**  
Signs are displayed as animated GIFs or 3D avatars, sometimes spelling out words letter-by-letter (fingerspelling) for clarity.

## Key Technologies

**Computer Vision:**  
OpenCV, MediaPipe.

**Deep Learning:**  
CNN, LSTM, BiLSTM, Transformers.

**NLP:**  
NLTK for text processing.

**Hardware:**  
Can run on standard devices like mobiles due to efficient design.

## Goals & Impact

**Inclusivity:**  
Bridges communication gaps between deaf and hearing communities.

**Independence:**  
Reduces reliance on human interpreters in daily life (hospitals, schools, workplaces).

**Accessibility:**  
Promotes easier social interaction and participation.
