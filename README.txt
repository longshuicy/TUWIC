old representative node list

random sample 100 followers of the candidate (TWICE)

perform weighted/unweighted vector space model
perform Naive Bayes (with/without penalizing the absence of feature)

total people from Chicago is 907, sample size is 9771, so approximately 10% say they are from chicago

average precision sample 1 (test on location match)
weighted cosine similarity method:	 0.3059144596993453
unweighted cosine similarity method:	 0.30009042429464794
Naive Bayes method:			 0.3144313068005247
Naive Bayes with penalty method:	0.31427365532158713
-----------------------unsupervised method-------------------------------


-----------------------supervised method---------------------------------
mannualy classify some data, then apply NB, SVM, Decision tree
football related words:

ball carrier, blitz, completion, downfield, extra point, face mask, field goal, forward pass, fumble, goal line, goalpost, gridiron, half-time, handoff, huddle, interception, juke, kick off, kicker, lateral pass, line of scrimmage, linebacker, linemen, midfield, out-of-bounds, passing play, pigskin, placekicker, punt, quarterback, running back, running play, rush, safety, scrimmage, signal caller, split end, tackle, tackler, tight end, touch football, touchback, touchdown, yard line

hand labeling:
46148356,1283267196,30254145,733152516683247616,44423405,176232700,1241637750,621522914,43530424,752306004872851456,975450122,2924408380,770351285178695680,37336702,164062745,717508616379621377,1345613311,3734726776,789699096,849617023,701371958,293753781,2548145526,24795305,710161008623374336,257957627,2270087558,775889513545687040,37945675,3025453876,403494826,97968287,25233272,2941297534,2830084011,1684267350,126124444,615610761,36873535,431079779,763708110817157120,311828546,342126885,30322075,742489204811304961,4108695973,14626348,3572689408,718203801061191681,409459019,47487197,439410532,2788845642,30070994,4156754953,100859077,762437132,90691208,44395175,3127628843,29291060,1270251462,1499761044,22333466,266218183,218158603,26409269,250316672,190070843,242518175,1949440105,344756733,781246329125306369,27038618,185417089,215002856,786755345876213761,22925169,2922020171, 59367817,25031566,789270782711042048,2905598754,774009692439846912,18744284,58543233

save the tweets in .word

Naive Bayes Bernouli model:

id marked true
how many user provide location:  403
how many user are from target area:  145
accuracy =  0.3598014888337469

id marked false
how many user provide location:  3447
how many user are from target area:  582
accuracy =  0.16884247171453437



mannualy classify some data, then apply NB, SVM, Decision tree