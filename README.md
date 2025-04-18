# Content-Moderation-Classifier-for-LLMs
DATASCI 207 - Applied Machine Learning


Humanity is swiftly and comprehensively stepping into the age of generative AI. Navigating this new frontier demands that we confront the vital task of deploying it responsibly. LLMs can inadvertently generate or be prompted with undesirable content, including hate speech, sexually explicit material, violence, and harassment. This poses significant risks to both model providers and users, necessitating robust content moderation systems.

Reliable LLM content moderation is complex. Current detection often lacks the holistic view needed for real-world use and struggles with dynamic content and adversarial prompts. As OpenAI notes, effective moderation requires nuanced categories, quality data, active learning for rare but critical events, and robustness against attacks and shifts. This project builds on some of the work done by OpenAI by attempting to build a holistic prompt classifier for safer LLMs. Our research question is the following:

*How effectively can multi-label classifiers, trained on a dataset of prompts sent to LLM, accurately identify and categorize multiple unsafe content labels?*

The classifiers developed in this project do not currently meet industry standards for practical deployment. This work highlights the significant challenge of prompt classification, suggesting that more sophisticated machine learning models are required beyond conventional techniques. We propose that future investigations should prioritize neural network architectures, particularly those employing transformers, and will necessitate a considerably expanded dataset.
