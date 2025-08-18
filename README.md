# Kendall Jon Butler

## Introduction

As an entry level data scientist, I look forward to directing my skills toward bringing insight and data-driven solutions to my future company. As a PhD, I am confident in my ability to adapt to new problems and persevere through difficult projects. This page will serve as a homepage, presenting my major projects in addition to some additional forthcoming portfolio projects, but first, here is a bit more about me:

I earned a BS in physics from the University of Maine in 2020, getting highest honors for my thesis "Investigating the Stability of Observed Low Semi-major Axis Exoplanetary Systems With Hypothetical Outer Planets Using The Program Mercury6". This included the plotting of various simulation data using python. After college, I went on to pursue a PhD in Physics from Drexel University. At first I worked with a mulit-school collaboration called PROSPECT, for which I analyzed a background radiation data using C++ in order to help remove background effects from their results. Later that year, I joined the Computational Biophysics group and began work on simulation of biologically inspired neuronal networks, specifically simulating traveling waves through sheets of neurons. That year, I re-wrote a previous students code, transferring our project from MATLAB to python using the BRIAN neural simulator. After four years working with the computational Biophysics group, I earned a PhD for my dissertation titled "Pathway Formation and Dynamical Transitions by Neuronal Traveling Waves with Plasticity". Part of this work is published in the Journal of Computational Neuroscience as "Neuronal traveling waves form preferred pathways using synaptic plasticity". Links to these works in addition to a repository for recreation of results in this published paper are included in the projects section of this page. 

Now that I have earned my PhD, I look forward to taking the next steps in my career. With years of experience working and teaching using python, I have a solid bedrock on which to begin a career in data-science. In addition, my experience in physics and my work as a PhD researcher have given me excellent tools, including problem solving, adaptability and perseverance through difficult projects. I am confident that I can learn and adapt to any challenges that I may face as a data scientist, and am excited to leverage my skillset to bring data-focused insights to problems that are faced by my future employer.

## Projects

### 1 - Neuronal traveling waves form preferred pathways using synaptic plasticity - Published in the Journal of Computational Neuroscience

**link to open-access paper:** [(https://link.springer.com/article/10.1007/s10827-024-00890-2)]

**repository:** [(https://github.com/kjb-research/JCN-Traveling-Wave-Pathways)]

This paper simulated traveling waves through a thin (3-layer) sheet of neurons using various mechanisms of input stimulation. The neurons in these simulations (like real neurons) communicated via synapses. Put simply, each neuron has many input synapses from other neurons. When enough stimulation is recieved from those synapses, the neuron fires and it sends its own signal. When that signal reaches it's synapses, stimulation is input into those neurons in turn. We include synaptic plasticity (the ability of synapses to change with activity) in the form of Spike-Timing Dependent Plasticity (STDP), where if the neuron sending a signal spikes before the neuron recieving it, that synapse is strengthened! If the opposite occurs (a negative correlation) that synapse is weakened instead. With the addition of STDP to a network with traveling waves, directional pathways were formed over time in all cases, which we visualized using vector fields of average weight changes for each region.

### 2 - Neuronal traveling waves form preferred pathways using synaptic plasticity - Dissertation Thesis

This is the dissertation thesis I wrote and defended in order to earn my PhD from Drexel University. It includes all meaningful projects I completed during my time with the Computational Biophysics group. 

**Link to open-access dissertation:** [(https://researchdiscovery.drexel.edu/esploro/outputs/doctoral/Pathway-formation-and-dynamical-transitions-by/991022057536604721)]

#### Breakdown of Thesis parts/projects

1. **Chapter 3 - The formation of pathways** (demonstrates pathway formation by traveling waves with the addition of plasticity in the form of STDP) - this is the same as project 1 above.
2. **Chapter 4 - Delay Plasticity (breakdown below)**
   a. A phase space is delineated using various metrics connected to synaptic delays and the rate of neuron membrane recovery
   b. An adjustment of STDP to changes in synaptic delays (delay-STDP), tested for multiple types
   c. Demonstration of increased pathway formation with the combination of STDP and bidirectional delay-STDP
3. **Appendix A** - Supplementary Information for Chapter 3
4. **Appendix B** - Recreation of a project done alongside a student I mentored in the 2023-2024 academic year
5. **Appendix C** - Supplementary Information for Chapter 4
6. **Appendix D** - Additional projects, including additional neuron types, synapse models, surrogate gradient learning (BPTT for spiking signals) using PyTorch, and the effects of network damage on wave propagation
7. **Appendix E** - Visualization of the effects that adjusting various network parameters has on wave propagation

### 3 - Additional Portfolio Projects (Forthcoming)
