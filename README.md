# Abu Bakar Siddique

Final-year BSc Computer Science and Technology at UESTC, Chengdu. Originally from
Brahmanbaria, Bangladesh.

I study AI reliability, which for me mostly means asking whether a model gives the same
answer when the same problem arrives in a different shape. My undergraduate research does
exactly that with network control: take one virtual network function placement instance,
encode it five ways (edge list, adjacency matrix, prose, JSON, ranked neighbour lists), and
see whether the placement survives the change. It does not always. Feasibility moved by 17.5
points for one model on formatting alone, while the other barely noticed. Worth knowing
before anyone hands a model the keys to a network.

Outside that I write small programs that measure something instead of assuming it. Most of
them do one job, print a short report, and stop.

## Right now

- Finishing the placement study and writing it up
- The other paper is a collaborative one, on AI adoption and green innovation in Chinese
  firms, where I cover the computer science side
- Filling in gaps in my systems background, mostly networking and distributed code

## Selected repositories

- [vnf_llm_sensitivity](https://github.com/abubakarsiddique360/vnf_llm_sensitivity), the
  pipeline behind the study above: five encodings, 150 instances, 3,500 queries, and an ILP
  baseline to compare against.
- [cuda-nbody-simulation](https://github.com/abubakarsiddique360/cuda-nbody-simulation)
  compares a serial N-body solver with a shared-memory tiled one. 985x faster on a T4.
- [mpi-sieve-of-eratosthenes](https://github.com/abubakarsiddique360/mpi-sieve-of-eratosthenes)
  is five MPI sieve implementations, textbook version up to a bit-packed one, benchmarked on
  a 96-core cluster.
- [SymptomPilot-AI](https://github.com/abubakarsiddique360/SymptomPilot-AI) is a local-first
  triage assistant: retrieval with citations, plus a rule-based red-flag check that runs
  before any model output. No API key needed to try it.
- [draftproof](https://github.com/abubakarsiddique360/draftproof) is a writing pipeline that
  will not publish a claim it cannot trace back to a source.
- [KubeClinic-AI](https://github.com/abubakarsiddique360/KubeClinic-AI) reads Kubernetes
  manifests for security and reliability problems and proposes a fix for each finding.

Everything else is on the repositories tab.

## Elsewhere

- Website: [cs-abubakarsiddique.me](https://cs-abubakarsiddique.me)
- Email: abubakarsiddique.cst@gmail.com
- LinkedIn: [e-abs](https://www.linkedin.com/in/e-abs)

Coursework so far has covered deep learning, NLP, databases and network systems. I read and
write Bangla, English and Chinese (HSK 4). Happy to talk about any of it, especially
evaluation for agents, which is the part of this field I find least settled.