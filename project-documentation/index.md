# Project Documentation

## Kompose - Convert your Docker Compose file to Kubernetes or OpenShift

<img src="markdown-content/profile-imagery/mateo-on-the-balcony-at-the-embassy.jpg" alt= “” width="225" height="225">

logo

    Installation
    Getting Started
    User Guide
    Conversion Matrix
    Architecture

An official Kubernetes project, located at github.com/kubernetes/kompose
Go from Docker Compose to Kubernetes
Kompose

Kompose is a conversion tool for Docker Compose to container orchestrators such as Kubernetes (or OpenShift).
Installation

$ kompose convert -f docker-compose.yaml

$ kubectl apply -f .

$ kubectl get po
NAME                            READY     STATUS              RESTARTS   AGE
frontend-591253677-5t038        1/1       Running             0          10s
redis-master-2410703502-9hshf   1/1       Running             0          10s
redis-replica-4049176185-hr1lr  1/1       Running             0          10s

Get started on Kubernetes immediately

So easy your human companion could do it too!

Why do cats (and developers) like Kompose?

Developers love to simplify their development environment with Docker Compose.

With Kompose, you can now push the same file to a production container orchestrator!
Getting Started
Built for container engineers

Our conversions are not always 1-1 from Docker Compose to Kubernetes, but we will help get you 99% of the way there!
The awesome features

• Compatibility with multiple versions of Docker Compose
• A conversion matrix that outlines all compatible values and versions
• An in-depth user guide to use advanced features such as LoadBalancer, Service and TLS
• Labels that provide the extra 1% needed to get to 1-1 conversion
User Guide
We are a Kubernetes incubator graduated project and officially part of the Kubernetes group
Apache License 2.0 licensed project
© 2023 Kompose Authors -- All Rights Reserved
Kompose

    SlackSlack GitHubGitHub 

