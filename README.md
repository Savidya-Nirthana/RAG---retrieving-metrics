<h1>Retrieval Metrics in RAG Systems</h1>

<p>Retrieval metrics are essential in Retrieval-Augmented Generation (RAG) systems because they help measure how well the retrieval component is performing. The retrieval step’s job is to find the most relevant documents or chunks from a knowledge base that can help answer a user’s query.</p>

To evaluate this effectively, we use a labeled dataset—a dataset where:

<ul>
  <li>Each query is already paired with its correct, relevant answers or documents.</li>
  <li>These “ground truth” answers serve as a benchmark to check how accurate the RAG system’s retrieved results are.</li>
</ul>

By comparing what the system retrieves against the known correct answers, we can calculate retrieval performance metrics. In this lab, the focus will be on two widely used metrics:

<ul>
  <li>Precision – Of all the documents the system retrieved, what fraction were actually relevant? (Measures correctness of retrieved results.)</li>
  <li>Recall – Of all the relevant documents in the dataset, what fraction did the system successfully retrieve? (Measures completeness of retrieval.)</li>
</ul>


#### Precision
Measures **how many of the retrieved documents are actually relevant**.  
<b>Precision</b> = (Relevant Retrieved) ÷ (Total Retrieved)

#### Recall
Measures **how many of the relevant documents were successfully retrieved**.  
<b>Recall</b> = (Relevant Retrieved) ÷ (Total Relevant)





