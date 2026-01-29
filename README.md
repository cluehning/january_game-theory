# Prisoner's Dilemma — From Fractals to Evolutionary Game Theory

## How the Mandelbrot Set Brought Me Here

This project began with a deep curiosity about complexity.

My first step was exploring the **Mandelbrot set**, a fractal created from the simple iteration:

    z → z² + c

What fascinated me was that such a simple rule produced infinite complexity — structure, self‑similarity, order, and chaos all intertwined.

That experience planted the idea:

**Simple rules can create incredibly rich behavior.**

---

## From Fractals to Chaos Theory

After Mandelbrot, I moved on to the **logistic equation**:

    xₙ₊₁ = r · xₙ · (1 – xₙ)

I generated the **bifurcation diagram**, and again I saw:
- stable fixed points  
- periodic cycles  
- sudden transitions  
- chaotic regimes  

All emerging just by changing one parameter.

This pushed me toward thinking about biological systems:
How does complexity arise in populations?
When does behavior stabilize — and when does it collapse into chaos?

---

## Enter Evolutionary Game Theory

That question led me directly to **evolutionary games**.

In biology, cooperation is a mystery:
organisms could defect and exploit others, yet cooperation still evolves.

The **Iterated Prisoner's Dilemma** captures this tension perfectly:
- Cooperate  
- Defect  
- Watch how strategies interact over time  

When combined with **replicator dynamics**, strategy frequencies in a population start to behave just like the logistic map:

    dx/dt = x (fitness_x – average_fitness)

Sudden shifts, stable coexistence, extinction —  
the same patterns from chaos theory reappear.

---

## What This Project Contains

- Prisoner's Dilemma payoff matrix  
- Classic strategies (Cooperate, Defect, Tit‑for‑Tat)  
- Repeated game simulation  
- Round‑robin tournament between strategies  
- Score plots and basic visualizations  
- Planned: replicator dynamics (evolution of strategies)  
- Planned: bifurcation diagrams based on payoff parameters  

---

## Why This Project Exists

This repository is the intersection of:

- fractal geometry  
- chaos theory  
- biological reasoning  
- algorithmic strategy dynamics  
- curiosity about how complexity emerges  

It is a continuation of the same mathematical story that started with Mandelbrot and grew through the logistic map — now applied to cooperation and conflict in evolving populations.

---

## License

MIT License
