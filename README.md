# Project--ChatBot-NLP-

<table>
  
**In this project we have made Q/A ChatBot using RNN(Recurrent Neural Network) with LSTM(Long Short Term Memory) in Natural Language Processing.** <br></br>




Here we will using End to End Memory Networks. The inputs will consist of:<br></br>
1: Story(It will be just the sequences of sentences which will be feeded into the embedding layer 'A' to form memrory vector(m)<br>
2: Questions(It will be questions asked w.r.t sentences which will be feeded into the embedding layer 'B' to form input vector(u)<br>

Then we will perform inner product of m and u. Then we will apply softmax function on that.<br>
Soon After we will put our Story into another embedding layer C and then we will calculate its weighted sum and assigned it as output(o).<br>

After this we will perform o(summation with u) which will give us weight. After which we will apply softmax on this to get the predicted answer.<br></br>



**Before jumping to the code lets understand LSTM(Long Short Term Memory), RNN(Recurrent Neural Network), and NLP(Natural Language Processing) First**...<br></br>


**What is NMF?** <br></br>

Non-negative Matrix Factorization (NMF) is a dimensionality reduction technique commonly used in Natural Language Processing (NLP) for topics extraction and document clustering. In NMF, a matrix representing the relationships between terms (words) and documents is factorized into two lower-dimensional matrices, typically referred to as the term-topic matrix and the topic-document matrix. <br></br>

**What is (NLP)Natural Language Processing**?<br></br>

NLP or Natural language processing is an interdisciplinary subfield of computer science and linguistics. It is primarily concerned with giving computers the ability to support and manipulate human language.<br></br>

NLP combines computational linguistics—rule-based modeling of human language—with statistical, machine learning, and deep learning models. Together, these technologies enable computers to process human language in the form of text or voice data and to ‘understand’ its full meaning, complete with the speaker or writer’s intent and sentiment.<br></br>

NLP drives computer programs that translate text from one language to another, respond to spoken commands, and summarize large volumes of text rapidly—even in real time. There’s a good chance you’ve interacted with NLP in the form of voice-operated GPS systems, digital assistants, speech-to-text dictation software, customer service chatbots, and other consumer conveniences. But NLP also plays a growing role in enterprise solutions that help streamline business operations, increase employee productivity, and simplify mission-critical business processes.<br></br>


**Important Note: Go through the quora_questions.csv file and get a proper understanding of it before jumping to the code.**


</table>

**So what are you waiting for...? Jump to the code to get started. As usual for any doubt or query see you in pull request section 😁😂. Thanks!**


