# Sarang: Fall in Tune with Yourself
Sarang is an AI-powered system designed to provide zero-latency, hardware-level vocal monitoring using deep learning and high-performance C++ audio pipelines. Developed to bridge the gap between pure physics and musical artistry, it transforms a standard smartphone into a professional-grade vocal studio.

🎵 OverviewDigital music education has evolved, yet real-time feedback on mobile remains a significant bottleneck due to high latency in standard Android audio layers. Sarang addresses these issues by providing an ultra-low latency environment tailored for both Western and Indian Classical Music.Key Issues Addressed:Audio Lag: Standard apps suffer from latency that disrupts a singer's natural rhythm.Microtonal Accuracy: Most tools lack the precision required for Indian Classical microtones.Environmental Noise: Background static often pollutes pitch detection in standard tools.Hardware Optimization: Mobile hardware is rarely utilized for professional-grade DSP.

# 🚀 Key Features
Ultra-Low Latency: Optimized audio pipeline (under 50ms) using Google Oboe.AI Pitch Detection: Real-time vocal pitch identification via TensorFlow Lite/JAX neural networks.Continuous Pitch Canvas: Specialized visualization for Indian Classical microtones (Meend).Ensemble Noise Filter: Rejects non-vocal interference for clean signal processing.Mathematical Precision: Translates raw frequency (Hz) into Musical Notes and Cents.🛠️ Technology StackProgramming Languages: Dart, C++, Python.Frameworks & SDKs:Flutter: For cross-platform UI rendering.Google Oboe: For native, low-latency audio capture.TensorFlow Lite: For efficient on-device AI inference.Dart FFI: For zero-copy C++ interop.Development Tools: VS Code, Android Studio, and CMake.

# 🏗️ System Architecture
The system follows a high-performance pipeline to ensure data integrity and speed:Hardware Capture: Direct microphone access via C++ Oboe.Ring Buffer: Data management through a Lock-Free C++ memory pool.FFI Bridge: Zero-copy data transfer from C++ to the Flutter UI.DSP Gating: Volume-based pre-processing to filter background noise.AI Inference: Fundamental frequency detection via the TFLite model.Decision Engine: Biological frequency validation and music math translation.Final UI Rendering: Real-time visualization in Flutter.

# ✅ Results & Validation
Performance: Successfully achieved zero-latency monitoring on Samsung S-series hardware.Accuracy: Error rate maintained within $\pm$ 2 Cents of mathematical perfection.Reliability: Validated against physical instruments (guitar strings) and successfully filtered out notification/environmental interference.

# 🔮 Future Scope
Auto-Scale Recognition: Dynamically identifying musical keys.Live DSP Effects: Integration of professional Reverb, Compression, and EQ.Reference Overlay: Scoring vocals against original artist tracks for improved training.🎓 Project CreditsDeveloper: Devansh Bajaj Department: Department of Computer Science University: SRM University, Delhi-NCR, Sonepat Academic Year: 2025-26 
