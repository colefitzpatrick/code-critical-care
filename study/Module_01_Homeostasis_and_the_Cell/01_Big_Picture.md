# 01 · The Big Picture (start broad)

Read this for the **model and the logic**. Do not try to memorize. You're building the
frame everything else hangs on.

---

## The one-sentence model
> **A living cell is a controlled compartment that spends energy to stay different from
> its environment, and the body spends energy to keep that environment constant.**

Two levels of the same idea:
- **Cell level:** keep the *inside* different from the *outside* (gradients).
- **Body level:** keep the *outside of the cell* (the internal environment) constant
  (homeostasis).

Disease = that control fails. Everything downstream is consequence.

---

## Engineering translation (your unfair advantage)

| Physiology word | What it actually is (your language) |
|---|---|
| Concentration gradient | A potential difference; drives flux: `J ≈ -D · dC/dx` (Fick) |
| Diffusion | Spontaneous transport down a gradient, ΔG < 0, no ATP |
| Active transport | A pump doing work *against* a gradient, ΔG > 0, **needs ATP** |
| Osmosis | Water moving to equalize *water* chemical potential (solute pulls water) |
| Homeostasis | A **closed-loop control system**: sensor → controller → effector |
| Set point | The controller's reference value (the SP in a PID loop) |
| Negative feedback | Error-correcting control (stabilizing) — ~99% of physiology |
| Positive feedback | Self-amplifying loop (explosive, must be terminated) |

If you ever feel lost later, translate the physiology back into this column. It's the
same math you already know.

---

## The core logic chain (this is the spine of the module)

```
Cell must do work to live
        ↓ (why?)
It must keep ion/solute gradients (esp. high K+ in, high Na+ out)
        ↓ (how?)
Selective membrane (barrier) + Na⁺/K⁺-ATPase pump (the engine)
        ↓ (so what?)
Gradients store energy → used for: resting membrane potential,
        secondary active transport, signaling, water balance
        ↓ (and the body's job?)
Keep the cell's *external* environment constant (temp, pH, ions, glucose, volume)
        ↓ (how?)
Negative-feedback loops: sensor → integrator → effector → corrects the error
        ↓ (clinical punchline)
Break the pump, the barrier, or the loop → predictable disease + predictable assessment
```

You will redraw a richer version of this in `02_Concept_Map.md`. This skeleton is the
trunk; the map adds branches.

---

## The 5 ideas everything else links back to
1. **Compartments & gradients** — inside ≠ outside, on purpose, at energy cost.
2. **The membrane is selective** — it *chooses* what crosses; that selectivity is control.
3. **The Na⁺/K⁺ pump is the master engine** — 3 Na⁺ out / 2 K⁺ in per ATP; it sets up
   nearly every other gradient (directly or indirectly).
4. **Homeostasis = negative feedback** — set point, error, correction. Stable by design.
5. **Tonicity decides cell volume** — water follows solute; this is why IV fluids can
   help or kill.

> Hold these 5. When you read `03_Notes`, you're just adding *why* and *consequence* to
> each one. When you do `05_Clinical_Reasoning`, you're just running them on patients.

➡️ Next: open `02_Concept_Map.md` and draw Tier 1 once while looking at it.
