
# Protein Mutation Stability

This project estimates how a single amino-acid mutation may affect protein stability. Given a wild-type protein sequence and a mutation such as `V42A`, it predicts the expected change in stability as a continuous ddG value.

The project uses the public MegaScale protein-stability dataset. It validates sequences and mutation notation, keeps related proteins separated across training and evaluation splits, and contains code for a ridge baseline and a regression head trained on frozen ESM-2 features.


