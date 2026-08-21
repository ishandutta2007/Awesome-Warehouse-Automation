# Awesome-Warehouse-Automation

Markdown
## Top Warehouse Automation Ecosystem


**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Warehouse Robotics, AMRs, AGVs, AS/RS, Goods-to-Person, Robotic Picking, Fleet Management & Warehouse Execution*  
**Last updated: August 2026**


This repository tracks notable **SaaS/Hosted Platforms** and **open-source projects** for **Warehouse Automation**. These technologies automate warehouse storage, retrieval, picking, sorting, replenishment, pallet handling, inventory movement, order fulfillment, and material transport using autonomous mobile robots (AMRs), automated guided vehicles (AGVs), robotic arms, automated storage and retrieval systems (AS/RS), conveyors, sortation systems, and warehouse-control software.


**Examples** include Locus Robotics, 6 River Systems, GreyOrange, Fetch Robotics, AutoStore, Exotec, Geek+, Swisslog, Dematic, and Körber.


**Open-source emphasis**: This repository is heavily expanded with open-source projects covering **robot operating systems, fleet management, autonomous navigation, SLAM, multi-robot coordination, task allocation, warehouse simulation, path planning, computer vision, robotic manipulation, digital twins, industrial IoT, warehouse management, and optimization**.


Unlike the commercial market, there are relatively few complete open-source equivalents to platforms such as Locus, AutoStore, Exotec, or Dematic. The open-source ecosystem is instead strongest at the **software infrastructure and robotics-component layer**, allowing developers to assemble custom warehouse-automation systems from interoperable components.


Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or GitHub repositories.


## Table of Contents


- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Additional Strong Open-Source Options](#additional-strong-open-source-options)
- [Open-Source Warehouse Automation Stack](#open-source-warehouse-automation-stack)
- [Warehouse Automation Building Blocks](#warehouse-automation-building-blocks)
- [Important Warehouse Automation Concepts](#important-warehouse-automation-concepts)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)


## SaaS/Hosted Platforms


- **[Locus Robotics](https://locusrobotics.com/)**  
  Autonomous mobile robot platform for warehouse fulfillment, picking, replenishment, and material movement. Provides robotic fleets and orchestration software for high-volume fulfillment environments.


- **[6 River Systems](https://www.6river.com/)**  
  Collaborative warehouse robotics platform centered around autonomous mobile robots and fulfillment workflows. 6 River Systems was acquired by Shopify.


- **[GreyOrange](https://www.greyorange.com/)**  
  AI-powered warehouse automation platform providing robotic fulfillment systems, warehouse orchestration, goods-to-person automation, and intelligent inventory movement.


- **[Fetch Robotics](https://fetchrobotics.com/)**  
  Autonomous mobile robotics platform focused on warehouse material transport, pallet movement, picking, and logistics automation. Fetch Robotics was acquired by Zebra Technologies.


- **[AutoStore](https://www.autostoresystem.com/)**  
  Cube-based automated storage and retrieval system using robots operating on a dense storage grid to retrieve bins and deliver them to workstations.


- **[Exotec](https://www.exotec.com/)**  
  Goods-to-person warehouse automation company known for its Skypod robotic storage and retrieval system using autonomous robots to move through storage racks.


- **[Geek+](https://www.geekplus.com/)**  
  Autonomous mobile robotics provider offering solutions for picking, sorting, moving, replenishment, and warehouse fulfillment.


- **[Swisslog](https://www.swisslog.com/)**  
  Warehouse automation provider offering automated storage and retrieval, robotic systems, conveyors, warehouse-control technologies, and software.


- **[Dematic](https://www.dematic.com/)**  
  Global warehouse automation provider covering automated material handling, storage, sortation, conveyors, robotics, and warehouse execution software.


- **[Körber Supply Chain](https://www.koerber-supplychain.com/)**  
  Supply-chain technology platform providing warehouse management, warehouse control, automation, robotics integration, and material-handling solutions.


### Additional Major Warehouse Automation Platforms
Recommended Open-Source Combinations

Basic AMR Warehouse

ROS 2 + Nav2 + SLAM Toolbox + Gazebo

Useful for building autonomous mobile robots capable of mapping and navigating warehouse environments.

Multi-Robot Warehouse

ROS 2 + Nav2 + Open-RMF + Free Fleet + Gazebo

Useful for coordinating multiple AMRs and managing traffic and tasks. Open-RMF is specifically designed for heterogeneous robot fleets and shared infrastructure.

Warehouse Task Optimization

Open-RMF + OR-Tools + PostgreSQL + Redis

Useful for combining robot fleet management with task allocation, routing, scheduling, and state management.

Robotic Picking

ROS 2 + MoveIt 2 + OpenCV + Open3D + GraspNet

Useful for building robotic picking and manipulation systems.

AI Warehouse Perception

ROS 2 + YOLO + OpenCV + Open3D + Segment Anything

Useful for detecting pallets, packages, humans, shelves, robots, and other warehouse objects.

Warehouse Digital Twin

ROS 2 + Gazebo + OpenUSD + Open-RMF

Useful for simulating warehouse layouts, robot fleets, traffic, and task execution before deployment.

Full Open-Source Warehouse Automation Stack

ERPNext/Odoo + Open-RMF + ROS 2 + Nav2 + MoveIt 2 + OpenCV/Open3D + OR-Tools + Gazebo + MQTT/OPC UA

This combination can provide inventory management, order management, task allocation, fleet management, autonomous navigation, robotic manipulation, computer vision, optimization, simulation, and industrial-equipment integration.

Warehouse Automation Building Blocks
Warehouse Robotics

Autonomous Mobile Robots (AMRs)

Automated Guided Vehicles (AGVs)

Autonomous Forklifts

Pallet-Moving Robots

Tugger Robots

Shelf-Moving Robots

Goods-to-Person Robots

Piece-Picking Robots

Robotic Arms

Mobile Manipulators

Palletizing Robots

Depalletizing Robots

Sorting Robots

Inventory Robots

Warehouse Drones

Storage Automation

Automated Storage and Retrieval Systems

AS/RS

Mini-Load AS/RS

Unit-Load AS/RS

Shuttle Systems

Cube Storage

Robotic Storage

Vertical Lift Modules

Horizontal Carousels

Vertical Carousels

Pallet Storage Automation

Bin Storage Automation

Goods-to-Person

Person-to-Goods

Dynamic Storage

Warehouse Execution

Warehouse Execution System

WES

Warehouse Control System

WCS

Warehouse Management System

WMS

Order Management

Task Management

Task Allocation

Order Batching

Wave Planning

Waveless Fulfillment

Workload Balancing

Dynamic Dispatch

Robot Scheduling

Resource Allocation

Exception Management

Fleet Management

Robot Fleet Management

Multi-Robot Coordination

Fleet Orchestration

Fleet Dispatch

Traffic Management

Traffic Negotiation

Collision Avoidance

Deadlock Avoidance

Path Planning

Dynamic Replanning

Task Allocation

Robot Assignment

Battery Management

Charging Optimization

Robot Health Monitoring

Robot Telemetry

Robot Localization

Navigation

SLAM

2D SLAM

3D SLAM

Visual SLAM

LiDAR SLAM

Localization

Path Planning

Motion Planning

Obstacle Avoidance

Dynamic Obstacle Avoidance

Costmaps

Waypoint Navigation

Autonomous Navigation

Behavior Trees

Recovery Behaviors

Map Management

Robotic Picking

Robotic Picking

Piece Picking

Bin Picking

Random Bin Picking

Depalletizing

Palletizing

Grasp Detection

Grasp Planning

6-DoF Grasping

Visual Servoing

Force Control

Motion Planning

Collision Avoidance

End-Effector Control

Vacuum Gripping

Parallel Grippers

Soft Robotics

Computer Vision

Object Detection

Object Tracking

Instance Segmentation

Semantic Segmentation

3D Perception

Depth Estimation

Point Clouds

RGB-D Perception

Package Detection

Pallet Detection

Barcode Detection

QR Detection

OCR

Pose Estimation

Visual Localization

Visual Inspection

Optimization

Task Allocation

Vehicle Routing

Multi-Robot Routing

Robot Scheduling

Order Batching

Pick-Path Optimization

Warehouse Slotting

Inventory Optimization

Resource Allocation

Constraint Programming

Mixed-Integer Optimization

Operations Research

Graph Optimization

Multi-Agent Path Finding

Conflict-Based Search

Hungarian Algorithm

A*

Dijkstra

D* Lite

RRT

RRT*

Model Predictive Control

Warehouse Infrastructure

Conveyors

Sorters

Automated Sortation

Pallet Conveyors

Roller Conveyors

Belt Conveyors

Pick Stations

Packing Stations

Robotic Workcells

Dock Automation

Loading Automation

Unloading Automation

Vertical Conveyors

Lifts

Automated Doors

Automated Gates

Industrial Integration

PLC

OPC UA

Modbus

MQTT

Ethernet/IP

PROFINET

Industrial IoT

Edge Computing

Robot APIs

Sensor Integration

Barcode Scanners

RFID

Cameras

LiDAR

IMU

Encoders

Warehouse Intelligence

Inventory Tracking

Real-Time Inventory

Robot Analytics

Fleet Analytics

Warehouse Analytics

Throughput Optimization

Order Cycle Time

Pick Rate

Robot Utilization

Travel Distance

Battery Utilization

Congestion Analytics

Bottleneck Detection

Predictive Maintenance

Equipment Monitoring

Digital Twins

Simulation

Warehouse Simulation

Robot Simulation

Multi-Robot Simulation

Digital Twins

Synthetic Data

Physics Simulation

Discrete Event Simulation

Layout Optimization

Throughput Simulation

Traffic Simulation

Robot Fleet Simulation

Pick Simulation

What-If Analysis

AI & Machine Learning

Robot Learning

Imitation Learning

Reinforcement Learning

Deep Reinforcement Learning

Vision-Language Models

Vision-Language-Action Models

Foundation Models for Robotics

Computer Vision

Object Detection

Grasp Learning

Learned Navigation

Predictive Maintenance

Demand Forecasting

ETA Prediction

Anomaly Detection

Warehouse Optimization

Communications

ROS 2 DDS

Zenoh

MQTT

Kafka

WebSockets

gRPC

REST APIs

OPC UA

Industrial Ethernet

5G Robotics

Wi-Fi Robotics

Edge-to-Cloud Robotics

Open-Source Warehouse Automation

Open-Source AMR

Open-Source AGV

Open-Source Fleet Management

Open-Source Warehouse Robotics

Open-Source WMS

Open-Source WES

Open-Source WCS

Open-Source Robot Navigation

Open-Source SLAM

Open-Source Robot Simulation

Open-Source Robotic Picking

Open-Source Warehouse Vision

Open-Source Multi-Robot Coordination

Open-Source Task Allocation

Open-Source Digital Twins

Self-Hosted Warehouse Automation

Self-Hosted Robot Fleet Management

Self-Hosted WMS

Self-Hosted AMR Infrastructure

Important Warehouse Automation Concepts

Warehouse Automation

Intralogistics

Autonomous Mobile Robots

AMR

Automated Guided Vehicles

AGV

Goods-to-Person

Person-to-Goods

Automated Storage and Retrieval

AS/RS

Warehouse Execution System

WES

Warehouse Control System

WCS

Warehouse Management System

WMS

Robot Fleet Management

Fleet Orchestration

Multi-Robot Coordination

Multi-Agent Path Finding

MAPF

Traffic Management

Traffic Negotiation

Collision Avoidance

Deadlock Avoidance

Task Allocation

Robot Assignment

Dynamic Dispatch

Robot Scheduling

Order Batching

Pick-Path Optimization

Warehouse Slotting

Inventory Optimization

SLAM

LiDAR SLAM

Visual SLAM

Localization

Path Planning

Motion Planning

A*

Dijkstra

D* Lite

RRT

RRT*

Model Predictive Control

Behavior Trees

Nav2

ROS 2

Open-RMF

Free Fleet

MoveIt 2

Robotic Picking

Bin Picking

Random Bin Picking

Palletizing

Depalletizing

Grasp Planning

Grasp Detection

6-DoF Grasping

Visual Servoing

Computer Vision

Object Detection

Object Tracking

Instance Segmentation

3D Perception

Point Clouds

RGB-D

LiDAR

Depth Cameras

Barcode Recognition

OCR

RFID

Conveyors

Sortation

Automated Sortation

Pallet Handling

Shelf Handling

Robotic Workcells

Pick Stations

Packing Automation

Dock Automation

PLC

OPC UA

MQTT

Modbus

Industrial IoT

Edge Robotics

Robot Telemetry

Predictive Maintenance

Robot Health Monitoring

Battery Management

Charging Optimization

Warehouse Digital Twin

Robot Simulation

Warehouse Simulation

Synthetic Data

Throughput Optimization

Warehouse Analytics

Robot Utilization

Congestion Analytics

Bottleneck Detection

Demand Forecasting

Reinforcement Learning

Imitation Learning

Robot Learning

Vision-Language Models

Vision-Language-Action Models

Foundation Models for Robotics

Open-Source Warehouse Robotics

Open-Source AMR

Open-Source Fleet Management

Open-Source Warehouse Management

Open-Source Robotic Picking

Open-Source Warehouse Simulation

Self-Hosted Warehouse Automation

How to Contribute

Fork the repo.

Add/edit entries in README.md (follow existing format).

Include: name, official link or GitHub repository, 1–2 sentence description, and whether it is SaaS/Hosted or open-source.

For open-source projects, identify the primary capability — fleet management, navigation, SLAM, manipulation, computer vision, simulation, WMS, optimization, industrial integration, or robotics middleware.

Clearly distinguish open-source, source-available, open-core, managed SaaS, and proprietary products.

Verify the current license before adding an open-source entry.

Prefer actively maintained repositories with meaningful documentation and recent development.

Do not describe a generic robotics library as a complete Locus/Exotec/AutoStore/Dematic alternative unless it actually provides the required warehouse functionality.

For infrastructure projects, prioritize functionality such as fleet management, task allocation, autonomous navigation, robotic picking, warehouse execution, warehouse simulation, and industrial integration.

Submit a PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

The commercial warehouse-automation market changes rapidly, particularly around AMRs, robotic picking, goods-to-person systems, AS/RS, AI-based perception, and warehouse orchestration.

The open-source ecosystem is substantially more fragmented than the commercial warehouse-automation ecosystem.

Some projects listed here are complete applications, while others are robotics middleware, navigation frameworks, fleet-management components, simulation environments, computer-vision libraries, optimization libraries, WMS platforms, or industrial-integration components.

Open-RMF, Nav2, ROS 2, MoveIt 2, Gazebo, OR-Tools, and OpenCV are important building blocks but are not one-for-one replacements for complete commercial warehouse-automation systems.

A production warehouse-automation deployment normally requires multiple layers: WMS/WES/WCS, fleet management, robot hardware, navigation, perception, task allocation, warehouse infrastructure, safety systems, industrial controls, networking, monitoring, and integration.

Warehouse robots operate in safety-critical environments. Production deployments require appropriate functional-safety engineering, risk assessment, emergency-stop systems, certified hardware, cybersecurity, and compliance with applicable local regulations and standards.

Always verify the current license, maintenance status, documentation, security posture, supported deployment model, hardware compatibility, and commercial-use restrictions before adopting an open-source project.

Robot hardware, firmware, simulation environments, models, datasets, and software can have different licenses. Verify each component independently.

Commercial platform features, integrations, pricing, AI capabilities, hardware models, and deployment options can change over time. Verify current capabilities with the vendor before making procurement decisions.

Made for warehouse operators, fulfillment centers, 3PLs, logistics companies, robotics engineers, warehouse-automation architects, supply-chain technologists, and open-source developers.
Let's make warehouse automation more open, intelligent, autonomous, interoperable, composable, and efficient.
