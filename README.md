![header](https://capsule-render.vercel.app/api?type=waving&color=FFA07A&height=300&section=header&text=Team%20Kukudas%20🐱&fontSize=90&animation=fadeIn&fontAlignY=38&desc=Kakao%20CloudSchool%20Engineer%20Class%201st%20term&fontColor=FFFFFF&descAlignY=50&descAlign=53)

# Groupware system for educational institutions <br>(Provision AWS resources with Terraform)

## Demo video 
https://www.youtube.com/watch?v=dLmNjxRBg_U

<br>

## Description

> 2022.11.01 - 2021.12.13

<br>

## Contests

📌 Final project of the 1st cohort of Kakao cloud school engineering training program (2022)

<br>

## Architecture
![Arch](https://user-images.githubusercontent.com/70618223/207789487-49b7f678-1064-4b89-adfb-6ba2e8f875b5.png)


<br>

## Implementation Plan

### Infrastructure Setup
  - Built AWS-based cloud infrastructure using Terraform (EKS, Load Balancer, VPC, high-availability deployment)
  - Deployed nodes across multiple zones for disaster recovery (DR) and configured auto scaling
  
### Node Management
  - Created Docker images to deploy Moodle and monitoring systems for each institution
   (Moodle: an open-source learning platform that supports and manages online education)
  - Managed pod deployment and nodes using Ansible
  
### Service Delivery
  - Provided monitoring dashboards for each institution (using Prometheus and Grafana)
  - Built a main website (Django) to collect institution names and SLAs, and stored them in RDS
  - Implemented HPA to satisfy the defined SLAs

<br>

## Expected effect

1) Ensures high availability and zero-downtime service through redundant cloud infrastructure
2) Reduces operational costs by scaling pods and worker nodes based on traffic
3) Shortens deployment time by distributing educational groupware via pods
4) Establishes a foundation for building groupware systems applicable not only to education but also to enterprises
