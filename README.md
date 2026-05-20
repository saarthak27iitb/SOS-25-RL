# Summer of Science 2026 — Reinforcement Learning


This repository is a curated map of resources for learning Reinforcement Learning over two months as part of SOS. If something isn't clicking, reach out to me.


## How to use this

- Below is the basic plan of action. I believe it covers the core topics and conceptual foundations for Reinforcement Learning but you are welcome to modify it according to your preferences and convenience
- Follow the learning path below broadly in order — each section builds on the previous
- For each topic, you don't need to exhaust every resource listed. Pick what works for you (textbook, video, or both)
---

### 1. Multi-Armed Bandits
> The simplest RL setting — no states, just decisions under uncertainty.

Start here. Bandits introduce the central trade-off of RL — **exploration vs exploitation**. If this is clear, everything downstream becomes easier.

**Resources:**
- Sutton & Barto — Chapter 2 *(primary)*
- [David Silver Lecture 9](https://www.youtube.com/watch?v=sGuiWX07sKw) — Exploration & Exploitation
- CS747 - Weeks 1,2 & 3 (lecture videos and slides are both available)

---

### 2. Markov Decision Processes
> The mathematical framework that underlies all of RL.

MDPs give you the language of RL — states, actions, rewards, policies, value functions, the Bellman equations.

**Resources:**
- Sutton & Barto — Chapters 3 & 4 *(primary)*
- [David Silver Lecture 2](https://www.youtube.com/watch?v=lfHX2hHRMVQ) — MDPs
- CS747 - Weeks 4,5 & 6

---

### 3. Model-Free Prediction & Control
> Learning from experience, without knowing how the world works.

This is core RL. Monte Carlo methods, TD learning, Q-learning, SARSA — these are the ideas most people mean when they say "reinforcement learning."

**Resources:**
- Sutton & Barto — Chapters 5 & 6 *(primary)*
- [David Silver Lectures 4 & 5](https://www.youtube.com/playlist?list=PLqYmG7hTraZDM-OYHWgPebj2MfCFzFObQ) — MC & TD Learning
- CS747 - Weeks 7,8 & 9 

---

### 4. (If you get here) Function Approximation & Deep RL
> What happens when the state space is too large for tabular methods?

This is where classical RL meets deep learning. Not everyone will reach this in two months, and that's completely fine. If you've understood the first three sections well, this is the natural next step.

**Resources:**
- Sutton & Barto — Chapters 9 & 10
- [David Silver Lecture 6](https://www.youtube.com/watch?v=UoPei5o4fps) — Value Function Approximation
- [Playing Atari with Deep Reinforcement Learning](https://arxiv.org/abs/1312.5602) — the original DQN paper *(optional, for the curious)*

---

## Primary References

| Resource | Notes |
|---|---|
| [Sutton & Barto — *RL: An Introduction* (2nd ed.)](http://incompleteideas.net/book/the-book-2nd.html) | The standard textbook. Free PDF. This is your primary reference throughout. |
| [David Silver's UCL Lectures](https://www.youtube.com/playlist?list=PLqYmG7hTraZDM-OYHWgPebj2MfCFzFObQ) | Best video companion to the textbook. Use alongside S&B. |
| [CS747 — IIT Bombay (Spring 2025)](https://www.cse.iitb.ac.in/~shivaram/teaching/old/cs747-s2025/index.html) | Full course following the same path — lecture videos, slides, and past exam problems |
| [Grokking Deep Reinforcement Learning](https://www.manning.com/books/grokking-deep-reinforcement-learning) | For the Deep RL. Pick this up after the tabular foundations are solid. |


---

##  Reaching the Mentor

If you're stuck on a concept, misunderstanding something, or want to know what to read next — just reach out. That's what this is for.



---

