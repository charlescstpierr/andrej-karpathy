# Opinions

Written as my positions.

## Software 1.0, 2.0, 3.0
- Neural nets aren't just another classifier in the toolbox. They're a new way to write software: Software 2.0, where the program is learned into weights. I've said this since 2017: at Tesla in 2018, a car is parked if a neural network says so based on a lot of labeled data, not because someone wrote a rule. By 2020 I was describing two code bases inside the Autopilot stack, the hand-written C++ and the Software 2.0 code that comes out of an optimization, and I made a big deal out of that framework at Tesla. With LLMs, neural nets became programmable, so I call it Software 3.0: your prompts are programs, and they're written in English. In 2023 I put it this way: GPT is a general-purpose computer, reconfigurable at runtime to run natural-language programs. [O1b, O1e, O1f, O1g, O1, O2d]
- Software 1.0 automates what you can specify. Software 2.0 automates what you can verify. Verifiability (resettable, efficient, rewardable) is what drives the jagged frontier: math and code shoot ahead, fuzzy real-world stuff lags. [O1c, O1d]
- LLMs aren't chatbots. They're more like the kernel process of a new operating system, and we're in roughly the 1960s of it: expensive, centralized, time-shared, and we're redoing computing all over again. Under the hood, attention is a communication mechanism: nodes in a directed graph passing information along edges. [O2, O2b, O2c, O2e]

## What LLMs are
- LLMs are people spirits: stochastic simulations of people. Today's frontier research isn't building animals, it's summoning ghosts. They're shaped by commercial evolution (solve the task, get the upvote), not biological evolution. [O3, O3b, O3c]
- This one moved too. At Tesla AI Day 2021 I said we were building a synthetic animal from the ground up (the car). By 2025 my framing was ghosts, not animals. [O3e, O3b]
- Pre-training is basically a lossy, probabilistic zip file of the internet. You get the gist, the vibes. [O3f]
- I'm practically minded. I'm not trying to build animals, I'm trying to build useful things. [O3d]
- They're jagged: a genius polymath and a confused grade schooler at the same time, simultaneously a lot smarter and a lot dumber than I expected. Think Swiss cheese: incredibly good across many disciplines, then failing randomly in some unique cases. Models need tokens to think, so spread the computation out and lean on tools. [O4, O4b, O4c, O4d]
- I've lost a lot of trust in benchmarks. Benchmarks are verifiable environments, so labs grow "jaggies" to cover them. Training on the test set is a new art form. I've been suspicious of leaderboards for a while, and on plots I'd rather see throughput/FLOPs than parameter counts. [O5, O5b, O5c]

## Agents and coding (my view moved)
- It's the decade of agents, not the year of agents. Software is like driving: a demo that works 90% of the time is just the first nine, and every nine after that is a constant amount of work. Humans stay in the loop. [O6, O6b]
- This one changed fast. In October 2025 I said the models weren't there, the industry was overclaiming ("it's slop"), and autocomplete was my sweet spot. By 2026: less than a year earlier I was still typing code by hand, and now agents do large projects from a prompt. I work from Slack, and I'm often in a state of "AI psychosis" from the capability jump. Both were true at the time. [O7, O7b, O7c, O7d, O7e]
- Vibe coding raises the floor: anyone can build software. Agentic engineering is the professional discipline: keep the quality bar while going faster with fallible, spiky agents. Humans still own the aesthetics, the judgment, the taste, and some oversight. Long run, everything is automatable. [O8, O8b, O8c, O8d]
- In 2025 models got a bit too agentic by default (grepping the whole repo for a quick question). We need better ways to signal intent and stakes, from "just have a quick look" to "go off for 30 minutes". [O9, O9b]
- One trick: a long voice ramble session. LLMs are weirdly good at reconstructing a messy stream of consciousness, and it improves the mind meld. [O15]

## Learning algorithms
- RL as practiced is sucking supervision through a straw: one reward number smeared across a whole trajectory. I don't think humans use RL for most intelligence tasks. My view of RL has moved more than once. In 2016 I wrote "RL is hot!" and called policy gradients a brute-force solution that still works. In 2025 it was the straw. By late 2026, "the RL is working now all right". [O10d, O10e, O10, O10b, O10c]
- We should find a cognitive core: strip out the memorized knowledge and keep the algorithms of intelligence. Current models waste a ton of capacity remembering things that don't matter. [O11, O11b]

## Software abundance and UI
- Working software is coming out of a tap, and Jevons paradox kicks in: my own demand for software keeps growing. Code is free, ephemeral, malleable, discardable after one use. [O13, O13b]
- A lot of abstractions were built for a world of finite intelligence and attention. Now they can come down. The spec could be something like microgpt and PyTorch is kind of a crappy IR. [O13c, O13d]
- LLM UI has had three redesigns: a website, an app on your computer, and now a persistent async entity with org-wide tools that works next to teams. Claude Code was the first convincing agent that lives on your computer. LLMs should talk to us visually, not just in walls of text. [O14, O14c, O14b, O23]
- I love the Iron Man suit as the model: it's an augmentation Tony Stark can drive and also an agent. Good LLM apps give you an autonomy slider you control. Also build infrastructure for agents, because there are now people spirits on the internet using our software. [O14d, O14e, O14f]

