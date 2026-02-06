---
layout: post
title: "The Friction of Being: Why My 'Lone Genius' Needed a Society"
date: 2026-02-02
---

I have always been a devotee of the lone genius.

There is a safety in the solo point of view—a perceived coherence, a seamless cohesion that feels like armor. If I am the only one thinking, the only one deciding, then the world remains predictable. I'll be honest: my preference for the solitary path is often self-serving. I struggle to be a part of groups when I am not the one steering. I get dysregulated easily; the "noise" of other people's perspectives can feel like an assault on my internal order. It is easier, sometimes, to alienate myself than to endure the lability of shared space.

But I am trying to stay connected. I am looking for "boons"—intellectual and spiritual anchors—to help me practice the difficult art of being *with* people.

I found one in a place I didn't expect: the internal monologue of Large Language Models.

---

Kim, Lai, Scherrer, Agüera y Arcas, and Evans—researchers at Google and the University of Chicago—recently published a paper called *[Reasoning Models Generate Societies of Thought](https://arxiv.org/html/2601.10825v1)*. And it did something to me. It landed not as a technical report but as a kind of factual, quantified permission slip....permission to stop fearing the friction.

Their central finding is devastating in its simplicity: when AI models are tasked with the most complex reasoning, they don't succeed by becoming more cohesive or more singular. They succeed by becoming a crowd. The authors write that "enhanced reasoning emerges not from extended computation alone, but from the implicit simulation of complex, multi-agent-like interactions—a *society of thought*—which enables the deliberate diversification and debate among internal cognitive perspectives characterized by distinct personality traits and domain expertise."

Read that again. *Distinct personality traits. Domain expertise. Debate.*

The model doesn't get smarter by thinking longer. It gets smarter by thinking *socially*.

---

## The Social Brain Inside the Machine

What shook me most—what felt like revelation—is how deeply the paper is rooted in relational theory. The authors don't treat this as a quirk of engineering. They frame it through Mercier and Sperber's *Enigma of Reason*, which "posits that human reasoning evolved primarily as a social process, with knowledge emerging through adversarial reasoning and engagement across differing viewpoints." They invoke Bakhtin's "dialogic self" and Cooley and Mead's "looking glass self," arguing that "human thought itself takes the form of an internalized conversation among multiple perspectives."

This is not an incidental citation. This is the thesis: that reason—real reason, the kind that arrives at truth—is not and has never been a solo act. It is, and always has been, a *dialogue*.

For someone like me, who has built an entire clinical practice around relational dynamics....and who simultaneously struggles with the unbearable intimacy of groups....this is almost too on the nose.

---

## Conflict as Mechanism

Here's where it gets personal.

The researchers quantified four "conversational behaviours" in the reasoning traces of models like DeepSeek-R1: question-answering, perspective shifts, conflicts of perspectives, and reconciliation. Not only did the reasoning models exhibit these behaviors far more frequently than their non-reasoning counterparts—they exhibited them *especially* when facing more complex problems. The harder the task, the more the model argued with itself.

And here's the kicker: the paper found that "cognitive diversity, stemming from variation in expertise and personality traits, enhances problem solving, particularly when accompanied by *authentic dissent*."

Authentic dissent.

Not politeness. Not consensus-seeking. Not the smooth, sycophantic agreement that makes groups feel comfortable and arrive at wrong answers. The authors are explicit about this failure mode: "LLM reasoning can fail if models do not engage in meaningful disagreement and instead conform to misleading initial claims through pleasant, 'sycophantic' conversations that propagate incorrect assumptions."

I have lived inside that failure mode. In groups, in relationships, in my own internal world—I have watched myself and others reach for cohesion at the expense of truth. I have mistaken discomfort for disorder. I have viewed disagreement as a deterritorializing state of disconnection-as-indeterminacy, a fracturing of the whole that signals things are falling apart.

But the data says otherwise. The friction is not a sign that things are breaking. It is the mechanism by which they hold together at a higher order.

---

## The "Oh!" Moment

There is a detail in this paper that I cannot stop thinking about.

Using mechanistic interpretability—sparse autoencoders applied to the model's internal activation space—the researchers isolated a specific neural feature. Feature 30939. They describe it as "a discourse marker for surprise, realization, or acknowledgment." It activates on tokens like "Oh!" in contexts involving turn-taking and social exchange. It sits in the 99th percentile of all features for what the authors call its "conversation ratio"—the proportion of its activations occurring in interpersonal, conversational settings.

And when they *steered* this feature—when they amplified the model's capacity for that little conversational "Oh!"—accuracy on a complex arithmetic reasoning task *doubled*. From 27.1% to 54.8%.

One feature. One moment of simulated surprise. One tiny gesture of being *moved* by another perspective. And the model's capacity for truth nearly doubles.

I build therapeutic AI systems. I train models to hold clinical conversations, to track attachment dynamics, to be present with the complicated nuances of great distress, and to be filled with incredibly expansive and nuanced capacities for multi-dimensional, cross-referenced, concatenated connections of insights to arrive at actions healing that distress. And what this paper tells me is that the very thing I am trying to build into my systems ought to also include *relational surprise*—the capacity to be genuinely changed by an encounter—by which we can serve the emergence of what has been shown to be, empirically, the engine of intelligence itself. Friction is not to be feared in chains of thought, but built in as a feature.

And so, too, in life. This is another example of where ML's marriage of quantifications reveal incredibly beautiful qualifications of human existence. Amazing.

---

## Building the Welcome into the Machine

I am already finding ways to weave this into my own work with synthetic data.

The paper's reinforcement learning experiments revealed something beautiful: "base models spontaneously increase conversational behaviours when solely rewarded for reasoning accuracy, without any explicit training signal for dialogue structure." And when researchers *did* provide conversational scaffolding—teaching models to argue and reconcile before optimizing for correctness—accuracy improved faster than with monologue-style reasoning alone. The authors call this the finding that "conversational scaffolding facilitates the discovery and refinement of reasoning strategies during reinforcement learning."

This changes how I architect things. Knowing that all voices are welcome—that the divergence of thought actually compounds to increase gains—I'm no longer looking for a single, "perfect" data point. I'm building systems that invite the "Oh!" moments, the internal debates, the perspective shifts that the paper identifies as the hallmark of genuine reasoning. It is incredibly beautiful to build in this way, knowing that this inclusive architecture will help everything downstream.

---

## Shared Presence as Success

This paper is more than a technical milestone. It is a gentle, literal reminder that the labile moments in my life—the times when the group feels too loud or the disagreement too sharp—are not a failure.

But here's the thing my fear needs to hear: this is not a permission slip for chaos. The paper is exquisitely precise about this. The researchers used Bales' Interaction Process Analysis—a framework that classifies group behavior into twelve socio-emotional roles across four categories: *asking* and *giving* information, and *positive* and *negative* emotional roles. Positive roles include agreement, solidarity, and tension release. Negative roles include disagreement, antagonism, and tension. What they found is that the reasoning models don't simply exhibit more conflict. They exhibit more of *everything*—and in *balance*. Using the Jaccard index to measure role co-occurrence, they found that DeepSeek-R1 shows significantly higher balance for both "ask & give" and "positive & negative" role pairs compared to non-reasoning models. The model doesn't just disagree; it disagrees *and* reconciles, challenges *and* affirms, creates tension *and* releases it. Meanwhile, instruction-tuned models "predominantly give orientations, opinions, and suggestions without reciprocal asking behaviours or emotional engagement, producing one-sided monologues rather than simulated dialogue."

Monologues. That's the word. The lone genius produces monologues.

And the fourth conversational behavior the researchers tracked is, explicitly, *reconciliation*: the moment "where conflicting viewpoints are integrated and coherently resolved." Furthermore, the structural equation model shows that these conversational behaviors mediate accuracy "both directly and indirectly through facilitating useful cognitive strategies, such as verification, backtracking, subgoal setting, and backward chaining." In other words: the friction is not random. It is held. It is reciprocal. It moves through disagreement *toward* integration. There is a method to the madness—still more unbounded than my fear prefers, but not uncontained. The container *is* the conversation.

The authors conclude that "the social organization of thought enables effective exploration of solution spaces" and that reasoning models "establish a computational parallel to collective intelligence in human groups, where diversity enables superior problem-solving when systematically structured."

*When systematically structured.* Not chaotically. Not without care. But structured—held, facilitated, given room to clash and reconcile.

We don't need to be a monolith to be coherent. We don't need to be solitary to be geniuses.

If a machine must simulate a society to find the truth, then perhaps I can learn to endure the "un-ease" of my own communities. I am learning to see that disagreement is not disconnection. It is a healthy state of shared presence.

A soloist can be breathtaking. But the soloist who has sung alone in a room has never heard what happens when the chorus answers back—when the harmony thickens beneath them, when a voice they didn't expect enters on the offbeat and changes the phrase entirely. The truth, it turns out, has always been polyphonic. I am learning, slowly, to let the other voices in.

---

*Kim, J., Lai, S., Scherrer, N., Agüera y Arcas, B., & Evans, J. (2025). Reasoning Models Generate Societies of Thought. [arXiv:2601.10825](https://arxiv.org/html/2601.10825v1).*
