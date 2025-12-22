# Hey there! 👋 I'm Aaron! 

I’m building a **production-style trading system in Rust**, focused on **execution correctness, determinism, and operational safety**.

https://github.com/aa-thomas/trading-systems

This profile documents an **active engineering journey**, not a finished product.

---

## What I’m Working On

I’m designing and implementing a trading system incrementally, treating it as a real production system from day one:

- deterministic simulations and replay  
- explicit order lifecycle state machines  
- execution pipelines with reconciliation  
- hard risk limits and fail-closed behavior  
- operator-focused observability and controls  

Each stage is built to surface **real failure modes** early — before real capital or live risk is involved.

---

## Why This Project Exists

Most trading system failures are not strategy failures — they are systems failures:

- state desynchronization  
- missing invariants  
- unsafe retries  
- unclear ownership of truth  
- poor operational visibility  

This project exists to learn how to **design systems that survive failure**, not just perform well under ideal conditions.

---

## Design Principles

- **Determinism by default**  
  Same inputs + config ⇒ same outcomes.

- **Explicit state machines**  
  Illegal states should be unrepresentable or rejected.

- **Fail closed under uncertainty**  
  If state, data, or truth is unclear → stop.

- **Replayable by construction**  
  Every decision should be explainable after the fact.

- **No hidden panics in core logic**  
  Errors are part of the system’s contract.

- **Documentation is part of the system**  
  Invariants, runbooks, and design tradeoffs matter.

---

## Current Focus Areas

- Rust for systems programming  
- Event-driven architectures  
- Order and execution modeling  
- Risk rules as code  
- Deterministic replay & observability  

As milestones are completed, they’ll be tagged, documented, and linked here.

---

## Status

This is an **active, evolving build**.

The goal is not to rush to “live trading,” but to build a system that would be **trustworthy once it gets there**.

---

## Notes

This work is intentionally **systems-first**, not strategy-first.

Execution correctness, safety, and operability come before optimization or alpha.


### 📫 Connect with Me
- **GitHub Discussions** – Feel free to open a discussion or issue on any of my repositories.
- **My [LinkedIn](https://www.linkedin.com/in/aaronthomas-dev/)**
- **My [Twitter](https://x.com/the_aaronthomas)**
- **My Email** – aarthomas01@gmail.com
