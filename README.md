# NLP with LSTM & TensorFlow

This notebooks uses word embedding and LSTM to generate new text based on Alice in Wonderland. Here's a sample of the original text:<span style="color:blue">
   _‘You are old, Father William,’ the young man said,
    ‘And your hair has become very white;
   And yet you incessantly stand on your head--
    Do you think, at your age, it is right?’_
    </span>.
The model generated prose that seems to have kept some of the original absurd style!
    _alice felt dreadfully puzzled. the hatter’s remark seemed to have no
    sort of meaning in it, and yet it was certainly english. ‘i don’t quite
    understand you, and listen to me! i’ll soon make you
    dry enough! ’_
 
 Worth noting that the text generator picks the highest probability word each time, adding some randomness _(see the Generate Next Word cell)_ produces interesting results.
 
 
 
    
