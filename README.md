# Data for "Is Semi-Automatic Transcription Useful In Corpus Creation? - Preliminary considerations on the KIParla corpus"

Organization of the repo:

* `data/eaf`: cleaned transcriptions produced with ELAN software
* `data/csv`: conversion of eaf files into csv format, one transcription unit per line
* `data/whisper_output`: output of automatic transcription, one token per line
* `data/output`: for each extract, output provided by the `kiparla-tools` suite and derived formats
* `data/alignments`: alignment of each transcription with gold (03) transcription
* * `data/whisper_output_aligned`: alignment of whisper output with each orthographic transcription
* `data/data_description.csv`: additional information concerning transcription sessions
* `data/audio`: placeholder folder to place audio files for investigation
* `data/notes`: support information for the `kiparla-tools` suite

* `data_analysis/*.ipynb`: jupyter notebooks used for data exploration and analysis
* `data_analysis/statistics`: scripts and plots for statistical analysis
* `data_analysis/whisper_output_aligned_annotated`: manual annotation of errors produced by Whisper