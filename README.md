# nepali-asr
Work on under-resourced languages in Nepal

Paper: Meelen, Marieke; O'Neill, Alexander; Coto-Solano, Rolando. End-to-End Speech Recognition for Endangered Languages of Nepal.

Best performing models:

[Dzardzongke: XLSR-Wav2Vec2](https://rcweb.dartmouth.edu/RCoto/nepali-asr-202312/dz-fromScratch-251mins.tar.gz)<br>
From 254 minutes of data: CER=0.071, WER=0.33

[Dzardzongke: XLSR-Wav2Vec2, with transfer learning from a Tibetan language model](https://rcweb.dartmouth.edu/RCoto/nepali-asr-202312/dz-transfer-251mins.tar.gz)<br>
From 254 minutes of data: CER=0.059, WER=0.30

[Newar: XLSR-Wav2Vec2](https://rcweb.dartmouth.edu/RCoto/nepali-asr-202312/nw-fromScratch-294mins.tar.gz)<br>
From 294 minutes of data: CER=0.115, WER=0.50

Post-processing modifications:<br>
Word correction for Dzardzongke (Python file)<br>
Word correction for Newar (Python file)
