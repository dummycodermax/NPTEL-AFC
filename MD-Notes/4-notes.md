# Affective Computing - Week 4

> Lecture 1 - Intro to Facial Expression Recognition

## Facial Expression Recognition
- Emotion Recognition
- Expression Recognition

### Inputs to FER
- Electromyography (EMG)
- Electrocardiogram (ECG)
- Electroencephalograph (EEG)
- Earables
- Camera
    - Most informative
    - Non-intrusive

## Static and Dynamic FER

- Static: Extracting handcrafted features from selected peak expression and spatio-temporal features from video

- Dynamic: Has higher recognition rate than static FER because it provides additional temporal information (Differet transition durations and different features so require more compute and time and more data)

## Conventional FER

### Three major Steps
1. Face and Facial components Detection
2. Feature Extraction
3. Classification

### Tools
- YOLO
- OpenFace
- DeepFace

## Deep learning based FER
- E2E learning to occur in the pipeline directly from the input image
- Highly reduce the dependency on face-phyics based models and other pre-processing techniques
- Need a large amount of training data

### Macro expressions
- Obvious and easily perceivable
- Movement of facial parts like mouth, eyes, eyebrows, etc.
- Last for 0.5 to 4 seconds
- Examples: Happiness, Sadness, Anger, Fear, Surprise, Disgust

### Micro expressions
- Spontaneous and subtle facial movements
- Harder to detect
- Last for 0.15 to 0.5 seconds
- Examples: Fleeting smile, slight frown, raised eyebrow

### Facial Action Coding System (FACS)
- Face muscles change to produce facial expressions
- Action units (AUs) are the basic components of facial expressions then we can perceive or predict the emotion

> Lecture 2 - Facial Feature Extraction

## Automatic FER
- Input image
- Face detection
- Feature extraction
- Classification

### Feature extraction
- Geometric features
    - Facial components used to construct a feature vector for training 
    - Position and Angle based, Euclidean distance based, etc.

- Shapes of geometric features alone are insufficient to capture the facial expressions

- Appearance features
    - Skin component basically the texture
    - Raw pixel intensity (Prone to lighting variations)

- Robust Appearance Features
    - Gabor Filters
    - Histograms of Oriented Gradients (HOG) (Change in x and y values for the gradient)
    - SIFT (Scale Invariant Feature Transform) (SIFT facial point detector)

- Appearance features (Higher Time complexity and storage) works better than geometric features (Lower Time complexity and storage)

- Bag of Words (n histogram in n locations in my face let each histrogram be a word and each face is a bag)

- Frequence of occurrence of each word in the bag is the feature vector

- Motion features
    - Optical flow
    - Motion history images
    - Local binary patterns
    - Motion energy images

### Dataset
- CK+ (593 video sequence and 123 sujects ranging from 18 to 30 yrs with both posed and non-posed spontaneous)
- Compound Emotion (CE) Dataset (5060 images - 22 categories with 230 humans - 130 females and 100 males)
- DISFA (Denver Intensity of Spontaneous Facial Affect) (130000 stereo video frames at high res of 27 adults - 12 females and 15 males)
- Binghamton University 3D facial expression (56% female and 44% males - 18 to 70 yrs old)
- Acted Facial Expression (AFEW) Dataset (Method actors from movies collected using subtitle analysis - Age, Gender)


> Lecture 3 - Group level emotions

-  Single pose image of a person and group of people (find the overall perceived emotion)
- Universal, Valence and Arousal

## Factors affeting group
- Grp A and Grp B
- Large face get more weightage
- Large people who are similing in center 
- Top-down affect: Neighbours, scene, group
- Bottom-up affect: Individual expression, Attributes: attractiveness, spontaneous, age, gender, large faces, center faces
- Bar's scene context model"
    - Low resolution holistic representation, similar to scene descriptor 
    - Detailed object level representation, face analysis

## Group Representation

### Top-down
- Object detector (faces): Group Images -> Fully connected graph -> G belongs (V,E) distance between two faces

- Min span tree -> Prim's algorithm 
    - If Theta of i = S_i/avg(size of neighbors)
    - distance of i = centriod of j - location of i

- AFER
    - GEM = Summation of (H_i * Theta_i * d_i)/n

- Deep learning based Group level emotion recognition

- Video based group level emotion 
- Audio video fusion
- Large datasets with specific contexts
- Concensus and consistent labellers
- Copyright issues

> Lecture 4 - Applications of Facial Expression Recognition

## Applications
- Physical Pain
- Depression and Psychological Distress (Unipolar - pysho motor retardation)
- Deception Detection (Micro expression)
- Drowsy Driver Detection
- In-class attention
- Use of additional modalities
    - Depression Voice is more prominent
    - Facial expression used in Gallery in the mobiles

## Limitation
- Real time systems: Computational complexity
- Illumination
- Occlusion
  - Self-occlusion (Heavy beard)
  - External occlusion (Other person blocking the face)
- Subtle facial expression (Micro expression)
- Individual variability
- We need better features and classifiers 
- Ethical issues
  - Fairness
  - Accountability
  - Transparency

### Assignement
1. Which input modality is considered the most informative and non-intrusive for Facial Emotion Recognition (FER)?
   - EMG
   - Camera ✅
   - EEG
   - Earables

2. Dynamic FER generally outperforms static FER because it:
   - Uses more sensors
   - Ignores temporal variations
   - Captures expression transitions over time ✅
   - Removes noise from peak frames

3. The first step in conventional FER pipelines typically involves:
   - Expression classification
   - Texture smoothing
   - Face and facial component detection ✅
   - Motion estimation

4. Deep-learning-based FER systems reduce reliance on:
   - Face-physics-based models and preprocessing ✅
   - Landmark detectors
   - Data augmentation
   - GPU resources

5. Macro expressions typically last:
   - Less than 1/2 second
   - 5–10 seconds
   - Longer than 10 seconds
   - Between 1/2 and 4 seconds ✅

6. Micro expressions are difficult to detect because they:
   - Last longer than macro expressions
   - Are consciously controlled
   - Are brief and often involuntary ✅
   - Do not involve facial muscles

7. Facial Action Coding System (FACS) is based on:
   - Facial muscle movements ✅
   - Wrinkle depth measurements
   - Tracking head pose only
   - Eye aperture changes exclusively

   1. Which appearance-based feature descriptor is sensitive to lighting variations?
   - SIFT
   - Raw pixel intensity values ✅
   - Gabor filters
   - HOG

8. Optical flow is primarily used to extract:
   - Static shape features
   - Texture gradients
   - Motion-based features ✅
   - High-resolution appearance cues

9.  Geometric features alone are sometimes insufficient because different AUs can produce similar landmark changes.
    - True ✅
    - False
