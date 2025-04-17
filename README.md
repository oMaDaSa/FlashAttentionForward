# Simplified FlashAttention with Triton

Simplified implementation of **FlashAttention** using **Triton**, focused only on the **forward pass**. For personal study, to understand the functionality of scaled dot-product attention in parallel.

---

## About

The implementation computes attention in blocks to improve GPU performance, using **Triton**.

---

## How to Use

1. Install the dependencies:

   ```bash
   pip install torch triton
   ```

2. Run the notebook or Python script.

   The code compares the output with PyTorch's official attention function to check accuracy.

---

## Expected Outcome

At the end, the test will show if the output of the custom implementation is close to PyTorch's output:

```bash
Test passed
```
