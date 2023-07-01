# \[[See the project that was worked on during this hackathon](https://github.com/esbenkc/ai-cyberdefense)\] 📊 Benchmarks for safety

A submission to the [9th Alignment Jam on Safety Benchmarks](https://alignmentjam.com/jam/benchmarks).

# Benchmarks for safety using mechanistic interpretability

[This Jupyter notebook](/test.ipynb) is set up to explore different ways we can use mechanistic interpretability to benchmark for safety in AI systems. A few preliminary research questions that I want to test out:

- Can we use [DeepDecipher](https://github.com/apartresearch/deepdecipher) in a way to benchmark systems? Is there a possibility for an automated search query over many test tokens? Can we find pairs of baises? Can we find neurons associated with ill intent?
- Can we memory edit models to perform better on [MACHIAVELLI](https://aypan17.github.io/machiavelli/)?
- Can we operationalize different metrics on a per-neuron basis? Is there some sort of neuroscientific equivalent to cognitive dominance in neural networks like Transformers?
- We have activation models with an explanability score. Can we generalize this in a useful fashion? Compare different explainability scores? Can we do a review of how neuroscience does this over correlation inside neural systems, e.g. with simpler models over clusters of neurons?
- Are there other useful metrics per neuron than the ones mentioned in [DeepDecipher](https://github.com/apartresearch/deepdecipher) and can we use these to benchmark for safety?
