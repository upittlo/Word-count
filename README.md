# Word frequency sample code

Use Amazon product review for sample data

Convert date column into datetime data type

Seperated by positive and negative review according to rating

function can be used independently

Include Function:

1. reg_exp() >> regular expression data cleaning
   input:  string
   output: string

2. extract_unigram_noun(text) >> extract Noun set from string
   input:  string
   output: a set of words
   each word will be count only one time
   function includes lemmatize and POS tagging, only extract Noun
   customize remove list exclude useless words
   
3. extract_bigram(text)  >> extract bigram
   input:  string
   output: a set of bigrams
   function includes lemmatize and POS tagging, only extract Noun
   Remove stopwords version
   customize remove list exclude useless words
   
   
4. common_word_graph(df_wordset,remove_list,n) >> graph version of word count
   input:  a list of word sets
   output: word count graph
   customize remove list exclude useless words
   n = how many words to show
   
5. common_word(df_wordset,remove_list) >>  word count
   input:  a list of word sets
   output: word count graph
   customize remove list exclude useless words

   

