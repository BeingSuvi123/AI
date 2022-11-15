# AI
Assignment 1</br></br>
<b> Intelligence</b></br>
Intelligence has been defined in many ways: the capacity for abstraction, logic, understanding, self-awareness, learning, emotional knowledge, reasoning, planning, creativity, critical thinking, and problem-solving. </br></br>
<b>Artificial Intelligence (AI)</b>
Artificial intelligence(AI) is intelligence - perceiving, synthesizing, and infering information - demonstrated by machines, as opposed to intelligence displayed by animals and humans. Artificial intelligence is the simulation of human intelligence processes by machines, especially computer systems. Specific applications of AI include expert systems, natural language processing, speech recognition and machine vision.</br></br>
<b>AI Perspectives: </br></br>
Acting Humanly</b></br>
The first proposal for success in building a program and acts humanly was the Turing Test. To be considered intelligent a program must be able to act sufficiently like a human to fool an interrogator. A human interrogates the program and another human via a terminal simultaneously. If after a reasonable period, the interrogator cannot tell which is which, the program passes.

To pass this test requires:

    natural language processing
    knowledge representation
    automated reasoning
    machine learning

This test avoids physical contact and concentrates on "higher level" mental faculties. A total Turing test would require the program to also do:

    computer vision
    robotics

<b>Thinking Humanly</b> </br>
This requires "getting inside" of the human mind to see how it works and then comparing our computer programs to this. This is what cognitive science attempts to do. Another way to do this is to observe a human problem solving and argue that one's programs go about problem solving in a similar way.

Example: GPS (General Problem Solver) was an early computer program that attempted to model human thinking. The developers were not so much interested in whether or not GPS solved problems correctly. They were more interested in showing that it solved problems like people, going through the same steps and taking around the same amount of time to perform those steps. 

<b>Acting Rationally</b></br>
Acting rationally means acting so as to achieve one's goals, given one's beliefs. An agent is just something that perceives and acts.

In the logical approach to AI, the emphasis is on correct inferences. This is often part of being a rational agent because one way to act rationally is to reason logically and then act on ones conclusions. But this is not all of rationality because agents often find themselves in situations where there is no provably correct thing to do, yet they must do something.

There are also ways to act rationally that do not seem to involve inference, e.g., reflex actions.

The study of AI as rational agent design has two advantages:

    It is more general than the logical approach because correct inference is only a useful mechanism for achieving rationality, not a necessary one.
    It is more amenable to scientific development than approaches based on human behaviour or human thought because a standard of rationality can be defined independent of humans.

Achieving perfect rationality in complex environments is not possible because the computational demands are too high. However, we will study perfect rationality as a starting place. 

<b>Thinking rationally</b> </br>
Aristotle was one of the first to attempt to codify "thinking". His syllogisms provided patterns of argument structure that always gave correct conclusions, giving correct premises.

Example: All computers use energy. Using energy always generates heat. Therefore, all computers generate heat.

This initiate the field of logic. Formal logic was developed in the late nineteenth century. This was the first step toward enabling computer programs to reason logically.

By 1965, programs existed that could, given enough time and memory, take a description of the problem in logical notation and find the solution, if one existed. The logicist tradition in AI hopes to build on such programs to create intelligence.

There are two main obstacles to this approach: First, it is difficult to make informal knowledge precise enough to use the logicist approach particularly when there is uncertainty in the knowledge. Second, there is a big difference between being able to solve a problem in principle and doing so in practice. </br></br>
    
<b>History of AI</b> <br/>
In the early days of AI there was great optimism that the intelligent computer were just a few decades off. However, the problem proved to be far more difficult than anticipated. Today most researchers in AI a smart enough not to make predictions. Also many are not really concerned with creating intelligence, rather they are concerned with creating more intelligent computer programs than currently exist.

The microworlds approach to AI was pioneered in the 1960's and tried to solve problems in limited domains.

The ANALOGY program could solve geometric analogy problems.

The most famous microworld is the Blocks World (1970's). A command such as "Pick up the red block" could be used to manipulate the world.

The microworld approach turned out to have problems because the advances made in writing programs for microworlds turned out not to be generalisable.

Early work in the Logicist camp also had problems because of the use of weak methods (these use weak information about a domain). However, knowledge intensive approaches have been more successful. A key development from the Logicist tradition was knowledge-based systems in the 1980's.

In the late 1980's Neural Networks became fashionable again (they had been popular in the 60's) due to improved learning algorithms and faster processors.

