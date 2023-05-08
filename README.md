# smart-gpt

Implementation of SmartGPT as an experiment to see perfomance vs [MMMLU](https://github.com/hendrycks/test) benchmark.

### Usages

To run the system:
1. you need to have the LLMU dataset in the `data` folder at the root of the directory.
2. Your open api key in a `.env` file.

Then run the notebook using Jupyter Notebook or Jupyter Lab.

```bash
jupyter notebook
```

### Design

The system works in 3 stages:

1. Generate several different solutions using CoT Reasoning [paper 1](https://arxiv.org/pdf/2305.02897.pdf)
2. Use reflection prompt to analysis each of the solution [paper 2](https://arxiv.org/pdf/2303.11366.pdf)
3. Use a resolved to analysis reflections and extract answer, this is done through dialogue-enabled resolving [paper 3](https://arxiv.org/pdf/2303.17071.pdf)

See Jupyter Notebook for more details.

### Results


### Acknowledgements

This system is entirely based on the system proposed by [AI Explained](https://www.youtube.com/watch?v=wVzuvf9D9BU)..
