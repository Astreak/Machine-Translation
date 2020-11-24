# Machine-Translation
English to French translation over limited data
## Algorithm Used
![alt-text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS6QjXBU3yyDLw5rL4yFiFqLW65Vl81GtwGcA&usqp=CAU)
### Encode Decoder Architecture:-
Machine translation is a major problem domain for sequence transduction models, whose input and output are both variable-length sequences. To handle this type of inputs and outputs, we can design an architecture with two major components. The first component is an encoder: it takes a variable-length sequence as the input and transforms it into a state with a fixed shape. The second component is a decoder: it maps the encoded state of a fixed shape to a variable-length sequence. This is called an encoder-decoder architecture, which is depicted.

The Encoder-Decoder architecture with recurrent neural networks has become an effective and standard approach for both neural machine translation (NMT) and sequence-to-sequence (seq2seq) prediction in general.

The key benefits of the approach are the ability to train a single end-to-end model directly on source and target sentences and the ability to handle variable length input and output sequences of text.

##### Bleu Score
![alt-text](https://3qeqpr26caki16dnhd19sv6by6v-wpengine.netdna-ssl.com/wp-content/uploads/2017/10/Loss-in-model-skill-with-increased-sentence-length.png)



![alt-text](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTJXTsjPrewtoTGevCbXXyEcJMXblPqHvBCAg&usqp=CAU)

# Technology and Frameworks used 
- Tensorflow
- keras
#### Sources:- Google , (https://machinelearningmastery.com/encoder-decoder-recurrent-neural-network-models-neural-machine-translation/)