AI Time Line

1943 - McCulloch and Pits propose modelling neurons using on/off devices.
1950's - Claude Shannon and Alan Turing try to write chess playing programs.
1957 - John McCarthy thinks of the name "Artificial Intelligence".
1960's - Logic Theorist, GPS, microworlds, neural networks.
1971 - NP-Comlpeteness theory (Cook and Karp) casts doubt on general applicability of AI methods.
1970's - Knowledge based systems and expert systems.
1980's - AI techniques in widespread use, neural networks rediscovered.
1990's - Deep Blue wins against world chess champion. Image and Speech recognition become practical.</br></br>
  
     
<b>Foundations of AI: </b></br></br>
<b>Philosophy</b> </br>
Philosophers staked out most of the important ideas of AI, but to move to a formal science requires a level of mathematical formalism in three main areas: computation, logic and probability.

Mathematicians have proved that there exists an algorithm to prove any true statement in first-order logic. However, if one adds the principle of induction required to capture the semantics of the natural numbers, then this is no longer the case. Specifically, the incompleteness theorem showed that in any language expressive enough to describe the properties of the natural numbers, there are true statements that are undecidable: their truth cannot be established by any algorithm.

Analogously, Turing showed that there are some functions that no Turing machine can compute.

Although undecidability and noncomputability are important in the understanding of computation, the notion of intractability has had much greater impact on computer science and AI. A class of problems in called intractable if the time required to solve instances of the class grows at least exponentially with the size of the instances.

Exponential vs. polynomial. In between is nondeterministic polynomial.

Even moderately sized instances of intractable problems classes cannot be solved in reasonable amounts of time. Therefore, one should strive to divide the overall problem of generating intelligent behaviour into tractable subproblems rather than intractable ones.

Another important concept from mathematics is problem reduction. A reduction is a general transformation from one class of problems to another such that the solutions to the first class can be found by reducing them to problems in the second class and then solving those.

One notion for recognizing intractable problems in that of NP-Completeness. Problems that can be solved in nondeterministic polynomial time. Any problem class to which an NP-complete problem can be reduced is likely to be intractable.

Probability is the principle mathematical tool that we have to represent and reason about uncertainty. Bayes proposed a rule for updating subjective probabilities in the light of new evidence. This rule forms the basis of the modern approach to uncertain reasoning in AI.

Decision theory combines probability theory with utility theory (which provides a framework for specifying the preferences of an agent) to give a general theory that can distinguish good actions from bad ones. </br></br>
<b>Economics</b><br/>
    How should we make decisions so as to maximize payoff?
    How should we do this when others may not go along?
    How should we do this when the payoff may be far in the future?

 Utility, Decision Theory, Game Theory, Operations Research.</br></br>
   <b>  Psycology</b></br>
     The principle characteristic of cognitive psychology is that the brain processes and processes information. The claim is that beliefs, goals, and reasoning steps can be useful components of a theory of human behaviour. The knowledge-based agent has three key steps:</br></br>

    Stimulus is translated into an internal representation
    The representation is manipulated by cognitive processes to derive new internal representations
    These are translated into actions

  <b>   Sociology</b> </br>
     How is AI related to sociology?
From a sociological perspective, it can be argued that intelligent machines are not too dissimilar from “regular” social agents: they are socialized thanks to (datafied) learning processes, and practically contribute to the reproduction of material and symbolic inequalities – as in the cases of race and gender .
</br></br>
    <b> Linguistics</b></br>
     Having a theory of how humans successfully process natural language is an AI-complete problem - if we could solve this problem then we would have created a model of intelligence.

Much of the early work in knowledge representation was done in support of programs that attempted natural language understanding. </br></br>
     
   <b>Neuroscience</b><br/>
How do brains process information?

Neuroscience is the study of the nervous system, especially the brain. We are still a long way from understanding how cognitive processes actually work. The truly amazing conclusion is that a collection of simple cells can lead to thought, action, and consciousness or, brains cause minds.The only real alternative theory is mysticism: that minds operate in some mystical realm that is beyond physical science.</br>
     
