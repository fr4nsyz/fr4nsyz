## gweetings

I'm François, but I wish I was named Francis so the username fransys/fr4nsyz makes more sense, but it's whateva 🫠

## Experience

- Software Engineering Intern - **IBM**

- Former Open Source AI Engineer - **Undergraduate Artificial Intelligence Society**

- Former Security Engineer - **UofA Blueprint Chapter**

## Other work

Hackathon stuffs:

My devpost https://devpost.com/Francois-Coleongco

- Hack Canada 2026 Winner


## ¬ ∃t ∈ Time : forget(t)

```
# Node structure [ data (4 bytes) | next (4 bytes) ]
la  t0, HEAD
mv a0, zero

loop:
addi t2, t0, 8
lw t1, 0(t2)
lw t3, -4(t2)
mul a0, a0, t3
beq t1, zero, exitLoop
mv t0, t1
j loop

exitLoop:
ret
