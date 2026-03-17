# SAT Competition 2026: Call for Solvers, Benchmarks, and Proof Checkers

SAT Competition 2026 is a competitive event for solvers of the Boolean Satisfiability (SAT) problem. It is organized as a satellite event of the 29th International Conference on Theory and Applications of Satisfiability Testing and continues the tradition of annual SAT Competitions and Races. The registration deadline is April 19, 2026 (23:59 AoE). More details are available on the competition website: <https://satcompetition.github.io/2026/>.

SAT solving has seen tremendous progress in recent years. Many problems in hardware and software verification that were out of reach a decade ago can now be solved routinely. Alongside new algorithms and better heuristics, refined implementation techniques have been essential to this success.

To sustain this momentum, we invite solver developers to present their work to a broad audience and compare it with that of other teams.

SAT Competition 2026 will include the following tracks:

* Main Track (including the option to choose among different proof checkers)

* Experimental Track (no proof checking)

* Parallel Track

* Cloud Track

## New This Year

### New Infrastructure for the Main Track

For the first time, SAT Competition 2026 will run on KIT's NHR system HoreKa/Blue in Karlsruhe. Details of the submission process will be published on the competition website.

### AI-Generated and AI-Tuned Solvers Have a Separate Sub-Track

There will be separate subcategories for AI-generated and AI-tuned solvers in each of the Main, Experimental, Parallel, and Cloud tracks. 
The same rules and limitations that apply to each track also apply to solvers flagged as AI-generated and/or AI-tuned.
However, these solvers are not eligible for regular track prizes. An award will be given to the best AI-tuned and AI-generated solver in each track.

### Benchmark Selection Script

For the first time, we are publishing the benchmark selection script _before_ receiving benchmark instances. The script is available for download on the competition website, and we welcome comments. Feel free to review the script before the solver registration deadline.

### System and Benchmark Descriptions Are Reviewed More Strictly and Require AI Statement

We will review system and benchmark descriptions more carefully than in past competitions and reserve the right to reject submissions that do not meet a baseline quality standard.
Specifically, your system description must report the original solver codebase and version,
along with the number of lines edited or added by humans and the number of lines edited or added by artificial intelligence.

## Aspects to Highlight

### Submission of Proof Checkers

Teams wishing to submit a proof checker must provide both the checker and its documentation by March 20, 2026 (23:59 AoE).

### Bring Your Own Benchmarks (BYOB)

Each team participating in the Main Track must submit 20 new benchmark instances that have not appeared in previous competitions, together with a description of their source and generation process. At least 10 of these benchmarks should be of moderate difficulty: neither too easy (solvable by MiniSat within one minute) nor too hard (not solved by the participant's own solver within one hour).

### PAR-2 Scoring Scheme

Solvers will be ranked by penalized average runtime (PAR-2). A solver's PAR-2 score is its average runtime over all instances, where each unsolved instance contributes twice the time limit.

Best regards,

The SAT Competition organizers
