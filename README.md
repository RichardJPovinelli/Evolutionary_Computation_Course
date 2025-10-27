# NEAT Minimum Viable Lecture Pack (neat-python)

This pack contains three runnable, Colab-friendly exercises:
1) XOR (hello world)
2) CartPole-v1 (Gymnasium classic control)
3) Parameter sweep (population size × compatibility threshold)

## Quickstart (Google Colab)
Run this first in a new Colab notebook cell:
```
!pip -q install neat-python gymnasium[classic-control]
```
Then:
```
!unzip -o neat_mvl_pack.zip -d /content
%cd /content/neat_mvl_pack/xor
!python xor_run.py
```
Repeat similarly for `cartpole` and `sweep`.
