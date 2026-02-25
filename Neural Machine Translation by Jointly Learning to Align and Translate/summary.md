This paper introduces **RNNsearch**, a novel neural machine translation architecture designed to overcome the limitations of traditional encoder-decoder models.

While older systems struggle with long sentences because they compress all information into a fixed-length vector, the authors propose an attention mechanism that allows the model to "soft-search" for relevant parts of a source sentence during translation.

This approach utilizes a bidirectional RNN to create a sequence of annotations, enabling the decoder to focus on specific input words as it generates each target word.

Experimental results on English-to-French translation demonstrate that this method significantly improves performance, particularly for long sentences, reaching a level comparable to state-of-the-art phrase-based systems.

Visualizations of the model’s alignment weights further confirm that it accurately identifies linguistic correspondences between languages, even when word orders differ.

Overall, the research represents a major advancement in building end-to-end neural networks capable of understanding and translating complex natural language.
