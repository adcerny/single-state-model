# Single State Model

An architectural stance for reducing distributed coordination by limiting where state and truth can exist.

## Why
Distributed asynchronous coordination is not free. It adds retries, compensations, eventual consistency, and cognitive load. Systems often run, but coherence becomes accidental and operation becomes quietly exhausting.

## The idea
The Single State Model prioritises coherence over distribution-by-default. It centralises critical state, keeps the write path explicit, and treats asynchronous workflows as the exception rather than the foundation.

## Read the full write-up

- [Single State Model – full description](single-state-model.md)

## Other posts:
- [LinkedIn](https://www.linkedin.com/pulse/single-state-model-restoring-coherence-distributed-systems-adam-cerny-x5ake/?trackingId=sUzuLLRyQZ6WFRmvKQssQA%3D%3D)
- [dev.to](https://dev.to/adamcerny/single-state-model-architecture-1269)
- [Medium](https://medium.com/@adamcerny_16041/single-state-model-architecture-d0fa24ff8528)

## Notes
This repo exists as a stable, bookmarkable home for the idea.
