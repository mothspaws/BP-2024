# Bachelor Thesis Repository: Non-Intrusive Speech Quality Assessment

This repository contains source code and example dataset, which were created while writing of my bachelor thesis, which focuses on the non-intrusive estimation of speech signal quality metrics. There are few demonstrations of various audio processing and models predictions.

## Audio Example 1: Combi-En model
Description: Detailed example of the audio processing and model predictions.

### 1. Clean Normalised Speech Signal
- **Audio File**: 8465-246943-0018.flac is a clean signal from Librespeech.
[/System/Volumes/Data/Volumes/Air/projekt/RIR_part/RIR-Generator/reverbs_set/noised_reverb_set/test_10/s/10_angle-30_t160_8465-246943-0018.flac](#)
- **Waveform Image**: ![/Users/mothspaws/Desktop/images for BP/readme/clean1.png](#)

### 2. Generate impulse response based on 30&deg; and wanted T60 level 160 ms
- The cleen normalised speech signal was filtered by generated impulse response.
[/System/Volumes/Data/Volumes/Air/projekt/RIR_part/RIR-Generator/reverbs_set/test_filtered/160/angle-30_t160_8465-246943-0018.flac](#)

### 3. Normalised Noise Component
- **Audio File**: [/Users/mothspaws/Desktop/images for BP/readme/10_angle-30_t160_8465-246943-0018.flac](#)
- **Waveform Image**: ![Normalised Noise Component Image](#)

### 4. Combination of Reverberated Speech and Noise
- **Audio File**: 10_angle-30_t160_8465-246943-0018.flac with noise level 10 dB.
[/System/Volumes/Data/Volumes/Air/projekt/RIR_part/RIR-Generator/reverbs_set/noised_reverb_set/noised_reverb_set/test_10/x/10_angle-30_t160_8465-246943-0018.flac](#)
- **Waveform Image**: ![Combined Signal Image](#)

### 5. Spectrogram
- **Image**: ![Spectrogram Image](#)

### 6. Prediction Graph
- **Description**: This graph shows the comparison of the expected metrics flow and the predicted metrics flow.
- **Image**: ![Prediction Graph Image](#)

### 7. Table: Comparison of Expected and Predicted Metrics
- **Description**: This tables show more detailed comparison of the expected metrics and the predicted metrics.

| Metric            | 1    | 2    | 3    | 4    | 5    | 6    | 7    | 8    | 9    | 10   | 11   | 12   | 13   | 14   |
|-------------------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|
| Expected SNR (dB) | 12.9 | 12.0 | 11.1 | 3.7  | 14.6 | 11.0 | 5.4  | 5.0  | 4.2  | 12.6 | 8.7  | 9.8  | 9.9  | 6.4  |
| Predicted SNR (dB)| 9.0  | 10.5 | 9.3  | 4.0  | 12.6 | 10.3 | 5.3  | 5.5  | 5.5  | 13.4 | 8.0  | 7.3  | 10.6 | 6.7  |

| Metric         | 1    | 2    | 3    | 4    | 5    | 6    | 7    | 8    | 9    | 10   | 11   | 12   | 13   | 14   |
|----------------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|
| Expected STOI  | 0.8  | 0.8  | 0.7  | 0.7  | 0.9  | 0.9  | 0.8  | 0.8  | 0.8  | 0.0  | 0.8  | 0.9  | 0.8  | 0.7  |
| Predicted STOI | 0.8  | 0.7  | 0.7  | 0.8  | 0.8  | 0.8  | 0.8  | 0.8  | 0.8  | 0.2  | 0.8  | 0.8  | 0.7  | 0.7  |



<!-- ## Audio Example 2
[Similar structure as Example 1]

## Audio Example 3
[Similar structure as Example 1]

## Audio Example 4
[Similar structure as Example 1]

## Audio Example 5
[Similar structure as Example 1]

## Audio Example 6
[Similar structure as Example 1] -->
