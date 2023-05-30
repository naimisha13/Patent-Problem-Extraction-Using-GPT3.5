# Patent-Problem-Extraction-Using-GPT3.5
Pre-processing and extracting relevant information form an 800mb consolidated XML file and prompting GPT's Davinci model to extract what problem the patent is Claiming to solve

## Abstract
The objective of this project is to identify the problem that a patent aims to solve by using text summarization techniques. To achieve this, I used an 800 MB XML file containing patent information as our input, from which the patent ID and description were extracted. After cleaning the data and extracting the description, used GPT-3's Davinci model to obtain embeddings and ask it to summarize the problem the patent claims to solve. Subsequently, I analyzed and cluster the embeddings obtained from the language model to gain insights into the data. This project can potentially improve patent analysis and enhance our understanding of the problems that patents aim to solve. <br>
Data can be obtained at the USPTO website.

<br>

## Conclusions and Open Problems

In this project, the objective was to utilize the power of the GPT-3.5 language model to determine the problem a patent is claiming to solve. However, I encountered several challenges throughout the process.<br>
The primary hurdle we faced was extracting the relevant information from the extensive 800 MB consolidated XML file, which encompassed details of approximately 6000 patents. The descriptions within the file, which contained the essential information for the language model to summarize, proved to be excessively lengthy in most cases. To overcome this, we had to condense the descriptions while still preserving the crucial details about the problem the patent aimed to address.<br>
One significant limitation we identified was the capacity constraint of the model itself. Given the extensive nature of the descriptions, it became evident that using a model with a higher capacity would be beneficial in effectively summarizing the patents and extracting the desired problem statements. The adoption of a more powerful model would alleviate the need for condensing the information, streamlining the process, and potentially improving the accuracy of the results.<br>
Although we made progress in extracting problem statements from a subset of patents, the project's scope could be expanded in several directions. Firstly, further exploration is needed to handle patents that did not meet the criteria for the GPT-3.5 model. Finding alternative methods or models to extract information from these patents would enhance the overall effectiveness of the approach.
Additionally, it would be valuable to investigate different techniques for data preprocessing and information extraction from the XML file. Exploring advanced natural language processing algorithms or utilizing domain-specific knowledge could potentially improve the quality and relevance of the extracted information.<br>
In conclusion, while this project has provided valuable insights into utilizing large language models for understanding the problem statements of patents, there are still areas for improvement and open problems to address. With advancements in model capacity and refined data processing techniques, we anticipate enhanced results and further advancements in automating the analysis of patent documents.

## Performance on random 100 patents
<img width="786" alt="image" src="https://github.com/naimisha13/Patent-Problem-Extraction-Using-GPT3.5/assets/36668575/e5632976-2188-4ebc-87e8-afba0bb7f908">

## Output of clustering
<img width="553" alt="image" src="https://github.com/naimisha13/Patent-Problem-Extraction-Using-GPT3.5/assets/36668575/bc021156-f0db-43dc-ab0e-b6d15f1c2142">

