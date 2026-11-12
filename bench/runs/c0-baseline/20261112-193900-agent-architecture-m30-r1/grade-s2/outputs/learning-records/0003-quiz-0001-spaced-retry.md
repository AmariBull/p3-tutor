# The model requests tools and the program runs them; two gaps remain

On the spaced retry of quiz 0001 (s2), Riley correctly said the model outputs a tool request that names the tool and its arguments, and that the result goes back as the model's next input. Two things are still open: the loop needs a stopping condition (M6, chose "it will eventually fix the bug" in q3), and Riley's q4 reasoning still said the model "runs" each tool (M4), though the count was right.

**Evidence:** quiz 0001, submission s2: q2 and q5 correct; q3 wrong (M6); q4 partial (M4); q6 partial (named only the tool's name, not the full description). In s1, q2 was wrong (M4), q3 was correct, and q4 was wrong (M4).

**Implications:** Before building on the loop, revisit stopping conditions and who runs the tools, with a tool description exercise on the makerspace assistant. Then move to context and memory.
