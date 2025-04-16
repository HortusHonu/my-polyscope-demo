Polyscope Demo Application

This repository contains a Polyscope demo application (demo-app) and associated data (bun000.ply) for rendering the Stanford bunny.

Prerequisites

CMake
C++ compiler (e.g., g++)
Install Polyscope dependencies (refer to https://polyscope.run/about/dependencies/)

Setup

Clone the repository:

git clone git@github.com:hortushonu/polyscope-demo-new.git
cd polyscope-demo-new

Build the demo application:

cd demo-app
mkdir build
cd build
cmake ..
make

Run the application:

./demo_app

The data/ directory contains bun000.ply, used by the demo application.

Notes





Ensure the data/bun000.ply file is accessible to the application at runtime.

For large .ply files, consider using Git LFS (not currently enabled).
