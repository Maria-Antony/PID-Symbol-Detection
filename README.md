# PID Symbol Detection using YOLOv11s

### 📌 Project Overview
This repository contains an object detection project focused on Piping and Instrumentation Diagram (P&ID) symbol detection using the YOLOv11s model. The goal is to automatically identify and classify engineering symbols in P&ID diagrams, enabling faster digitalization, verification, and downstream integration for industrial automation and process engineering.

### 📊 Dataset

Size: ~12,000 images
Splits: Train / Validation / Test
Dataset was filtered and preprocessed to improve quality.
Each image contains multiple P&ID symbols annotated for detection.

### 🛠️ Methodology

Data Analysis: Inspected dataset distribution and symbol class representation.
Training: Used YOLOv11s for object detection. Initial training shows promising results but requires further fine-tuning for higher accuracy.
Evaluation: Currently evaluating model performance on test splits.

### 🚀 Results (Work in Progress)
Initial training demonstrates reasonable detection performance.
Accuracy can be improved with additional epochs, hyperparameter tuning, and possibly augmentation strategies.

### 🔮 Future Directions
This project is being extended into a P&ID LLM Helper, guided by another research paper. The idea is to:
Combine object detection results with LLM-based reasoning to automatically interpret entire diagrams.
Enable text-based querying of diagrams (e.g., "Which valves are connected to Pump P-101?").
Develop an AI assistant that bridges P&ID diagrams and natural language understanding for industrial applications.

### 📚 References
[[YoLov5 for symbol extraction in PID Diagrams](https://www.researchgate.net/publication/366123842_YOLOv5_for_symbol_extraction_in_PID_diagrams)]
[Paliwal et al., 2021] Paliwal, S., Jain, A., Sharma, M., and Vig, L. (2021). Digitize-PID: Automatic digitization of piping and instrumentation diagrams. In Lecture Notes in Computer Science, pages168–180. Springer International Publishing

### 🙏 Acknowledgments
🔗 Special thanks to [ch-hristov] for providing the dataset and releasing the associated paper that inspired this work. 
Community contributors and open-source maintainers of YOLOv11.
