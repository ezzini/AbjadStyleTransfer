<h1>Evaluation</h1>
<p>The ranking will be based on the following automatic metrics:</p>
<ul>
    <li><strong>Sentiment Style Accuracy</strong>: A baseline sentiment classifier will be used to measure the percentage of outputs with the correct target polarity.</li>
    <li><strong>Content Preservation</strong>: Semantic similarity will be measured using BERTScore (Zhang et al., 2019) between the input and output sentences.</li>
    <li><strong>Fluency</strong>: Perplexity score calculated using a large Arabic language model.</li>
</ul>