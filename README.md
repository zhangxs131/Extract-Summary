# Extract-Summary
the normal way to realize summarizaition for extracting,lead3,textrank


### how to use

    
        tr = TextRankSum()

    score_ques = tr.summarize(doc, num=100, model_type="textrank_gensim") # "text_rank_sklearn")
    for sq in score_ques:
        print(sq)