<b> Mathmatics</b><br/>
    What are the formal rules to draw valid conclusions?
    What can be computed?
    How do we reason with uncertain information?</br></br>
<b>Computer Science</b><br/>
         How can we build an efficient computer?

 Operational computer and operational programmable computer

AI has pioneered many ideas that have made their way back to mainstream computer science, including time sharing, interactive interpreters, personal computers with windows and mice, rapid development environments, the linked list data type, automatic storage management, and key concepts of symbolic, functional, declarative, and object-oriented programming.</br></br>
 <b>    Control Theory</b> <br/>
         How can artifacts operate under their own control?

 control Theory, Homeostatic and objective function.
</br></br>

     
  <b>Applications of AI</b></br></br>
     
 1. AI in Astronomy

    Artificial Intelligence can be very useful to solve complex universe problems. AI technology can be helpful for understanding the universe such as how it works, origin, etc.</br></br>

2. AI in Healthcare

    In the last, five to ten years, AI becoming more advantageous for the healthcare industry and going to have a significant impact on this industry.
    Healthcare Industries are applying AI to make a better and faster diagnosis than humans. AI can help doctors with diagnoses and can inform when patients are worsening so that medical help can reach to the patient before hospitalization.</br></br>

3. AI in Gaming

    AI can be used for gaming purpose. The AI machines can play strategic games like chess, where the machine needs to think of a large number of possible places.</br></br>

4. AI in Finance

    AI and finance industries are the best matches for each other. The finance industry is implementing automation, chatbot, adaptive intelligence, algorithm trading, and machine learning into financial processes.</br></br>

5. AI in Data Security

    The security of data is crucial for every company and cyber-attacks are growing very rapidly in the digital world. AI can be used to make your data more safe and secure. Some examples such as AEG bot, AI2 Platform,are used to determine software bug and cyber-attacks in a better way.</br></br>

6. AI in Social Media

    Social Media sites such as Facebook, Twitter, and Snapchat contain billions of user profiles, which need to be stored and managed in a very efficient way. AI can organize and manage massive amounts of data. AI can analyze lots of data to identify the latest trends, hashtag, and requirement of different users.</br></br>

7. AI in Travel & Transport

    AI is becoming highly demanding for travel industries. AI is capable of doing various travel related works such as from making travel arrangement to suggesting the hotels, flights, and best routes to the customers. Travel industries are using AI-powered chatbots which can make human-like interaction with customers for better and fast response.</br></br>

8. AI in Automotive Industry

    Some Automotive industries are using AI to provide virtual assistant to their user for better performance. Such as Tesla has introduced TeslaBot, an intelligent virtual assistant.
    Various Industries are currently working for developing self-driven cars which can make your journey more safe and secure.</br></br>

9. AI in Robotics:

    Artificial Intelligence has a remarkable role in Robotics. Usually, general robots are programmed such that they can perform some repetitive task, but with the help of AI, we can create intelligent robots which can perform tasks with their own experiences without pre-programmed.
    Humanoid Robots are best examples for AI in robotics, recently the intelligent Humanoid robot named as Erica and Sophia has been developed which can talk and behave like humans.</br></br>

10. AI in Entertainment

    We are currently using some AI based applications in our daily life with some entertainment services such as Netflix or Amazon. With the help of ML/AI algorithms, these services show the recommendations for programs or shows.</br></br>

11. AI in Agriculture

    Agriculture is an area which requires various resources, labor, money, and time for best result. Now a day's agriculture is becoming digital, and AI is emerging in this field. Agriculture is applying AI as agriculture robotics, solid and crop monitoring, predictive analysis. AI in agriculture can be very helpful for farmers.</br></br>

12. AI in E-commerce

    AI is providing a competitive edge to the e-commerce industry, and it is becoming more demanding in the e-commerce business. AI is helping shoppers to discover associated products with recommended size, color, or even brand.</br></br>

13. AI in education:

    AI can automate grading so that the tutor can have more time to teach. AI chatbot can communicate with students as a teaching assistant.
    AI in the future can be work as a personal virtual tutor for students, which will be accessible easily at any time and any place.

     
     
     
