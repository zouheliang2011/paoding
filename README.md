# paoding
Lucene 中文分词“庖丁解牛” Paoding Analysis
庖丁在不同场景下可能需要使用不同的字典库，目前开源代码中只有一个字典库，所有做了一点修改，增加了一个入参itemcat，这个入参用于控制读取不同的原字典，同时编译生成不同的字典编译文件。具体的文件读取规则可以参考paoding-analysis-withdic中的：FileWordsReader.java SortingDictionariesCompiler.java类
