## How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/awesomeslayer/Transformers2026.git
   cd Transformers2026/1
   ```

2. **Build the Docker image**
   ```bash
   ./build
   ```

3. **Launch the container**
   ```bash
   ./launch_container
   ```

4. **Execute the notebook**
   Open `http://localhost:8881` in your browser. The launch script disables the token requirement. Open `DimABSA.ipynb`. Run all cells.

The code saves prediction `.jsonl` files to the `results/` directory for CodaBench submission.