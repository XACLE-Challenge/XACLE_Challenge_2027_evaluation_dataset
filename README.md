# XACLE Challenge 2027 evaluation dataset

## Contents

This dataset consists of the following componets:

- Audio–text pairs

	This dataset includes 4,000 audio–text pairs. Each text is written in English.
	All audio samples was converted to mono 16-bit 16 kHz format.

## Download

To download the evaluation dataset, please send an email to dataset@xacle.org with “Download evaluation dataset” in the subject line. 
You will receive an automated reply with the download link.
<b>If you don't receive a reply after a while, please check your spam folder. If the email fails to send or you still don't receive a reply, please contact the organizer at y-oka@g.ecc.u-tokyo.ac.jp.<b>



## Statistics

|  | Test |
| :--- | ---: |
| Audio–text pairs | 4,000 |
| Audio duration [s] | 38,744.6 |

## File format

- evaluation.csv: There are 2 columns in the each csv file.
	- wave_file_name: The file name of audio.
	- text: The text's corresponding audio.

## Directory structure

The directory structure of this dataset is as follows:

```
XACLE2027_evaluation_dataset
├── meta_data
│   ├── evaluation.csv
│   
└── wav
    └── evaluation
        ├── 13500.wav
        ├── 13501.wav
        ├── 13502.wav
        ├──   .
        ├──   .
        └──   .
    
```

<!--
## Citation

```
@INPROCEEDINGS{XACLE2026,
  author={Okamoto, Yuki and Takizawa, Riki and Kishi, Minoru and Kanamori, Yusuke and Tonami, Noriyuki and Nagase, Ryotaro and Takamichi, Shinnosuke and Imoto, Keisuke},
  booktitle={Proc. IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)}, 
  title={XACLE Challenge 2026: The First X-to-Audio Alignment Challenge}, 
  year={2026},
  pages={21877-21879},
}
```
-->

## Acknowledgment

The work was supported by JSPS KAKENHI Grant Number 24K23880, 25K21221, JST Moonshot Grant Number JPMJMS2237.

