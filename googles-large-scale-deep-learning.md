Google Large Scale NN Project

Artificial Intelligence and Machine Learning
 - AI: Making machines intelligent
 - ML: Making machines that learn

What is Deep Learning?  
 - A modern reincarnation of ANN’s from 80s & 90s
 - A collection of simple trainable mathematical units, which collaborate to compute a complicated function
 - Only very loosely inspired by what (little) we know about the biological brain

DistBelief: Google’s large-scale deep learning infrastructure
 - Desired NN partitioned into four chunks (separate machines)
 - Add another layer of parallelism
 - replicas training on different data

Does everyone need this?  
 - Def not!
 - The biggest models are not necessarily the best
 - A few clever people with a few GPUs can train a mighty fine deep net plenty fast enough

When do I recommend Deep Learning to someone at the “C” level (CEO, CFO, etc.)?
 - Is this a "machine perception act” (hearing, vision, photo recognition, etc.)? Then (basically) try deep learning right away! 
 - Do we have a mountain of (labelled) data? But, benchmark first, then try machine learning next quarter.
 - If you don’t have a mountain of data… you probably should have a mountain of data.  So, bootstrap more data.

Deep learning drawbacks
 - demands large data sets - larger than available in many domains
 - Substantially greater in computational costs (than most alternatives)
 - Not yet that easy to do this - may require expertise that you don’t have in-house yet
 - More black-box and less interpretable than alternatives - although this is an area of active research