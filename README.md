# lab3-part1-Software-Quality

Docker - Docker is a platform that allows developers to build, ship, and run applications in lightweight, portable containers. These containers package everything needed to run the app — code, runtime, libraries, and dependencies, ensuring it works the same in development, testing, and production.

Docker Terminologies

- Image - A read-only template with instructions to create a container. It includes the application code, runtime, libraries, and environment configurations.
- Container - A running instance of a Docker image. It’s isolated, lightweight, and runs your application.
- Registry - A storage system for Docker images. Public examples include Docker Hub, where images can be pushed, pulled, and shared.

Advantages:
- Portability: Containers work the same across different environments (developer’s laptop, test server, cloud, etc.).
- Resource Efficiency: Containers are lightweight compared to virtual machines

Disadvantages
- Complex Networking: Networking between containers, hosts, and external systems can become complex, especially in larger deployments.

Kubernetes (K8s) is an open-source container orchestration platform that helps manage, scale, and automate the deployment of containerized applications across clusters of machines.

Kubernetes Terminologies
- Cluster: A set of nodes (machines) that run containerized applications managed by Kubernetes.
- Pod: The smallest deployable unit in Kubernetes. A pod can hold one or more containers that share networking and storage.
- Deployment: A Kubernetes object that defines how to deploy and manage a set of replicated pods. It handles rolling updates and scaling.
- Service: A Kubernetes object that exposes a set of pods to the network (either inside the cluster or externally). It provides a stable IP and DNS name, even if pods are replaced.
