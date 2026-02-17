# Robotics-Control-Lab-4.1
# 🦾 SO101 Robot Arm: PID Tuning & Cross-Simulator Validation
> *Engineering Investigation: MuJoCo to Gazebo Transferability*

[![Project Status: Active](https://img.shields.io/badge/Status-Active-success.svg)](#)
[![Simulator: MuJoCo](https://img.shields.io/badge/Physics-MuJoCo-blue.svg)](https://mujoco.org/)
[![Env: uv](https://img.shields.io/badge/Environment-uv-purple.svg)](https://astral.sh/uv)

## 🎯 Purpose
Esta actividad transforma la sintonización de controladores en una investigación técnica profunda. El objetivo es comandar el brazo *SO101* en *MuJoCo, analizar cómo las acciones proporcionales, derivativas e integrales moldean la dinámica del sistema bajo perturbaciones, y validar la fidelidad de la transferencia de control hacia **Gazebo*.

## 🛠️ System Architecture & Files
El repositorio está organizado para garantizar la reproducibilidad y el rigor académico:
* run_mujoco_simulation.py: Script principal para ejecutar la trayectoria de prueba.
* so101_mujoco_pid_utils.py: Implementación central del controlador PID y gestión de ganancias.
* so101_ros_bridge.py: Interfaz para la validación cruzada y comunicación con sistemas externos.
* pyproject.toml & uv.lock: Configuración del entorno de desarrollo mediante el gestor uv.

## 🚀 Installation & Environment
Este proyecto utiliza *uv* para una gestión de dependencias ultra-rápida y determinista.

1. *Sincronizar el entorno:*
   ```bash
   uv sync
