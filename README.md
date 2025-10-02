# register_spill_debug
An easy to view register spill from PTX and SASS instructions. Though PTX is pre-compiled code, not runtime execution trace, you'd need runtime profiling data (like from Nsight Compute) to know actual warp assignments.

This is just to help me track down the local spills in generated PTX in compile time, see exactly what the compiler decided to spill and understand why your kernel is slow before profiling.

Also (just for caution) this is vibecoded from claude 4.5. An "ulterior" motive of mine is also to test out how good is 4.5 in one shot generation. It have been long since I touched HTML, CSS and JavaScript. Pardon claude if it makes any mistake.

And let me know if anything fruitful we can add into this to make it a little more info rich.
