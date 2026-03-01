# 🚀 Ultimate GPU ZIP Cracker

> Powered by RTX ⚡ + PyTorch CUDA\
> High-performance ZIP password brute-force tool with CPU, GPU, and
> Hybrid modes.

> You can check by creating a zip file with a password

------------------------------------------------------------------------

## 🔥 Features

-   🎯 GPU Acceleration (CUDA via PyTorch)
-   💻 CPU Brute-Force Mode
-   🔄 Hybrid Mode (GPU + Multi-threaded CPU)
-   📊 Real-time speed & progress monitoring
-   📁 Native Windows file picker
-   🔐 AES ZIP support (via pyzipper)
-   ⚡ VRAM monitoring
-   📈 Estimated cracking time calculation
-   🎨 Clean terminal UI with detailed stats

------------------------------------------------------------------------

## 🖥️ System Requirements

### Minimum

-   Python 3.9+
-   8GB RAM
-   Windows / Linux

### Recommended (For GPU Mode)

-   NVIDIA RTX GPU
-   CUDA-compatible drivers
-   PyTorch with CUDA support

------------------------------------------------------------------------

## 📦 Installation

### 1️⃣ Clone the Repository

``` bash
git clone https://github.com/Pabasaralakmal2/Zip-Password-Cracker.git
cd Zip-Password-Cracker
```

### 2️⃣ Install Dependencies 

``` bash
pip install torch pyzipper numpy

```

install only If using GPU acceleration, install PyTorch with CUDA support from:

👉 https://pytorch.org/get-started/locally/

------------------------------------------------------------------------

## ▶️ Usage

Run the script:

``` bash
python main.py
```

### Workflow:

1.  Select ZIP file (Explorer or manual path)
2.  Enter password length
3.  Select character set
4.  Choose attack method:
    -   1️⃣ CPU Only
    -   2️⃣ GPU Only (Fastest)
    -   3️⃣ Hybrid (GPU + Threads)

------------------------------------------------------------------------

## ⚙️ Attack Modes Explained

### 💻 CPU Mode

-   Most compatible
-   Works on any system
-   Slower but reliable

### 🎯 GPU Mode

-   Uses CUDA via PyTorch
-   Massive parallel password generation
-   Best performance on RTX GPUs

### 🔄 Hybrid Mode

-   GPU generates password batches
-   CPU threads test passwords in parallel
-   Balanced performance

------------------------------------------------------------------------

## 📊 Performance Estimates

Speed depends on:

-   GPU model
-   CPU cores
-   Password length
-   Character set size

Example:

  Mode     Speed (Approx)
  -------- --------------------
  CPU      \~8,000 pwd/sec
  GPU      \~150,000 pwd/sec
  Hybrid   Depends on threads

------------------------------------------------------------------------

## 🔐 Supported ZIP Types

-   AES encrypted ZIP files
-   Standard encrypted ZIP files

Powered by: - pyzipper

------------------------------------------------------------------------

## 📂 Project Structure

    ultimate-gpu-zip-cracker/
    │
    ├── main.py
    ├── README.md
    └── requirements.txt

------------------------------------------------------------------------

## 🧠 How It Works

### GPU Password Generation

-   Converts characters into tensor format
-   Uses base-N index conversion
-   Generates large batches in parallel
-   Sends passwords to CPU for validation

### CPU Testing

-   Attempts decryption using pyzipper
-   Reports success instantly
-   Displays live speed tracking

------------------------------------------------------------------------

## ⚠️ Important Disclaimer

This tool is created for:

-   Educational purposes
-   Cybersecurity research
-   Recovering your own lost passwords

❗ Do NOT use this tool on files you do not own or do not have
permission to access.

The developer is not responsible for misuse.

------------------------------------------------------------------------

## 🛠️ Future Improvements

-   Dictionary attack mode
-   Mask attack support
-   Distributed cracking over network
-   Web dashboard interface
-   Real GPU hash acceleration (advanced cryptographic kernel)

------------------------------------------------------------------------

## 👨‍💻 Author



>  **Pabasara Lakmal** 🚀

------------------------------------------------------------------------

## ⭐ Support

If you like this project:

-   ⭐ Star the repository
-   🍴 Fork it
-   🛠️ Contribute improvements

------------------------------------------------------------------------

## 📜 License

MIT License

------------------------------------------------------------------------

## 🎉 Final Words

> Speed meets power.\
> RTX meets brute force.\
> Built with passion for performance. ⚡
