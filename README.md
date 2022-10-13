# Allowing Safe Contact in Robotic Goal-Reaching

## Introduction
This repo includes code for the paper "Allowing Safe Contact in Robotic Goal-Reaching: Planning and Tracking in Operational and Null Spaces".

This repo provides Jupyter notebooks and configuration files to run the simulation experiments in the paper. Besides the ball and wall environments, we further provide a strawberry picking environment and a PyBullet robot simulator.

## Install
In the Conda env, install [Jax](https://github.com/google/jax#installation), [Brax](https://github.com/google/brax#using-brax-locally), and other libraries with the following command
- `pip install --upgrade "jax[cuda]" -f https://storage.googleapis.com/jax-releases/jax_cuda_releases.html` 
    - We highly recommend to use the CUDA version, results in the paper are computed with CUDA support
    - Please check the installation [manual](https://github.com/google/jax#installation) for details
- `pip install brax pybullet notebook tqdm scipy`

## Usage
- Use `Brax_ball.ipynb` to play with the ball environment
- Use `Brax_wall.ipynb` to play with the wall environment
- Use `Brax_strawberry.ipynb` to pick strawberries :)
- Use `PyBullet_Kuka.ipynb` to see the compliance controller in PyBullet
