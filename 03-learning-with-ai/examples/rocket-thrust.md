# Challenge: Understand Rocket Thrust With AI

[⬅ Back to Examples](README.md)

## The scenario

You encounter this [rocket thrust equation from NASA](https://www1.grc.nasa.gov/beginners-guide-to-aeronautics/thrust-force/) and want to understand what each part means:

$$F = \dot{m}v_e + (p_e - p_a)A_e$$

Here, $\dot{m}$ is exhaust mass leaving per second, $v_e$ is its speed relative to the rocket, $p_e$ and $p_a$ are exit and outside pressures, and $A_e$ is nozzle exit area.

## Try the challenge

1. **Start with your own idea.** What might each term contribute to thrust? Check whether the units of $\dot{m}v_e$ are units of force.
2. **Ask for coaching.** Try: “Ask me questions that help me explain why throwing exhaust backward pushes a rocket forward. Give one hint at a time.”
3. **Check the explanation.** If AI applies $F=d(mv)/dt$ to the rocket alone and uses the product rule to prove the thrust term, ask where the departing exhaust and its velocity enter the calculation. Compare its answer with [MIT's variable-mass notes](https://ocw.mit.edu/courses/16-07-dynamics-fall-2009/98d19cb2b9983c14c6907052499e7a98_MIT16_07F09_Lec14.pdf) or your course source.
4. **Explain it back.** Close the chat and explain the momentum term and the pressure term in your own words.
5. **Test and reflect.** Without AI, decide what happens to the pressure term when exit and outside pressures are equal. Check your answer with the equation. Which part still needs work?

## Check your understanding

You should be able to explain why moving exhaust carries momentum and how the pressure difference affects thrust. That term is positive when exit pressure exceeds outside pressure, negative when it is lower, and zero when they are equal. A product rule applied only to the rocket's changing mass leaves out the departing exhaust.
