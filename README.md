# maui-software-examples

Hello!

Welcome to the Maui Software Examples repository. Here, you will find a series of notebooks that showcase each feature of Maui, along with data analysis examples.  
If you have any questions, encounter any issues or bugs, or would like to request a new feature, please use the [original project's GitHub discussions](https://github.com/maui-software/maui-software/discussions)!

---

## Installing Dependencies and Running Notebooks

To run these notebooks locally, you will need to install **Maui** and **FFmpeg**. We strongly recommend using a virtual environment.  
Maui works on **Linux**, **Windows**, and **macOS**. Below are the steps to install and run the notebooks.  
We assume you already have **Python**, **pip**, and **Git** installed.

---

### Linux (Ubuntu / Debian)

In the terminal, follow the steps below:

#### 1. Install FFmpeg
```bash
sudo apt update

sudo apt install ffmpeg
```

Once installed, you can verify the installation with the following command. You should see the FFmpeg version and a list of supported codecs:

```bash
ffmpeg -version
```

#### 2. Clone this repository
```bash
git clone https://github.com/maui-software/maui-software-examples.git
```

#### 3. Create and activate the virtual environment
```bash
python -m venv venv
source venv/bin/activate
```

Once activated, your terminal should look like this:
```bash
(venv) usuario@maquina:~/maui-software-examples$
```

#### 4. Install Maui and Jupyter Lab
```bash
pip install --upgrade pip wheel
pip install maui-software
pip install jupyterlab
```

#### 5. Run the notebooks

That's it! Now just run JupyterLab and open the notebooks. Everything should work smoothly:

### Windows

![WIP](https://img.shields.io/badge/status-WIP-yellow)


### Mac Os

![WIP](https://img.shields.io/badge/status-WIP-yellow)