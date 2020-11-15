Interactive Learning for Model-based Software Engineering
=====================
[PDF of the thesis can be found here](pdf/thesis.pdf).


Abstract:
Model-based technologies improve the efficiency of designing and developing IT systems by making it possible to automate verification, code generation and system analysis based on a formal model. A simple way of describing the behavior of systems is state-based modeling, which - due to the advancements of formal analysis techniques in recent years - can be widely and effectively utilized when analyzing systems. A possible way of synthesizing such models is to apply active automata learning algorithms.

Acquiring a correct formal model of a system can be challenging. On one hand, it is difficult for the designing engineer to keep every property of the envisioned system in mind at a given time, partly because of the complexity of the system, and because of possible hidden implications and contradictions. On the other hand, there are fully automated solutions, for instance, active automata learning, where the model construction is characterised by a teacher component - which is familiar with the extensive behavior of the system under learning - and a learner component - which synthesises the model via queries to the teacher component. However, such solutions have practical boundaries when validating the inferred behavior of the system. We propose a semi-automated solution, that applies automata learning to provide an interactive environment for model development.

The objective of this work is to support the design of systems and components from the ground up through InterActive automata learning. It utilizes the frequent input of designing engineers - who themselves are regarded as the teaching component of the algorithm - along with automated techniques, resolving the infeasibility of automated equivalence validation. The resulting semi-automated concept allows the engineer to focus on the expected behavior of the system, specifying its behavioral requirements in a declarative way and evaluating the model proposed by the algorithm.

This thesis presents an adaptive state-based modeling framework, into which we designed and integrated the interactive algorithm. The thus created framework combines the advantages of manual and automated solutions. Additionally, we extended the framework to handle and reconcile different formalisms, allowing the analysis and development of interactive automata learning algorithms to support model-driven development with an extended scope. 
