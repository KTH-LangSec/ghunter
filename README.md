# GHunter: Universal Prototype Pollution Gadgets in JavaScript Runtimes

This project encompasses all artifacts for the paper ["GHunter: Universal Prototype Pollution Gadgets in JavaScript Runtimes"][publication].
GHunter is a pipeline to systematically detect gadgets in V8-based JavaScript runtimes with prime focus on Node.js and Deno.
It supports a lightweight dynamic taint analysis to automatically identify gadget candidates which we validate manually to derive proof-of-concept exploits.

The project consists of three sub artifacts for the different experiments presented in the paper.
For more details we recommend reading the per-artifact instructions found in each projects' `README.md` file.

- `ghunter4deno`: The artifact for the analysis on the Deno runtime.
- `ghunter4node`: The artifact for the analysis on the Node.js runtime as well as the GHunter part of the comparison between GHunter and Silent Spring.
- `silentspring4ghunter`: The Silent Spring part of the comparison between GHunter and Silent Spring.

## Citation

If you use the paper, tool, and/or experiment results for academic research we encourage you to cite it as:

```bibtex
@inproceedings{GHunter2024,
  title={GHunter: Universal Prototype Pollution Gadgets in JavaScript Runtimes},
  author={Cornelissen, Eric and Shcherbakov, Mikhail and Balliu, Musard},
  booktitle={33rd USENIX Security Symposium (USENIX Security 24)},
  pages={3693--3710},
  year={2024}
}
```

[publication]: https://www.usenix.org/conference/usenixsecurity24/presentation/cornelissen
