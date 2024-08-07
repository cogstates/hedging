<h1>Training LLMs to Recognize Hedges in Spontaneous Narratives</h1>

This repo contains the data and code for the analyses presented in [Training LLMs to Recognize Hedges in Spontaneous Narratives](https://arxiv.org/abs/2408.03319), which was accepted to [SIGDIAL 2024](https://2024.sigdial.org/).

If you have any questions, you can direct them to the appropriate author using the information below. The first three authors have contributed equally to this study. 

<h2>Contributions by author:</h2>

- <b>Amie Paige -</b> Background/theory, pre-processing and coding the transcripts, inter-rater reliability, Gold Error analysis, and discussion.
<b>amie.paige@stonybrook.edu</b>

- <b>Adil Soubki -</b> GPT experiments, LLama 3 experiments.
<b>asoubki@cs.stonybrook.edu</b>

- <b>John Murzaku -</b> Background/theory, BERT experiments and fine-tuning.
<b>jmurzaku@cs.stonybrook.edu</b>

- <b>Suan Brennan -</b> Background/theory, discussion.


- <b>Owen Rambow -</b> Background/theory, discussion.


<h2>Note about the transcripts:</h2>
The transcripts used in our project were originally collected and analysed in Galati & Brennan (2010). The original transcripts contained markings for breath groups, non-verbal communication (e.g. laughter, coughing), and turns made by addressees. To prepare the transcripts for this project, we pre-processed the transcripts by removing non-verbal markers, and breath group notations. We also annotate for hedges.

**For more details about the original study, please see:**
Galati, A. & Brennan, S. (2010). Attenuating information in spoken communication: For the speaker, or for the addressee? *Journal of Memory and Language*, *62*(1), 35-51. https://doi.org/10.1016/j.jml.2009.09.002

<h2>Overview</h2>

The "transcript" folder contains:

- Original transcripts and annotations from Galati & Brennan (2010).
- Pre-processed transcripts with annotated hedges marked to the right of original utterances.
- The codebook used to train an additional RA to annotate the transcripts.
- A csv file with all 63 transcripts combined in one file.

The "code" folder contains:
- TBD

<h2>Acknowledgements</h2>
This material is based upon work supported in part by the National Science Foundation (NSF) under No. 2125295 (NRT-HDR: Detecting and Addressing Bias in Data, Humans, and Institutions) as well as by funding from the Defense Advanced Research Projects Agency (DARPA) under the CCU (No. HR001120C0037, PR No. HR0011154158, No. HR001122C0034) program. Any opinions, findings and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the NSF or DARPA.


We thank both the Institute for Advanced Computational Science and the Institute for AI-Driven Discovery and Innovation at Stony Brook for access to the computing resources needed for this work. These resources were made possible by NSF grant No. 1531492 (SeaWulf HPC cluster maintained by Research Computing and Cyberinfrastructure) and NSF grant No. 1919752 (Major Research Infrastructure program), respectively.





