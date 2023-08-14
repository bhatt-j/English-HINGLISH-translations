# Language-translations

Built a basic Translation of English to hindi using MBart model. Model also helps to translate english to 49 different langauges.

## Future Enhancement
Code-Mixing can be done for English to Hinglish Translation.
* There is a proposed Two-phased pipe line
    * Basic monolingual conversion i.e English to Hindi except the nouns in the sentences
    * Training a Seq2Seq model, which takes English sentences as an input and generates a code-mixed sentences. In this cases the nouns remain in English as its an English to Hinglish Translation.
    
## Installations
* transformers
* sentencepiece
