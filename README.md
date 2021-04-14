This repo contains scripts for an unpublished package created by and forked from Judith Mildner, a graduate student researcher in Dr. Diana Tamir's Princeton Social Neuroscience Laboratory at Princeton University's Department of Psychology.

This repo contains 4 measures of creativity from unusual uses/alternative uses tasks.

1. Fluency:
    number of responses given by a participant. Responses that are highly similar are collapsed into one before counting
2. Elaboration:
    number of words per response (after removing stopwords)
3. Flexibility:
    dissimilarity between response and target word, corrected for elaboration
4. Originality:
    distance from nearest response cluster
    
To get a single creativity score per participant, Z score each of these and average them.

The files `nathan_run_S1.py` and `nathan_run_S2.py` are the scripts which were compiled.