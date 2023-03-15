# tf-doom-like-rng
Every time you run this terraform, you get a predictable pseudo-random number based on the method used in Doom (1993).

## Why?

I wanted to see how easy it would be to store arbitrary values in state, and then iterate on them with subsequent runs.

You would never use this in Production (or even Test), I'm just interested in making Terrraform do strange things.

This currently only works on local state files, but should be trivial to extend into reading remote state files (S3 buckets, Azure Storage Accounts etc)
