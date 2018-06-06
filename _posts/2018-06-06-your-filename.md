---
published: false
---
# Mapping Cicero's Letters

As I've mentioned before on Twitter, I'm interested in using the visualization tool Gephi to explore social relationships in Cicero's letters:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Gathering up metadata on Cicero&#39;s letters. Plan to import it into Gephi and analyze epistolary correspondence as a sort of &#39;social network&#39;. Github repo: <a href="https://t.co/LbfPcBX6Dl">https://t.co/LbfPcBX6Dl</a> <a href="https://twitter.com/hashtag/ancmakers?src=hash&amp;ref_src=twsrc%5Etfw">#ancmakers</a> <a href="https://t.co/LAD0gkWIMd">pic.twitter.com/LAD0gkWIMd</a></p>&mdash; Ryan Pasco (@rympasco) <a href="https://twitter.com/rympasco/status/952334222735429637?ref_src=twsrc%5Etfw">January 14, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

My goal is to make an interactive 'web' of individuals represented in Cicero's letters (adressers, addressees, and those named or alluded to within the bodies of the letters themsleves) and their relationships with each other as the letters describe them. Each relationship will be dated to allow the user to watch social relationships as they shift over time; further, the relationships will have a number of attributes assigned to them, such as letter number, letter type, topic of letter, social status/ethnic origins of addressee, etc., that will allow the user to filter through the data and ask particular questions in an intuitive way. For example: does the portrait of social life meaningfully differ in letters on philosophical vs. political topics? If so, how? 

I am not, of course, the first person to look into the idea of mapping social networks in ancient epistolography. [Benjamin Hicks](https://cdh.princeton.edu/people/benjamin-hicks/) at Princeton is working on mapping Pliny's letters. More relevant to the project at hand, Caitlin Marley recently defended her dissertation "Sentiments, Networks, Literary Biography: Towards a Mesoanalysis of Cicero's Corpus", in which she examines the emotional plot of Cicero's orations using sentiment analysis, a way of computationally determining the postive/negative emotion of a text or piece of text by tracking the use of positive and negative words throughout. In her project, she also uses Cicero's letters to create a social network and examines the positivity or negativity of correspondence between individuals:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">To everyone who expressed interest in the idea, look forward the work of Caitlin Marley <a href="https://twitter.com/CaitlinAMarley?ref_src=twsrc%5Etfw">@CaitlinAMarley</a> at U of Iowa, who is wrapping up a diss. on this very subject! <a href="https://twitter.com/hashtag/ancmakers?src=hash&amp;ref_src=twsrc%5Etfw">#ancmakers</a> <a href="https://t.co/mErXCDzszM">https://t.co/mErXCDzszM</a></p>&mdash; Ryan Pasco (@rympasco) <a href="https://twitter.com/rympasco/status/952650540315480064?ref_src=twsrc%5Etfw">January 14, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

1) What makes my work different? 
2) Why I am doing this in the open?  
Reducing something as complex as 'social relationships' into 

In the way of introduction, a little bit about how I came to the idea: 

In my first semester of graduate school, I took a seminar on Latin Epistolography. It was my first meaningful look at Cicero's letters; in the process, I became fascinated with one figure, the Etruscan Aulus Caecina, with whom Cicero corresponds (*Ad Fam.* 6.5-8). Over a decade after his own exile, Cicero exchanges letters in 46BCE with Caecina, himself exiled for writing a tract against Caesar 

>Adhuc stili poenas dem. Qua quidem in re singulari sum fato. Nam cum mendum scripturae litura tollatur, stultitia fama multetur, meus error exsilio corrigitur. Cuius summa criminis est, quod armatus adversario maledixi (6.7.1).
 I am still paying the penalty of my writings. And in that respect my fate has no parallel; for while a clerical error is removed by erasure, and fatuity is penalized by publicity, my mistake is corrected by banishment, though the charge against me amounts to no more than my having spoken ill of an adversary when I was actually in arms against him (trans. Williams).

Writing is pow

The letters capture the social positions of Aulus Caecina and Cicero in a brief span of time. Caecina the exile seeks Caesar's forgiveness through Cicero as intermediary, gets updates on his son at Rome, and writes a praise-work of Caesar (with Cicero as editor); Cicero gathers information on Caesar's disposition towards Caecina (through Largus, a friend of the Etruscan), communicates with the absent Caesar's associates Balbus and Oppius, and recommends Caecina to T. Furfanius Postumus and his legates. Without these few letters, we would know little about Caecina or about his relationship with elite Romans. As Seneca writes of Cicero's correspondence with Atticus:

>Nomen Attici perire Ciceronis epistulae non sinunt.
Cicero's letters do not let the name of Atticus perish.

My fascination with the letters of Cicero and Caecina, which comprise only a small portion of the *ad Familiares*, only a small part of the picture of social life captured in the letter collection, gave way to an interest in social relationships in the letters of Cicero more broadly. How do social relations change in conjunction with major political events? How might the web of relationships change based on the type or topic of letter or the addressee? How could I begin to collect and sort through so much data? I didn't know, however, the best way to approach this question, given that the intimidating size of Cicero's collected letters.

It wasn't until I attended [HILT](http://dhtraining.org/hilt/) in 2017 -- my first pivot towards digital scholarship --  that I learned of a possible approach. A fellow participant introduced me to a [mapping project](http://sites.fhi.duke.edu/ecologyofnetworks/letters-from-distant-lands-carolingian-intellectuals-and-their-networks/) of Carolingian intellectual networks by Clare Woods that uses the program [Gephi](https://gephi.org/). With the tool, a user can easily create and manipulate visualzations, which helps explore and discover patterns in the data. 

A graphing program like Gephi 'social network' captured in Cicero's letters
