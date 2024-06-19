# JapanLP

This project aims to generate informal Japanese to formal Japanese (Keigo). Although I am holding N1 Japanese-Language Proficiency Test, it is still difficult for me to write in formal Japanese (Keigo). This thought inspires me to start this project. When I was doing some research, I saw this [wordrabbit company](https://wordrabbit.jp/) that does exactly what this project is aiming to do and plus correcting grammars. The company name is provided as a reference. 

This is a Natural Language Processing (NLP) project which follows the Seq2Seq model. For Seq2Seq concept, here is some links that helped me understand the concept: 
* [Recurrent Neural Networks cheatsheet](https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-recurrent-neural-networks)
* [Standford online course](https://youtube.com/playlist?list=PLoROMvodv4rMFqRtEuo6SGjY4XbRIVRd4&si=SYTMKNq3x64AwVDN) 
* [Speech and Language Processing](https://web.stanford.edu/~jurafsky/slp3/ed3book.pdf) 

There are mutiple sites and code examples that support me to build this model: 
* [bentrevett/pytorch-seq2seq](https://github.com/bentrevett/pytorch-seq2seq/blob/main/1%20-%20Sequence%20to%20Sequence%20Learning%20with%20Neural%20Networks.ipynb) -> most of the reference is from here for seq2seq model
* [NLP From Scratch: Translation with a Sequence to Sequence Network and Attention](https://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html#loading-data-files)
* [日本語テキストの前処理：neologdn、大文字小文字、Unicode正規化](https://tuttieee.hatenablog.com/entry/ja-nlp-preprocess)
* [Hironsan/natural-language-preprocessings](https://github.com/Hironsan/natural-language-preprocessings/blob/master/preprocessings/ja/cleaning.py)
* [社会的関係を考慮した日本語敬語コーパスの構築への取り組み](https://www.jstage.jst.go.jp/article/pjsai/JSAI2022/0/JSAI2022_2C1GS601/_article/-char/ja/)
* [敬語変換タスクにおける評価用データセット](https://github.com/cl-tohoku/keigo_transfer_task?tab=readme-ov-file)

Please feel free to reference the code here if you want. HOWEVER, **rememeber to read the conclusion section before you refer to this project**.

*Disclaimer: this is for personal project (self-improvement) only, not for commercial use.*  