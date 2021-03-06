---
layout: relation
title: 'advcl'
shortdef: 'adverbial clause modifier'
---

An adverbial clause modifier is a clause which modifies a verb or other predicate (adjective, etc.), as a modifier not as a core complement. This includes things such as a temporal clause, consequence, conditional clause, purpose clause, etc. The dependent must be clausal (or else it is an [advmod]()) and the dependent is the main predicate of the clause.


~~~ sdparse
Nuair a bhí siad ag teacht ar ais, chonaic siad é \n When they were coming back, they saw it
advcl(chonaic, bhí)
advcl(saw, when)
~~~


~~~ sdparse
Má imríonn siad mar faoi is féidir leo, is dóigh liom go bhfillfidh siad ar Staid Semple \n If they play as well as they can, I believe they will return to Semple Stadium
advcl(dóigh, imríonn)
advcl(believe, play)
~~~

~~~ sdparse
Ní thugtar íocaíochtaí mura n-iarrtar iad \n Payments are not given if they are not asked for
advcl(n-iarrtar, thugtar)
advcl(asked, given)
~~~



~~~ conllx
1	Ach	ach	SCONJ	SCONJ	_	4	mark	_	_
2	nuair	nuair	SCONJ	SCONJ	_	4	mark	_	_
3	a	a	PART	PART	_	4	mark:prt	_	_
4	bhíodar	bí	VERB	VERB	_	8	advcl	_	_
5	ag	ag	ADP	ADP	_	6	case	_	_
6	dul	dul	NOUN	NOUN	_	4	xcomp	_	_
7	aníos	aníos	ADV	ADV	_	6	advmod	_	_
8	casadh	cas	VERB	VERB	_	0	ROOT	_	_
9	mairnéalach	mairnéalach	NOUN	NOUN	_	8	nsubj	_	_
10	leo	le	ADP	ADP	_	8	nmod:prep	_	_
~~~
