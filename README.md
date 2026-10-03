# The QRL Book

**Learn Quantum Computing and MBQC with the Quantum Relational Language**

📚 **Read online:** [dcoldeira.github.io/qrl-book](https://dcoldeira.github.io/qrl-book/)

## About

This book teaches quantum computing from first principles using QRL (Quantum Relational Language) - a relations-first approach to quantum programming that compiles directly to Measurement-Based Quantum Computing (MBQC).

## Contents

- **Part I: Quantum Foundations** - Qubits, entanglement, n-qubit systems
- **Part II: MBQC Theory** - Cluster states, graph states, measurement patterns
- **Part III: QRL Programming** - Hands-on tutorials with working code
- **Part IV: Advanced Topics** - Tensor networks, categorical QM, fault-tolerance

## Building Locally

### Prerequisites

- [Quarto](https://quarto.org/docs/get-started/) 1.4+

### Preview

```bash
quarto preview
```

### Build HTML

```bash
quarto render --to html
```

### Build PDF

```bash
# Install TinyTeX (one-time)
quarto install tinytex

# Render PDF
quarto render --to pdf
```

## Contributing

Contributions welcome! Please:

1. Fork this repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

Found a typo? [Open an issue](https://github.com/dcoldeira/qrl-book/issues)

## Related Projects

- [Quantum Relational Language](https://github.com/dcoldeira/quantum-relational-language) - The QRL implementation
- [David's Blog](https://dcoldeira.github.io) - Development journey and technical posts

## Author

**David Coldeira**
- Email: [david@entangledcode.dev](mailto:david@entangledcode.dev)
- Website: [entangledcode.dev](https://entangledcode.dev)
- GitHub: [@dcoldeira](https://github.com/dcoldeira)
- Blog: [dcoldeira.github.io](https://dcoldeira.github.io)

## License

- **Text**: [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
- **Code examples**: [MIT License](LICENSE)

You may read, share and adapt the text for non-commercial purposes, with attribution, under the same license. Commercial rights (including print and ebook editions) are reserved by the author. Versions published before this change remain available under CC BY-SA 4.0.
