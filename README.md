# Model-SL Project

**Model-SL** (Split Learning) is a research and development project focusing on implementing **Split Learning with Encryption** to enhance data security while leveraging **user history** for improved model performance. The project aims to address privacy concerns in collaborative machine learning by securely partitioning the learning process across multiple entities.

---

## Features

- **Split Learning**: Implements a partitioned neural network architecture where training is distributed between client and server without sharing raw data.
- **Encryption**: Adds robust encryption mechanisms to protect intermediate data exchanges.
- **User History Integration**: Leverages historical user data securely to improve model predictions and personalization.
- **Flexible Execution**: Supports both cloud-based and local execution.

---

## Installation

To get started, clone this repository along with its submodules:

```bash
git clone --recurse-submodules https://github.com/AIerLab/model-sl.git
```

---

## Usage

### Cloud Execution

For cloud-based execution, run:

```bash
bash run_cloud.sh
```

### Local Execution

For local execution, run:

```bash
bash run_local.sh
```

---

## Folder Structure

- **`/model-sl/`**: Main repository containing the core codebase for split learning.
- **`/submodules/`**: Includes necessary submodules for encryption, user history management, and utility scripts.
- **`run_cloud.sh`**: Script for deploying and running the project on a cloud environment.
- **`run_local.sh`**: Script for running the project locally.

---

## Prerequisites

- Python 3.8+
- Required libraries (install via `requirements.txt` if applicable)
- Access to cloud services (e.g., AWS, Azure, or GCP) for cloud execution
- Supported Linux environment for local execution

---

## Contributing

We welcome contributions to the **Model-SL Project**! To contribute:

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add a new feature'`.
4. Push the branch: `git push origin feature-name`.
5. Open a pull request on GitHub.

---

## License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

## Support

For issues and discussions, visit the [GitHub Issues](https://github.com/AIerLab/model-sl/issues) section or contact the team at **support@aierlab.com**.
