## gweetings

I'm François, but I wish I was named francis so the username fransys/fr4nsyz makes more sense, but it's whateva 🫠

---

## Experience

- Software Engineering Intern - IBM  
  https://www.ibm.com/ca-en

- Open source contributor - Falco Security  
  https://github.com/falcosecurity  
  Cloud native runtime security used across IBM, AWS, Red Hat ecosystems

- Former Open Source AI Engineer - Undergraduate Artificial Intelligence Society  
  https://github.com/UndergraduateArtificialIntelligenceClub

- Former Security Engineer - UofA Blueprint Chapter  
  https://uofablueprint.com/

---

## Other work

Hackathons and project work  
https://devpost.com/Francois-Coleongco

---

## Contact

LinkedIn  
https://ca.linkedin.com/in/francois-coleongco

Instagram  
https://www.instagram.com/fr4nsyz

---

## Snippet

¬ ∃t ∈ T : forget(t)

```asm
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
