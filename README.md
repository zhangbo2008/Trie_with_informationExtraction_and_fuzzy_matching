#main3.py是最新代码: 具有模糊匹配, 带?表示任意一个非空字符, 具有信息抽取标注能力.









2023-02-23,21点48
我想搞一下并行加速.
让查询速度更快.
test2.py









"# searching_in_trie_in_microseconds_1000wdata_python" 


just a  very simple using of trie Tree. very useful in big data of matching substring with the words in dict. you can assume the solving is a powerful version of kmp in big data.


# if your keywords have overlap you can select there method below as your situation. you can check them in 1.py with example . you can test them. the test defualt not activate you can change them in 1.py:309
# pipei have 3 method   pipei means find_substring    
pipei_shortest : if you match the shortest word in dict, after that and you just skip this word and match the else string with the word in dict.


pipei_all: you find all the matching with the word in dict. 
 
pipei_longest:you can find the lognest word in dict , after that  and you just skip this word and match the else string with the word in dict.


i hope you can find the explaning code in the 1.py
# trie_multiprocess
# trie_multiprocess
# Trie_with_informationExtraction_and_fuzzy_matching
