# MLOps-assignment-3 : End-to-End Pipeline
| Metric             | Original Sklearn Model | Quantized Model |
|--------------------|------------------------|-----------------|
| R² Score           | 0.6053                 | 0.6051          |
| Model Size (KB)    | 0.40 KB                | 0.32 KB         |

- **R² Score** remains almost the same → minimal impact on accuracy after quantization.
- **Model size** reduced by 20%, which is beneficial for deployment on edge devices or limited-resource environments.

