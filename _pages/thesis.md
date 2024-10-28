---
layout: page
permalink: /Dissertation/
title: Dissertation
description: Introduction of my Ph.D. Dissertation.
nav: true
nav_order: 5
---

<h3> Author Verification Model for Cross-texting Detection in Korean Messenger Chat </h3>
<p><b>URL</b>: <a href="https://dcollection.pusan.ac.kr/common/orgView/000000165787">https://dcollection.pusan.ac.kr/common/orgView/000000165787</a></p>
<p><b>Keywords</b>: author verification, online text analysis, cross-texting, graph-based text analysis </p>

<p><b>Abstract:</b></p>
   As the Internet and IT technology continue to develop, short text-based communication has become more popular compared to voice-based communication. 
   Chat-based communication enables rapid, short, and extensive exchange of messages with many people, but it also creates new social problems. 
   **`Cross-texting'** is one such problem. 
   It refers to accidentally sending a text to an unintended person during concurrent conversations with multiple people. 
   Cross-texting can be a serious issue in languages that require respectful expressions, such as Korean.
   As text-based communication grows in popularity, it is crucial to prevent cross-texting by detecting it in advance, especially in languages with honorific expressions.

   This dissertation introduces a model designed to detect cross-texting in messenger platforms by adapting the conventional authorship verification approach, which relies on stylistic attributes, to ascertain whether the authors of two documents are identical.
   Leveraging the insight that individuals may adopt varying tones depending on their conversation partner, the continuity of the dialogue is modeled through the analysis of the user's prior chat interactions. 
   Subsequently, the extent to which this coherence persists in newly introduced messages is assessed.
   To accomplish this, it is imperative to define features capable of capturing consistency while considering the characteristics of Korean chat messages.

   This dissertation proposes two approaches.
   First, it establishes criteria for evaluating the degree of formality and completeness in expressions used in chat messages, aiming to model the consistency of attitudes observed in conversations.
   This approach comprises explicitly defined evaluation criteria and a combination of internally pre-trained models.
   Second, it constructs a graph based on the co-occurrence relationships of syllables used in chat messages to model the consistency of frequently used patterns in conversations. 
   This approach is constituted by a model that captures patterns inherent in given chat messages without pre-training.
    
   To evaluate the detection performance of the model, cross-texting datasets with varying levels of difficulty were constructed by adjusting the types and lengths of cross-texting messages using real messenger corpora.
   Experimental results revealed that the first approach achieved up to 95% accuracy in detecting cross-texting with relatively small-dimensional feature values. 
   Furthermore, through the distribution of these feature values, it was confirmed that the proposed model effectively modeled the consistency of actual chat messages.
   The second approach demonstrated stable performance compared to other models when the change in attitudes expressed in chat messages was minimal, achieving a maximum accuracy of 82% in cross-texting detection.
