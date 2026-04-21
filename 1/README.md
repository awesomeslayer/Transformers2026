# Subtask 1: DimABSA Track A

This folder contains the implementation for the Dimensional Aspect-Based Sentiment Analysis task using a Unified Generative Approach (Flan-T5).

## How to Run

Follow these steps to reproduce the results:

1.  **Clone the project**:
    ```bash
    git clone https://github.com/ВашеИмя/Transformers2026.git
    cd Transformers2026/1
    ```

2.  **Build the Docker image**:
    ```bash
    ./build
    ```

3.  **Launch the container**:
    ```bash
    ./launch_container
    ```

4.  **Access Jupyter**:
    *   Copy the URL/token from the terminal output.
    *   Open it in your browser (usually `http://localhost:8881`).
    *   Open and run all cells in `DimABSA.ipynb`.

## Results
Predictions are saved in the `results/` folder as `.jsonl` files, ready for submission to CodaBench.