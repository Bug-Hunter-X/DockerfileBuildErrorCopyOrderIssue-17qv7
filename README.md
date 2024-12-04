# Dockerfile Build Error: Incorrect COPY Order

This repository demonstrates a common error in Dockerfiles: incorrect ordering of `COPY` instructions. The original Dockerfile fails to build because the `requirements.txt` file is copied before the `app.py` file.  The fixed version correctly orders the instructions to ensure a successful build.