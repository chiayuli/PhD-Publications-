The code was originally written by [@Espnet-group](https://github.com/espnet/espnet) and modified by [@Chia-Yu Li](https://github.com/chiayuli).

# Citations
```
@INPROCEEDINGS{9037688,
  author={Li, Chia-Yu and Vu, Ngoc Thang},
  booktitle={2019 International Conference on Asian Language Processing (IALP)}, 
  title={Integrating Knowledge in End-to-End Automatic Speech Recognition for Mandarin-English Code-Switching}, 
  year={2019},
  volume={},
  number={},
  pages={160-165},
  keywords={Hidden Markov models;Speech recognition;Switches;Dictionaries;Acoustics;Decoding;Computational modeling;end-to-end speech recognition;Mandarin-English Code-Switching speech;language model integration},
  doi={10.1109/IALP48816.2019.9037688}}
```
# Datasets
* SEAME: Mandarin-English Code-Switching in South-East Asia (LDC2015S04) for training baseline ASR and CycleGAN
* [@Aishell-1](https://www.openslr.org/33/), [@SMS](https://scholarbank.nus.edu.sg/handle/10635/137343) for training Sequence-to-sequence (S2S) model (baseline) and CycleGAN.
* [@THCHS-30](https://www.openslr.org/18/): A Free Chinese Speech Corpus Released by CSLT@Tsinghua University
* [@ST-CMDS](https://www.openslr.org/38/): A free Chinese Mandarin corpus
* [@Librispeech](https://www.openslr.org/12): Large-scale (1000 hours) corpus of read English speech
* [@Common Voice](https://commonvoice.mozilla.org/en/datasets) (old version, 425 hours)
* [@TedXSingapore](https://www.ted.com/tedx/events/56510)