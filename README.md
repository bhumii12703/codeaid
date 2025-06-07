CodeAid: AI Code Language Predictor
CodeAid is an AI-powered tool that identifies the programming language of a given code snippet. Using deep learning models trained on large-scale datasets like CodeNet and CodeSearchNet, CodeAid provides accurate, fast, and scalable language classification for source code.

🚀 Features
Predicts code language from snippets with high accuracy
Supports 10 languages: Python, Java, C++, C#, JavaScript, PHP, Ruby, C, Rust, Haskell
Based on CNN & Sequential models with tokenization and dropout
Trained on 2M+ code samples using Project CodeNet

🧠 Model Architecture
Input Layer: Functional input, 64,512 token length
Dense Layers: Feature compression to 128 dimensions
Dropout: Prevents overfitting
Output Layer: 10-class softmax for language prediction.

📦 Dataset
Source: CodeSearchNet, Project CodeNet
Size: 2M+ snippets
Languages: Python, Java, JS, C++, C#, Ruby, PHP, etc.
Split: 80% Train, 10% Validation, 10% Test

⚙️ Preprocessing
Tokenization: Byte Pair Encoding
Normalization: Removed comments, whitespace
Padding: Fixed sequence length
Augmentation: Variable renaming, comment edits

🛠 Training Setup
Optimizer: Adam
Epochs: 30
Batch Size: 64
Loss: Categorical Cross-Entropy.

** Future Scope**
Expand language support
Deploy as web/IDE plugin
Improve accuracy with transformer-based models
