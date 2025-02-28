# XML-Mini
XML 1 Mini is a lightweight, GPT-based text generation model designed to predict the next character in a given input sequence. It operates on text-based datasets and can generate contextually relevant text based on its training data. For example, when trained on a Shakespearean dataset, it can produce text in a Shakespearean style.

However, XML 1 Mini is not optimized for answering questions or providing structured responses. Instead, it focuses on character-level text prediction, continuing the sequence until the specified output length is reached.

# Important Considerations
	•	The model may generate incoherent or directionless text.
	•	Best results are achieved with large text datasets, balancing training time and data quality.
	•	XML 1 Mini does not currently benefit from GPU acceleration framewroks such as Nvidia's Cuda, AMD's ROCm, or Apple's Metal 3 Framework.
	•	XML 1 Mini has currently been only tested on M-Series chips. 
	•	It takes _:__ mins to train XML 1 Mini on a ~2 million letter or ~400,000 word dataset on a M1 chip.

Developer: David Akhmedbayev
