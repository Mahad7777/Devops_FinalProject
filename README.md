# DevOps Final Project

This project demonstrates a full-stack application with a DevOps pipeline using technologies like Terraform, Ansible, Docker, and Nginx.

## Technologies Used

- **Terraform**: Infrastructure as Code (IaC) for provisioning resources.
- **Ansible**: Configuration management and deployment automation.
- **Docker**: Containerization for application deployment.
- **Nginx**: Web server for routing.
- **React**: Frontend application using Create React App.

## How to Run

### Prerequisites

- Docker
- Ansible
- Terraform
- Node.js (for the frontend)

### Steps

1. **Provision Infrastructure** using Terraform:
   ```bash
   cd terraform
   terraform init
   terraform apply

2. **Configure the Servers** using Ansible::
   ```bash
    cd ansible
    ansible-playbook playbook.yml

3. **Run the Frontend**:
    ```bash
    cd src
    npm install
    npm start

4. **Build the Docker Containers**:
    ```bash
    docker-compose up --build


## Project Structure

- **terraform/**: Terraform scripts for provisioning.
- **ansible/**: Playbooks for configuration.
- **src/**: Frontend application built with React.
- **Dockerfile**: Defines the Docker container for the app.
- **nginx.conf**: Configuration for Nginx web server.
