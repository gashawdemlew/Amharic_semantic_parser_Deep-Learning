# Amharic semantic parser using Deep Learning

# Semantic Parser:
To process and understand natural languages, it is necessary to organize the linguistic structure of the texts at different levels. The semantic level of linguistic analysis is concerned with producing accurate representations of the meaning of utterances that may contain significant conventions. The semantic parsing aims to map natural language discourses to machine-comprehensible meanings. Traditional methods of creating semantic analyzers depend on high-quality lexicons, hand-made grammars, and language features that are limited by the domain or expression applied. This repository presents an Amharic semantic parser developed using an attention-enhanced sequence-to-sequence neural model that encodes sentences and generates their logical forms. The model is constructed to handle different types of sentences from simple to complex, and to accept additional difficulties for the Amharic language such as rich morphology and greater freedom in the composition of sentences. We trained the model with a fully supervised training setting where utterances-logic forms are given and tested in Amharic sentences collected in three different domains. **<em>It scored 0.95 for BLEU-4 and 0.97 for LEPOR</em>**.

# The repository consists of: 
   <ul>
     <li>A deep learning algorithm written by python language (jupyter notebook) to develop semantic parser model</li>
     <li>sample training, validation, and testing dataset</li>
     <li>Image of developed model</li>
     <li>Train vs Test loss graph</li>
   </ul>

# The code consists the following activities:
  1) Reading tab-separated paired file (Amharic sentence vs Logic form)
  2) Pre-processing Amharic sentences and Data preparation
  3) Model building (**3-Layer, Bi-derectional, Lstm, encoder-decoder, with attention (i.e. Bahdanau Attention)**)
  4) Model training
  5) Model validation using Bleu and LEPOR scores
  6) Model testing

# Note: 
   <em>The code can be used to develop semantic parser (and machine translation) for different languages except pre-processing component</em>
