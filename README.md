# Transformers with Cosine Similarity

This repository contains a modified version of the Transformers code where the attention mechanism has been altered to use cosine similarity between the Query (Q) and Key (K) vectors.

## Motivation

Traditional attention mechanisms in Transformers use dot-product attention to compute the attention scores. This modification introduces cosine similarity, which may provide different characteristics to the attention mechanism.

## Changes Made

The main modification lies in the attention computation, where the cosine similarity between Q and K vectors is employed instead of the dot product.


