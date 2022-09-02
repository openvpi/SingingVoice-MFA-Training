# SingingVoice-MFA-Training

Hello, everyone! I'm a graduate student in Shanghai who major in phonetics. I'm highly grateful to my college and my institution (Institute of Linguistics, IOL) for providing me with interdisciplinary knowledge for language studies. My institution offers me a chance to learn about traditional linguistic knowledge and frontiers of speech science. Special thanks to my supervisor Mr. Zhu, who constantly encourages me to pursuit my dream.

2022.09.02

Task 1: Split TextGrid to Sentence level

In the Opencpop dataset, the textgirds is given in a level of the whole song. It also offers splited wav files in the sentence level, so we need to split the textgrids to the sentence level, which makes them suitable for aligning with splited wav files.

***split_textgrid_addictive_order.praat*** is based on praat scripting, where I combined the praat scripts offer by [Articulatum](https://www.zhihu.com/people/articulatum) and [ShaoPengfei](https://github.com/feelins/Praat_Scripts). The function of this file (ending with .praat) is to split original textgrids offered by Opencpop to sentence level, with the same name of their corresponding wav slices.

You need to download Praat to make ***split_textgrid_addictive_order.praat*** available to be opened. Double click ***split_textgrid_addictive_order.praat***  and Praat will automatically open itself. The only two things you need to do include: 1. Put all original textgrids into the folder ***original-textgrid*** (you can change the folder name as you wish) 2. Click the button ***"Run"*** in the pop-up window of Praat, and change the path of ***Directory_name*** (the folder contains original textgrids) and ***output_Directory_name*** (the folder you wish to store the split textgrid). 

