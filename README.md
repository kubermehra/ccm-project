# Extending the Rogers and McClelland (2003) Semantic Cognition Model

This repository contains extensions of the seminal Rogers and McClelland (2003) Semantic Cognition Model. The extensions aim to enhance the original model's ability to represent and process semantic knowledge using advanced neural network architectures.

## 1. Feed Forward Extension

This extension modifies the original Semantic Cognition Model by incorporating a feed-forward neural network architecture. The primary goals of this extension are:

- **Improved Semantic Representation:** The feed-forward design enhances the ability of the model to capture nuanced relationships within semantic data.
- **Scalability:** Allows the model to scale efficiently with larger datasets.
- **Faster Training:** Reduces computational complexity and training time compared to recurrent models.

### Key Features:
- Implementation of multi-layer perceptrons (MLPs) with activation functions suited for semantic cognition tasks.
- Customizable number of hidden layers and neurons per layer.
- Support for advanced optimization techniques (e.g., Adam, RMSProp).


## 2. RNN Model Extension

This extension adapts the Semantic Cognition Model into a recurrent neural network (RNN) framework. The RNN-based model captures temporal and sequential dependencies within semantic information, making it well-suited for dynamic semantic tasks.

### Key Features:
- Integration of standard RNN units as well as advanced variants such as LSTMs and GRUs.
- Capability to process sequential semantic data with varying time steps.
- Enhanced modeling of context-dependent semantics.




## Getting Started

To get started with these extensions, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/semantic-cognition-extensions.git
   ```

3. Navigate to the desired folder and follow the respective documentation for setup and execution.

---

## Repository Structure

```
semantic-cognition-extensions/
├── feedforward_extension/
│   ├── models/
│   ├── data/
│   └── docs/
├── rnn_extension/
│   ├── models/
│   ├── data/
│   └── docs/
├── tests/
├── requirements.txt
└── README.md
```

---

## Contributing

Contributions to this project are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a clear description of your changes.



## Acknowledgments

This project builds upon the foundational work of Rogers and McClelland (2003) and aims to extend its applicability to modern semantic cognition challenges.

