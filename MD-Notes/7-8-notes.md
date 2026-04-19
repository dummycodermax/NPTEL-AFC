# Affective Computing - Week 7

> Lecture 1 - Physiological Signals

- Physiological Signals
- Heart Rate and Emotions
- Skin Conductance and Emotions
- EEG and Emotions

## Physiological Signals
- Signals (ANS - Autonomic Nervous System) can tell what other modalities cant tell (since they can fake)

## Emotion and Physiology
- BP (Blood Pressure)
- ECG (Electrocardiogram)
- EEG (Electroencephalogram)
- EMG (Electromyogram)
- GSR (Galvanic Skin Response)
- HR (Heart Rate)
- RSP (Respiration)
- T (Tempature)

## Heart Rate
- Heart activity is closely linked to arousal
- Overall indicator for physical activation and effort

## Heart Rate measurement
- ECG (Electrocardiography)
- Pulse Rate (PPG - Photoplethysmography) (Dry clips are used so fast and less bothersome)

## Cardiac Parameters
- Heart Rate (HR) (Expressed in bpm)
- Inter-Beat Interval (IBI) (Time interval between individual beats of the hearts generally measured in ms)
- Heart Rate Variability (HRV) - More closely related to emotional arousal and emotional regulation
- Low HRV (Aroused, stress from exercise, psychological events)
- Higher HRV (Relaxed, calm, positive emotions)

## HRV formula
RMSSD = sqrt(mean{(RR1 - RR2)^2 + (RR2 - RR3)^2 + ... + (RRn-1 - RRn)^2})

## Other factors
- ECG can give a much more accurate instantaneous heart rate.
- Assumption for PPG based measurement: Heart rate time-series is stationary.
    - Longer time windows will give more accurate estimates.
    - 5 minutes (60 BPM) = 300 samples
- ECG or PPG data cant tell us whether the arousal was due to +ve or -ve emotions
- They are used to track emotional arousal they are not able to emotional valence

## Skin conductance and Emotions
- When aroused our skin conductance changes aka EDA (Electrodermal Activity)
- Skin conductance is measured using GSR (Galvanic Skin Response) for -ve complexity
- Caused by sweat glands (eccrine glands)
- GSR measurement is done on the palms of the hand and soles of the feet
- GSR response time is 2 to 20 microsiemens to 1 and 2 microsiemens
- Typical rise time is 1 to 3 seconds and recovery time is 2 to 10 seconds
- Data is acquireed with sampling rates between 1 to 10Hz
- SCL (Skin Conductance Level) and SCR (Skin Conductance Response) are the two components of GSR
- Tells how strong is the emotion not +ve or -ve

- Event related
    - Peak amplitude → how strong was the reaction
    - Number of peaks → how many reactions
    - Rise time → how fast it increased

- Frequency features
    - Band: 0.5–5 Hz
    - Measure
        - Min
        - Max
        - Variance

## Electroencephalography (EEG)
- Thousands of neutrons fire in sync to produce electrical activity
- EEG measures the electrical activity of the brain
- EEG is measured using electrodes placed on the scalp
- EEG is non-invasive and can be used to measure brain activity in real-time
- EEG is used to study brain activity in a variety of contexts, including sleep, epilepsy, and brain-computer interfaces
- Electrode placements in Brain
    - Prefrontal (Fp)
    - Frontal (F)
    - Temporal (T)
    - Parietal (P)
    - Occipital (O)
    - Central (C)
    - (Cz)
    - (Fz)
    - (Oz)
- Even numbers right side and left side is for odd numbers
- Frequency bands
    - Delta (0.5-4Hz) - Deep sleep
    - Theta (4-8Hz) - Drowsiness, meditation
    - Alpha (8-12Hz) - Relaxed wakefulness
    - Beta (13-25Hz) - Active thinking, concentration
    - Gamma (30-100Hz) - High-level cognitive processing
- Since electordes are placed on the scalp, they are not able to capture the electrical activity of the brain accurately from the deeper parts

## Assignment - week 7
1. Physiological signals are especially valuable in affect detection because they
    - Cannot be voluntarily controlled and reflect pure emotional states ✅
    - Require full attention from the participant
    - Are easier to fake than facial expressions
    - Are unaffected by wearable technologies

2. Which of the following is not a physiological measure?
    - Respiration
    - Electrocardiogram
    - Heart Rate
    - Eye-blink frequency ✅

3. Heart rate is strongly associated with which dimension of emotion?
    - Valence
    - Arousal ✅
    - Dominance
    - Surprise

4. A key advantage of PPG (Photo-Plethysmography) over ECG is that PPG
    - Provides greater spatial resolution
    - Is quicker to attach and less intrusive ✅
    - Measures electrical pulses directly
    - Requires medical-grade gel electrodes

5. Heart Rate Variability (HRV) measures
    - The average heart rate over the day
    - The electrical intensity of heart contractions
    - The variation in RR intervals between beats ✅
    - The number of peaks in each heartbeat waveform

6. A major limitation of ECG/PPG for affect recognition is that they
    - Only measure emotional valence, not arousal
    - Cannot measure changes over short intervals
    - Are too invasive for most participants
    - Cannot distinguish positive from negative arousal ✅

7. Physiological signals like HR and GSR are less likely to be consciously manipulated compared to facial expressions.
    - True ✅
    - False

8. ECG-based heart rate measurements are more accurate than PPG because
    - They measure electrical activity directly ✅
    - They require fewer sensors
    - They work better at long distances
    - They are less sensitive to motion artifacts

9. GSR can reveal whether the emotional state is positive or negative.
    - True
    - False ✅

10. Low HRV is typically associated with:
    - Relaxation
    - Strong stress or arousal ✅
    - Enhanced emotional control
    - Deep sleep

## Assignment - week 8
1. Skin Conductance (GSR/EDA) measures changes primarily due to
    - Sweat gland activity ✅
    - Body temperature
    - Blood pressure
    - Respiration depth

2. In GSR signals, the fast, event-related component is called
    - SCL (Skin Conductance Level)
    - EDL (Electrodermal Level)
    - SCR (Skin Conductance Response) ✅
    - ERV (Emotional Response Value)

3. GSR can reveal whether the emotional state is positive or negative.
    - True
    - False ✅

4. Skin conductance responses (SCR) correspond to
    - Slow tonic changes in conductivity
    - Rapid, event-related changes triggered by stimuli ✅
    - Changes due to respiration cycles
    - Variations caused only by temperature

5. The most emotionally reactive sweat glands are located on
    - Forehead
    - Knees
    - Palms and soles ✅
    - Back

6. In EEG signals, alpha-band power has what relationship with cortical activity?
    - Direct (more alpha = more activity)
    - Inverse (more alpha = less activity) ✅
    - No relationship
    - Only positive emotions change alpha

7. In multimodal emotion recognition, early fusion requires
    - Combining classifier decisions
    - Using only a single modality
    - Late-stage hypothesis selection
    - Synchronizing signals before concatenation ✅

8. Slow fusion is beneficial because it
    - Avoids all redundancy across modalities
    - Assumes strict independence of cues
    - Exploits correlations while relaxing synchronization requirements ✅
    - Works only with visual cues

9. The SEMAINE project aims to train a system that
    - Engages in multimodal social interaction as a Sensitive Artificial Listener ✅
    - Predicts emotional valence using only speech
    - Detects emotions using physiological sensors alone
    - Generates emotional facial expressions automatically

10. A challenge in multimodal affect data collection is
    - Too many synchronized datasets exist
    - Overabundance of annotated corpora
    - Lack of available audio signals
    - Getting spontaneous, subtle expressions with aligned modalities ✅
