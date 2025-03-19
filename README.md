# 🔍 PiVision: Object and Animal Recognition with Raspberry Pi

## 📝 Description

PiVision is a sophisticated computer vision project that leverages the power of Raspberry Pi to identify and track objects and animals in real-time. Using the COCO dataset, this system can recognize 91 unique objects/animals while providing constantly updating confidence ratings for each detection.

## ✨ Features

- Real-time object and animal recognition
- Detection of 91 different object classes from the COCO dataset
- Live confidence rating updates
- Optimized for Raspberry Pi hardware
- Lightweight implementation for edge computing

## 🛠️ Technologies Used

<div align="center">
  <a href="https://opencv.org/"><img src="https://github.com/JonIbarreche/Proyecto-IOT/blob/main/img/OpenCV-Logo.png" width="100" alt="OpenCV" /></a>
  <a href="https://www.python.org/"><img src="https://github.com/JonIbarreche/Proyecto-IOT/blob/main/img/Python-logo.png" width="100" alt="Python" /></a>
  <a href="https://pypi.org/project/coco-lib/"><img src="https://github.com/JonIbarreche/Proyecto-IOT/blob/main/img/CocoLib-nologo.png" width="150" alt="COCO Library" /></a>
  <a href="https://es.wikipedia.org/wiki/Bash"><img src="https://github.com/JonIbarreche/Proyecto-IOT/blob/main/img/BashLogo.png" width="150" alt="Bash" /></a>
  <a href="https://www.tensorflow.org/"><img src="https://github.com/JonIbarreche/Proyecto-IOT/blob/main/img/tensorflow_logo_icon_170598.png" width="100" alt="TensorFlow" /></a>
</div>

## 📸 Project Gallery

<div align="center">
  <img src="https://github.com/JonIbarreche/Proyecto-IOT/blob/main/img/Project-IOT-1.jpg" width="400" alt="PiVision in action" />
  <img src="https://github.com/JonIbarreche/Proyecto-IOT/blob/main/img/Project-IOT-2.jpg" width="400" alt="PiVision setup" />
</div>

## 🚀 Installation

```bash
# Clona el repositorio
git clone https://github.com/JonIbarreche/PiVision.git

# Navega al directorio del proyecto
cd PiVision

# Instala virtualenv si no lo tienes
pip3 install virtualenv

# Crea un entorno virtual
python3 -m virtualenv env

# Activa el entorno virtual
source env/bin/activate

# Ahora instala las dependencias en el entorno virtual
pip install -r requirements.txt

# Configura la cámara de Raspberry Pi
sudo raspi-config
# Navega a "Interface Options" > "Camera" y habilita la cámara

# Asegúrate de que tu Raspberry Pi está actualizada
sudo apt-get update
sudo apt-get upgrade
```

## 💻 Usage

```bash
# Run the main recognition script
python main.py
```

## 🔧 Requirements

- Raspberry Pi (3 or newer recommended)
- Pi Camera or USB webcam
- Python 3.6+
- OpenCV
- TensorFlow Lite

## 👥 Contributors

- Jon Ibarreche <jon.ibarreche@opendeusto.es>
- Javier Fuente <javifuenn@opendeusto.es>