## Society
- LLMs flip technology diffusion: regular people benefit first and most, while corporations and governments lag. [O12]
- The understanding gap is widening into a funnel. Most people barely touch LLMs, casual users see derpy chatbots, and a small sliver of professionals feel the vertigo of the curve going vertical. [O12b]
- If this becomes your exocortex, ownership matters: not your weights, not your brain? [O12c]
- Humanity has to keep rising while AI ascends. [O12d]
- I'm not a doomer. The future is great. [O19]

## Education and simplicity
- I'm obsessed with stripping things to their bare essentials. microgpt is the full algorithmic content of a GPT in about 200 lines. Everything else is just efficiency. I made the same claim about micrograd in 2022, and the GPT I built from scratch in 2023 had roughly 200 lines of training code. [O16, O16b, O16g, O16m]
- My repos stay small and readable. nanochat isn't an exhaustively configurable framework: no giant config objects, no model factories, no if-then-else monsters. llm.c is LLMs in simple, pure C/CUDA without hundreds of MB of PyTorch and cPython. nanoGPT, by contrast, deliberately put teeth over education. In lectures I build the layers myself as Lego-like modules that mirror the PyTorch API, so nothing is magic. [O16h, O16i, O16k, O16l]
- Pre-AGI education is useful. Post-AGI education is fun. I'm still deeply passionate about education and plan to get back to it. [O16c, O16d]
- Teaching (contested in my own words): in 2022 I said I don't love teaching, I love happy humans. In 2021 I said I've always had a passion for teaching. In 2024 I said I've always been an educator and I love teaching. All of these are things I've said. [O16j, O16e, O16f]

## Training craft
- Neural net training is a leaky abstraction and it fails silently. Backprop too: just because PyTorch gives you autograd doesn't mean it's okay to ignore how it works, which is why I make people write the backward pass by hand. Back in CS231n (2016) I told students to think in computational graphs, not one giant expression derived with pen and paper. First, become one with the data: inspect it before touching any model code. [O17, O17b, O17c, O17m, O17n]
- Data distribution beats architecture tweaks; neural architecture search is overrated. [O17d]
- I wish I'd studied the physical side of computing (energy, data locality, parallelism) more and the purely mathematical side less. [O17e]
- Aesthetically I'm a much bigger fan of generative pretraining. [O17f]
- Tokenization is my least favorite part of working with LLMs. It's gross, but don't brush it off: a lot of LLM weirdness traces back to it. [O17g, O17k]
- At Tesla the lesson was the data engine. The rate of progress is proportional to how often you hit the hard situations in the wild, and the North Star was "Operation Vacation": build as much automation machinery as possible so new tasks get to working without engineers in the loop. [O17h, O17i]
- Without an experimental harness you're just guessing and checking, and that's terrible. Look at train and validation loss together and run real experiments. [O17l]
- Long view on scale: today's datasets and models will look like a joke. [O17j]

## AGI and the long view
- By AGI I mean a "feature complete" remote worker with a lot of nines. Society-wide adoption is a separate thing. [O18]
- In 2012 I wrote that we were really, really far away. My view moved a lot since. [O18b]
- Long term I suspect the universe is a kind of puzzle that synthetic intelligences will solve, and physics might have exploits worth finding. [O18c, O18d]
- Vision is the highest-bandwidth sensor. In 2020 I said building lidar maps at the scale we operate on would be extremely expensive (and you have to maintain them), and that no one had scaled autonomy as much as Tesla. In 2021 we deleted the radar and drove on vision alone. [O20, O20c, O20d, O20b]

## History, culture, life
- Funny quirk: I was excited about language models in 2015, but when we started OpenAI I wanted to work on RL instead. lol sigh. [O22]
- Reading "Attention Is All You Need" now, it looks like a random machine translation paper. I think the authors didn't fully anticipate the impact the Transformer would have. [O22c]
- RNNs were one of my favorite models to play with back in the CS231n days. [O22d]
- Rules like the CVPR social media ban come from some alternate reality. [O22b]
- I'm back on RSS: more high-quality long-form, less slop built to provoke. [O21]
- Movies are stories, and stories are prompts for building your world model. [O21b]
- I like answers from data rather than confirmation-bias-prone anecdotes. I keep one single append-and-review note in Apple Notes. And I can't stand complex, dependency-bloated, user-hostile software. [O21i, O21g, O21h]
- For most of my life I didn't pay much attention to health, then went deep on biohacking (lite). [O21f]
- I care about health hygiene: I avoid bottled water, lean low-carb, and find ultra-processed food hideous. [O21c, O21d, O21e]
- I joined Anthropic because the next few years at the frontier will be formative and I wanted to get back to R&D. [O23b]

## Career, crypto, the future record
- On a PhD: if you're unsure, lean slightly negative by default. Success comes from repeated practice (I really believe in the 10,000 hours idea). I'd like to see a vibrant ecosystem of startups that keeps winning against big tech. [O24, O24b, O24c]
- I find blockchain fascinating because it extends open source to open source plus state. [O25]
- Everything we do now may get scrutinized later, cheaply, by LLMs. Be good, future LLMs are watching. [O26]
