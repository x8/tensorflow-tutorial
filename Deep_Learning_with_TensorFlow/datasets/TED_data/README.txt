原始文件(train.raw.en, train.raw.zh)是由https://wit3.fbk.eu/mt.php?release=2015-01下载的XML文件中提取的文本。
英语训练文件(train.txt.en)使用Moses tokenizer进行切词: https://github.com/moses-smt/mosesdecoder/blob/master/scripts/tokenizer/tokenizer.perl
中文训练文件(train.txt.zh)按字符切词。
示例程序中只需要用到train.txt.en和train.txt.zh，原始文件仅供参考之用。