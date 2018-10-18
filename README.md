# NLP with LSTM & TensorFlow

This notebooks uses word embedding and LSTM to generate new text based on Alice in Wonderland. 

Here's a sample of the original text:  
&nbsp;&nbsp;&nbsp;&nbsp;   _‘You are old, Father William,’ the young man said,  
&nbsp;&nbsp;&nbsp;&nbsp;   ‘And your hair has become very white;  
&nbsp;&nbsp;&nbsp;&nbsp;    And yet you incessantly stand on your head--  
&nbsp;&nbsp;&nbsp;&nbsp;    Do you think, at your age, it is right?’_  
   
The model generated prose that seems to have kept some of the original absurd style!  
&nbsp;&nbsp;&nbsp;&nbsp;    _alice felt dreadfully puzzled. the hatter’s remark seemed to have no
&nbsp;&nbsp;&nbsp;&nbsp;    sort of meaning in it, and yet it was certainly english. ‘i don’t quite
&nbsp;&nbsp;&nbsp;&nbsp;   understand you, and listen to me! i’ll soon make you
&nbsp;&nbsp;&nbsp;&nbsp;    dry enough! ’_
 
 Worth noting that the text generator picks the highest probability word each time, adding some randomness _(see the Generate Next Word cell)_ produces interesting results.
 
 
 
    
