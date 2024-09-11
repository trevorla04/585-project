**Contextual Real-time Intelligent Typo Identifier & Corrector (CRITIC)**

A context-aware spell-check ML System that provides appropriate feedback to the user in real-time after they make an error.

_Problem_

Typos are a common issue since we don't always type what we intend to. Both humans and LLMs are good at understanding context. We need a way to leverage LLMs to automate spell correcting with real-time feedback, low resource utilization, and offline inference.


_Solution_



_Evaluation_

We will evaluate performance measuring latency of time taken from input to result; optimal resource utilization by monitoring CPU usage; and correctness of the predicted vs. intended outcome.

_Feedback_

- Context rich spell checker on iPhone
- Running on CPU vs GPU

_References_

https://link.springer.com/article/10.1007/s10462-019-09787-4 - discusses how an LLM is used to spell check

_Risk_

A possible risk of using LLMs to spell check is overcorrection/context misinterpretation. If an LLM does not understand the context such as in a technical field of medicine or engineering, it can change what the user intended to spell. This can be mitigated by incorporating supervised learning where the LLM has oversight and its spell checks can be flagged for review.

CSCE 585 Project: Trevor La, Nicholas Miklaucic, and Kevin Francis
