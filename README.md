# multilingual-translation
This repository contains a source code (Jupyter notebook) used during experiments for the realization of my master2 thesis in the branch of computer science, option data science. The subject was __A multilingual machine translation approach sequence to sequence with deep neurals networks__ done at [_University of yaounde 1_](https://uy1.uninet.cm/) in french __Une approche de traduction automatique multilingue séquence à séquence à l'aide des réseaux de neurones profonds__.


# Data
The folder input contain datas use to feed learning algorithms. Datas used are part of [Europarl Dataset](https://www.statmt.org/europarl/) (_Khoen 2005_) in one case.
Ewondo dataset is taken at Martin Ongolo [repository](https://github.com/Martingeek4life/crossLingual-word-embedding-for-neural-machine-translation). The yemba datasets from Dr michel kana at tutotrial [about translation of under-ressourced languages](https://towardsdatascience.com/heres-how-to-build-a-language-translator-in-few-lines-of-code-using-keras-30f7e0b3aa1d)
To use datasets, enter in each input folder and unzip directly the zip inside. 

# Configuration
## multilingual-translation-experimentation.ipynb
That notebook contain a main code of our experimentation, run it will produce for differents language the encoder and the decoder of différents languages (french,english,ewondo,yemba) used in our experimentations. It is higher configurable with the __ACTION__ dictionary created inside. You can choose the components you want to train or not. You can choose what you want to evaluate. configs names are friendly used.

## french-ewondo-translation.ipynb

That notebook is like the first but it treat about only ewondo and french. it was created to make the second experimentation. That last one havent goal to compare bilingual translation of under-ressouced language and the method proposed in our work.