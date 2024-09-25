# TITLE: AN AI-BASED CONCEPTUAL PROJECT BUILT USING NEAT-GENETIC-ALGORITHM TO TRAIN AN AI-ENGINE TO PLAY PONG

## NEAT-Pong-Python
Using the NEAT algorithm to train an AI to play pong in Python!

## NEAT
        NEAT is a Neuro-Evolution of Augmenting Topologies Implementation

## Overview and Explanation on the concept of Genetic Algorithms

In simple terms, this is a genetic algorithm that takes inspiration from human history and natural selection and
essentially produces multiple generations of what we call genomes.

NEAT is an advanced layer on Neural Networks

The Genomes are the population of the nodes in the network and we take all the genomes, test them and 
determine what their fitness is.

The fitness of a genome is its score and a measure of how well it performs. In humans and on the basis of Natural
Selection, that will be a question of how long do you survive?

## The Theory of Natural Selection:
Natural Selection essentially states that over time, multiple generations of humans, the ones that were the smartest and the ones that were able to survive, they bred together, that created a smarter offspring and then continued on and on and on.

## Training the AI
The metric for measuring the fitness per genome is on the basis of how well they perform our tasks. i.e. the number of times the AI hits the ball. Firstly, we randomize the fitness in a shared distribution, then we keep the best genomes and discard the worst ones, bred the best genomes together and move to the next generation.

## Breeding the Genomes
This simply means that we look at the architecture of each of the NN (each genome is simply a NN) and taking those properties and merging them together into another genome and whatever the mutation is, we are breeding the best NN together and hoping to get a better offspring. That's the concept.

## Mutation Overview
NEAT will keep different species of NN in a group the species and ensure that during our various mutations, it's keeping at least one or two genomes from each species so we don't have a species going extinct. The essence of this is due to the fact that a Recessive-NN (RNN) in one generation can have a promising architectural form as to becoming a Dominant-NN (DNN) in another mutative-generation.
