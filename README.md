# Bachelor Thesis Repository: Non-Intrusive Speech Quality Assessment

This repository contains source code and example dataset, which were created while writing of my bachelor thesis, which focuses on the non-intrusive estimation of speech signal quality metrics. There are few demonstrations of various audio processing and models predictions.

## Audio Example 1: Combi-En model
Description: Detailed example of the audio processing and Combi-En model model predictions.

### 1. Clean Normalised Speech Signal
- **Audio File**: 8465-246943-0018.flac is a clean signal from Librespeech.
<audio controls="1" controlslist="nodownload nofullscreen noremoteplayback" src="[https://github.com/mothspaws/BP-2024/assets/72342131/d08f528b-5011-46f4-9d33-ba1a6425c6ef](https://github.com/mothspaws/BP-2024/assets/72342131/d08f528b-5011-46f4-9d33-ba1a6425c6ef)">https://github.com/mothspaws/BP-2024/assets/72342131/d08f528b-5011-46f4-9d33-ba1a6425c6ef</audio>

- **Waveform Image**: 
![clean1](https://github.com/mothspaws/BP-2024/assets/72342131/ea27d411-cec3-4a76-a852-1ffe19cb2986)

### 2. Generate impulse response based on 30&deg; and wanted T60 level 160 ms
- The cleen normalised speech signal was filtered by generated impulse response.
<audio controls="1" controlslist="nodownload nofullscreen noremoteplayback" src="[https://github.com/mothspaws/BP-2024/assets/72342131/09b5133e-2963-4d96-afb3-8388c88680dc](https://github.com/mothspaws/BP-2024/assets/72342131/09b5133e-2963-4d96-afb3-8388c88680dc)">https://github.com/mothspaws/BP-2024/assets/72342131/09b5133e-2963-4d96-afb3-8388c88680dc</audio>

### 3. Normalised Noise Component
- **Audio File**:
<audio controls="1" controlslist="nodownload nofullscreen noremoteplayback" src="[https://github.com/mothspaws/BP-2024/assets/72342131/77427293-28d6-47d8-a65c-8559c5074aec](https://github.com/mothspaws/BP-2024/assets/72342131/77427293-28d6-47d8-a65c-8559c5074aec)">https://github.com/mothspaws/BP-2024/assets/72342131/77427293-28d6-47d8-a65c-8559c5074aec</audio>

- **Waveform Image**:
![noise1](https://github.com/mothspaws/BP-2024/assets/72342131/c52c6a59-3d33-466b-9e95-e6523beeab69)

### 4. Combination of Reverberated Speech and Noise
- **Audio File**: 10_angle-30_t160_8465-246943-0018.flac with noise level 10 dB.
<audio controls="1" controlslist="nodownload nofullscreen noremoteplayback" src="[https://github.com/mothspaws/BP-2024/assets/72342131/02eb3f81-729d-492d-b746-460a02d42d33](https://github.com/mothspaws/BP-2024/assets/72342131/02eb3f81-729d-492d-b746-460a02d42d33)">https://github.com/mothspaws/BP-2024/assets/72342131/02eb3f81-729d-492d-b746-460a02d42d33</audio>

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

## Audio Example 2: Reverb-En model
Description: Detailed example of the audio processing and Reverb-En model model predictions.

### 1. Clean Speech Signal
- **Audio File**: 89-219-0042.flac is a clean signal from Librespeech.
<audio controls="1" controlslist="nodownload nofullscreen noremoteplayback" src="[https://github.com/mothspaws/BP-2024/assets/72342131/f2036dbf-0397-4e7b-8231-dacf1d84c9e0](https://github.com/mothspaws/BP-2024/assets/72342131/f2036dbf-0397-4e7b-8231-dacf1d84c9e0)">https://github.com/mothspaws/BP-2024/assets/72342131/f2036dbf-0397-4e7b-8231-dacf1d84c9e0</audio>

- **Waveform Image**: 
![clean2](https://github.com/mothspaws/BP-2024/assets/72342131/c9d5ee31-3e7c-4bf2-84e0-911e7d734501)

### 2. Generate impulse response based on 0&deg; and wanted T60 level 240 ms
- The cleen speech signal was normalised and filtered by generated impulse response.
<audio controls="1" controlslist="nodownload nofullscreen noremoteplayback" src="[https://github.com/mothspaws/BP-2024/assets/72342131/fb6ea60a-7f8c-440c-9531-02829ba23f9b](https://github.com/mothspaws/BP-2024/assets/72342131/fb6ea60a-7f8c-440c-9531-02829ba23f9b)">https://github.com/mothspaws/BP-2024/assets/72342131/fb6ea60a-7f8c-440c-9531-02829ba23f9b</audio>

![filtered2](https://github.com/mothspaws/BP-2024/assets/72342131/0cdb13ee-ba64-4485-b573-689489430772)

### 3. Spectrogram
- **Image**:
![spect2](https://github.com/mothspaws/BP-2024/assets/72342131/5e6b0f96-9d58-4399-9d5d-5da909c857ce)

### 4. Prediction Graph
- **Description**: This graph shows the comparison of the expected metrics flow and the predicted metrics flow.
- **Image**:
![predictions2](https://github.com/mothspaws/BP-2024/assets/72342131/64df1e86-e1c0-4f5a-834d-e9bf15e42228)

### 5. Table: Comparison of Expected and Predicted Metrics
- **Description**: This tables show more detailed comparison of the expected metrics and the predicted metrics.

| Metric         | 1      | 2      | 3      | 4      | 5      | 6      | 7      | 8      | 9      | 10     | 11     | 12     | 13     | 14     | 15     | 16     |
|----------------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|
| Expected STOI  | 0.8    | 0.7    | 0.4    | 0.7    | 0.7    | 0.7    | 0.7    | 0.6    | 0.4    | 0.6    | 0.7    | 0.6    | 0.6    | 0.7    | 0.6    | 0.5    |
| Predicted STOI | 0.7    | 0.7    | 0.2    | 0.7    | 0.6    | 0.7    | 0.6    | 0.6    | 0.3    | 0.5    | 0.7    | 0.6    | 0.6    | 0.7    | 0.6    | 0.6    |


| Metric     | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 10  | 11  | 12  | 13  | 14  | 15  | 16  |
|------------|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Expected T60 | 240 | 240 | 240 | 240 | 240 | 240 | 240 | 240 | 240 | 240 | 240 | 240 | 240 | 240 | 240 | 240 |
| Predicted T60| 255 | 267 | 281 | 270 | 289 | 302 | 286 | 244 | 242 | 262 | 276 | 268 | 281 | 301 | 317 | 275 |

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
