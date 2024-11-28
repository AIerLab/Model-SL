# Model-SL Project: Adaptive Split Learning with Localized Encryption and Decryption Models

**Model-SL** is an innovative project that implements **Split Learning** with **adaptive encryption and decryption models**. These models are parameterized and run locally on user devices, leveraging **user history data** to train and fine-tune their parameters, enabling personalized and robust encryption-decryption mechanisms. This ensures data security and privacy while enhancing collaborative learning capabilities.

**⚠️ Note: This project is under active construction. Expect frequent updates and experimental features.**

---

## Features

- **Localized Encryption and Decryption Models**: Each user has locally parameterized encryption and decryption models, ensuring data never leaves their device unencrypted.
- **User History-Driven Training**: User history data is securely used to train and adapt the encryption and decryption models for personalized performance.
- **Split Learning**: The neural network is partitioned between the user and server, minimizing the exposure of sensitive data.
- **Privacy-Preserving Architecture**: The design ensures that raw user data remains secure and never directly shared with the server.
- **Modular Design**: Future-ready for adding new features and extending encryption mechanisms.

---

## Installation

To get started, clone the repository with submodules:

```bash
git clone --recurse-submodules https://github.com/AIerLab/model-sl.git
```

---

## Usage

### Cloud Execution

For deploying in a cloud environment:

```bash
bash run_cloud.sh
```

### Local Execution

For testing locally on your machine:

```bash
bash run_local.sh
```

---

## Current Workflow (Under Construction)

1. **Data Partitioning**:
   - User data is retained locally, and only encrypted representations are shared with the server.
   
2. **Training Local Models**:
   - **Encryption Model**: Trains on user history to generate secure representations of intermediate outputs.
   - **Decryption Model**: Trains in tandem to decode the encrypted data on the server side.

3. **Split Learning Integration**:
   - The encrypted intermediate data is transmitted to the server for further processing, while local models adapt based on user-specific requirements.

4. **Continuous Learning**:
   - User models evolve by leveraging historical data, enhancing encryption robustness over time.

---

## Folder Structure

- **`/model-sl/`**: Main repository containing the split learning implementation.
- **`/submodules/`**: Includes experimental modules for encryption and decryption.
- **`/user-history/`**: Placeholder for user history data (ensure compliance with privacy standards).
- **`run_cloud.sh`**: Script for cloud execution.
- **`run_local.sh`**: Script for local execution.

---

## Development Status

### Current Focus
- Implementing basic encryption and decryption models.
- Establishing secure communication protocols.
- Testing integration of user-specific data with model parameterization.

### Future Goals
- Fine-tuning encryption-decryption models using federated learning techniques.
- Enhancing performance through model optimization and hyperparameter tuning.
- Expanding support for additional use cases and datasets.

---

## Contribution

As the project is still in its early stages, contributions are welcome! 

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push the branch: `git push origin feature-name`.
5. Open a pull request on GitHub.

---

## License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

---

## Support and Feedback

For questions, feature requests, or bug reports, please reach out via [GitHub Issues](https://github.com/AIerLab/model-sl/issues) or email us at **support@aierlab.com**.

---

**Stay tuned as we build the future of adaptive, secure split learning!**
