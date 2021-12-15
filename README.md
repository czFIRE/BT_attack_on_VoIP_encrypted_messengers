# Replication of attack on VoIP end-to-end encrypted messengers
Repository for bachelor thesis: Replication of attack on VoIP end-to-end encrypted messengers.

This thesis deals with the topic of inferring spoken phrases in end-to-end encrypted VoIP communications only by looking at the lengths of the packets corresponding to the transmission of the conversation.  
We perform an exploratory analysis of our dataset derived from voice corpus TIMIT using codecs with settings used in real conversations over Skype and WhatsApp. By combing the theoretical background presented in this thesis on VoIP and human voice with the results of the exploratory analysis, we choose suitable machine learning methods for this task (e.g., K-nearest-neighbors or neural networks). 
We train these models only on a series of packet lengths representing sequences of phonemes and words said in the conversation. We also derive additional features from this series to further help with the classification. We also choose a novel approach for our labels by examining word labels directly rather than only labels for phonemes.
We compare our results with the previous works that tried a variation of this attack and show that the attack is still indeed possible in modern VoIP conversations.
