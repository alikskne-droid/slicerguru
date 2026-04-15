

![Slicer Guru Logo](logo.png)




Bazuko v2 - ML G-Code Optimization

"The next generation of 3D printing optimization. Using data-driven models to push the limits of speed and precision in G-code execution."
🚀 Overview

Bazuko v2 is a high-performance G-code post-processor that leverages Machine Learning to redefine the boundaries of FDM 3D printing. Unlike traditional rule-based optimizers, Bazuko analyzes geometric patterns and extrusion dynamics to provide a smarter, faster, and more reliable printing experience.
✨ Key Features

    Intelligent Path Analysis: ML models identify optimal speeds for complex geometries.

    Vibration Mitigation: Predicts and prevents ringing/ghosting by adjusting acceleration profiles dynamically.

    Flow Rate Optimization: Ensures perfect extrusion consistency across varying speeds.

    Time Efficiency: Reduces print time by up to 20% without sacrificing surface quality.

    Hardware Optimized: Built to run efficiently on modern GPUs (optimized for NVIDIA RTX series).

🛠 Tech Stack

    Language: Python 3.10+

    ML Frameworks: Scikit-learn / XGBoost (for high-speed tabular data processing)

    Data Processing: NumPy, Pandas

    Compatibility: Optimized for Bambu Studio and Orca Slicer outputs.

📊 How It Works

    Parsing: Ingests standard G-code files.

    Feature Extraction: Extracts spatial coordinates, E-steps, and velocity vectors.

    Inference: The trained ML model predicts the ideal parameters for each segment.

    Generation: Outputs an optimized G-code ready for high-speed machines like Bambu Lab A1.
