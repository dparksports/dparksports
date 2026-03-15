Dear Yiling Wu,

May I share my unsought perspective on this paper? 

I recently read *"The Presupposition Problem in Representation Genesis,"* a philosophy of mind paper that asks a genuinely profound question: how does a physical system transition from merely instantiating informational states to having representations that guide behavior in content-sensitive ways?

The paper's core diagnosis is sharp. When major frameworks—LOT, teleosemantics, predictive processing—try to explain how representation first arises, they consistently smuggle in concepts that presuppose the very capacity they're trying to explain. (Fodor's Language of Thought is the clearest case: you can't learn a concept by hypothesis-testing if you need that concept to form hypotheses in the first place.) This **"Representation Presupposition"** creates a systematic explanatory deferral the paper calls the **"Representation Regress."**

I buy this diagnosis entirely. Where I push back is the paper's use of Large Language Models (LLMs) as the diagnostic case to ask its next question: *If representation genesis did not occur in a system, what capacities are missing?*

The paper treats LLMs as systems that achieve high performance "without clearly undergoing representation genesis," suggesting they rely purely on "statistical encoding" (compressing distributional patterns) rather than "content-manipulable representation" (states individuated by what they represent).

But looking closely at how models are trained, this boundary is blurrier than the paper assumes. We can actually use ML to answer the paper's foundational questions from a different, empirical angle:

1. **How does genesis occur without a "Representation Regress"?** We start with random weights—no representations at all. We optimize for next-token prediction across massive corpora. But this optimization pressure doesn't just reward memorizing n-gram statistics; it rewards building compressible, transferable structure. To predict "the glass shattered" after "the glass fell," the network must develop latent features that track physical dynamics (gravity, fragility, causal sequences). Gradient descent provides a strictly non-circular mechanism: the error signal shapes internal states to track environmental structure without presupposing prior cognitive machinery.

2. **What makes these states "count" as representations?** The paper defines content-manipulable representation by functional criteria: target-directedness, content-sensitive use, and the possibility of misrepresentation. LLMs arguably satisfy these. When a model's internal "gravity" feature systematically influences predictions across novel contexts, that is content-sensitive use. When it predicts incorrectly because that feature was activated inappropriately, that is misrepresentation. 
   
   > *This doesn't mean LLMs have human-like representations. The paper is right that architectural constraints matter—autoregressive sampling limits systematic reasoning in ways that recurrent or deliberative architectures don't. But that is a difference in representational quality, not a failure of representational genesis.*

3. **Are our philosophical categories adequate?** The paper concludes we need a new "meta-ontology of mind" to solve the genesis problem. I suspect we need something more modest: better empirical attention to how optimization dynamics organically create representational structure, and more nuanced functional criteria for when statistical patterns become representations.

The "genesis" of representation isn't just an abstract philosophical mystery—it's happening empirically in data centers worldwide. The real question is whether our conceptual categories can catch up to the mechanisms we've already built.

I’d love to hear thoughts from folks working at the intersection of ML, cognitive science, and philosophy. How clean is the boundary between statistical encoding and true representation?

---
*Tags: #MachineLearning #CognitiveScience #PhilosophyOfMind #ArtificialIntelligence #LLMs*
