# Week 1 Overview

## Description

Tools needed to learn in this week:
- Docker
- PostgreSQL
- Terraform

## Steps that should be done (in order):

1. PostgreSQL CMD line for Docker
2. pgcli (PostgreSQL CLI)
3. Run Jupyter Notebook
4. Download NY Taxi data
5. read_csv from pandas
6. Install SQLAlchemy and connect to PostgreSQL
7. Generate PostgreSQL-compatible DDL
8. While-loop to ingest CSV in chunks

## [1.2.1 What is Docker?](https://www.youtube.com/watch?v=EYNwNlOrpr0&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)

**Docker** is a tool that allows developers to package applications and their dependencies into lightweight, portable containers. These containers can run consistently across different environments, such as development, testing, and production.

### Advantages of Docker:
1. **Consistency Across Environments**: Containers ensure that an application runs the same way, regardless of where it's deployed.
2. **Lightweight**: Containers share the host operating system, making them faster and less resource-intensive compared to virtual machines.
3. **Portability**: Docker containers can run on any system that supports Docker, including cloud services and local machines.
4. **Efficiency**: Multiple containers can run on the same machine, making better use of system resources.
5. **Simplified Deployment**: Containers bundle everything the app needs, simplifying deployment and scaling.
6. **Version Control**: Docker images are versioned, enabling easy rollback and better tracking of changes.
7. **Isolation**: Each container runs in its own environment, preventing conflicts between applications.