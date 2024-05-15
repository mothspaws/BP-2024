# Bachelor Thesis Repository: Non-Intrusive Speech Quality Assessment

This repository contains source code and example dataset, which were created while writing of my bachelor thesis, which focuses on the non-intrusive estimation of speech signal quality metrics. There are few demonstrations of various audio processing and models predictions.

## Audio Example 1: Combi-En model
Description: Detailed example of the audio processing and model predictions.

### 1. Clean Normalised Speech Signal
- **Audio File**: 8465-246943-0018.flac is a clean signal from Librespeech.
https://github.com/mothspaws/BP-2024/assets/72342131/d08f528b-5011-46f4-9d33-ba1a6425c6ef

- **Waveform Image**: 
![clean1](https://github.com/mothspaws/BP-2024/assets/72342131/ea27d411-cec3-4a76-a852-1ffe19cb2986)

### 2. Generate impulse response based on 30&deg; and wanted T60 level 160 ms
- The cleen normalised speech signal was filtered by generated impulse response.
https://github.com/mothspaws/BP-2024/assets/72342131/09b5133e-2963-4d96-afb3-8388c88680dc

### 3. Normalised Noise Component
- **Audio File**:
https://github.com/mothspaws/BP-2024/assets/72342131/77427293-28d6-47d8-a65c-8559c5074aec

- **Waveform Image**:
![noise1](https://github.com/mothspaws/BP-2024/assets/72342131/c52c6a59-3d33-466b-9e95-e6523beeab69)

### 4. Combination of Reverberated Speech and Noise
- **Audio File**: 10_angle-30_t160_8465-246943-0018.flac with noise level 10 dB.
https://github.com/mothspaws/BP-2024/assets/72342131/02eb3f81-729d-492d-b746-460a02d42d33

- **Waveform Image**:
![combined1](https://github.com/mothspaws/BP-2024/assets/72342131/9ec63cb9-c520-424a-aeb6-99a6d467d977)


### 5. Spectrogram
- **Image**:
![spect1](https://github.com/mothspaws/BP-2024/assets/72342131/98a71e16-a39a-45ad-b3db-fe252ccf26cd)

### 6. Prediction Graph
- **Description**: This graph shows the comparison of the expected metrics flow and the predicted metrics flow.
- **Image**:
![predictions1](https://github.com/mothspaws/BP-2024/assets/72342131/a89edbb7-354c-4af3-8b29-b81d348e857b)

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
