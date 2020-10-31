# MVAEBasedBSE
## DEMO
This repository presents examples of extracted speech signals using the method proposed in paper 
*Target Speech Extraction Based on Blind Source Separation and X-vector-based Speaker Selection Trained with Data Augmentation*

#### Naming Rules
- Input: mixed-\<T<sub>60</sub>\>--\<*target speaker id*\>-\<*target utterance id*\>\_\<*interference speaker id*\>-\<*interference utterance id*\>\_\<*DOA interval*\>
- Ground Truth: target--\<*target speaker id*\>-\<*target utterance id*\>\_\<*interference speaker id*\>-\<*interference utterance id*\>
- Interference: interference--\<*target speaker id*\>-\<*target utterance id*\>\_\<*interference speaker id*\>-\<*interference utterance id*\>
- Output: extracted-\<*BSS algorithm*\>-\<T<sub>60</sub>\>--\<*target speaker id*\>-\<*target utterance id*\>\_\<*interference speaker id*\>-\<*interference utterance id*\>\_\<*DOA interval*\>
