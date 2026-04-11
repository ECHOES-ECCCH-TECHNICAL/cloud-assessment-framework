# Digital services

This page lists the evaluation dimensions and related entries for this resource family.

## Hierarchy diagram

```mermaid
flowchart LR
    service_dim_digital_service_evaluation["Digital Service Evaluation Dimensions"]
    service_dim_availability["Availability"]
    service_dim_digital_service_evaluation --> service_dim_availability
    service_dim_service_uptime["Service Uptime"]
    service_dim_availability --> service_dim_service_uptime
    service_dim_redundancy_and_failover["Redundancy and Failover Mechanisms"]
    service_dim_availability --> service_dim_redundancy_and_failover
    service_dim_incident_response_time["Incident Response Time"]
    service_dim_availability --> service_dim_incident_response_time
    service_dim_monitoring_and_alerting["Monitoring and Alerting"]
    service_dim_availability --> service_dim_monitoring_and_alerting
    service_dim_reliability["Reliability"]
    service_dim_digital_service_evaluation --> service_dim_reliability
    service_dim_fault_tolerance["Fault Tolerance"]
    service_dim_reliability --> service_dim_fault_tolerance
    service_dim_data_integrity["Data Integrity"]
    service_dim_reliability --> service_dim_data_integrity
    service_dim_backup_and_recovery["Backup and Recovery Procedures"]
    service_dim_reliability --> service_dim_backup_and_recovery
    service_dim_service_consistency["Service Consistency"]
    service_dim_reliability --> service_dim_service_consistency
    service_dim_performance["Performance"]
    service_dim_digital_service_evaluation --> service_dim_performance
    service_dim_response_time["Response Time"]
    service_dim_performance --> service_dim_response_time
    service_dim_throughput["Throughput"]
    service_dim_performance --> service_dim_throughput
    service_dim_resource_utilization_efficiency["Resource Utilization Efficiency"]
    service_dim_performance --> service_dim_resource_utilization_efficiency
    service_dim_scalability_under_load["Scalability Under Load"]
    service_dim_performance --> service_dim_scalability_under_load
    service_dim_security["Security"]
    service_dim_digital_service_evaluation --> service_dim_security
    service_dim_access_control["Access Control"]
    service_dim_security --> service_dim_access_control
    service_dim_data_protection["Data Protection"]
    service_dim_security --> service_dim_data_protection
    service_dim_vulnerability_management["Vulnerability Management"]
    service_dim_security --> service_dim_vulnerability_management
    service_dim_compliance_and_auditing["Compliance and Auditing"]
    service_dim_security --> service_dim_compliance_and_auditing
```

## Overview

- [**Digital Service Evaluation Dimensions**](#digital-service-evaluation-dimensions)
    - [**Availability**](#availability) — This dimension assesses the extent to which the digital services are continuously operational and accessible, minimizing downtime and ensuring users can reliably access CH resources at any time.
        - [**Service Uptime**](#service-uptime) — Measures the proportion of time that the services remain fully operational and accessible to users.
        - [**Redundancy and Failover Mechanisms**](#redundancy-and-failover-mechanisms) — Assesses the presence and effectiveness of backup systems, load balancing, and failover strategies that ensure service continuity in case of component failure.
        - [**Incident Response Time**](#incident-response-time) — Evaluates how quickly the infrastructure team can detect, respond to, and resolve outages or service interruptions.
        - [**Monitoring and Alerting**](#monitoring-and-alerting) — Examines the robustness of monitoring systems and real-time alert mechanisms that track service health and performance.
    - [**Reliability**](#reliability) — This dimension evaluates the infrastructure’s ability to deliver consistent and dependable service performance under expected and peak workloads, avoiding system failures and data loss.
        - [**Fault Tolerance**](#fault-tolerance) — Assesses the infrastructure’s capacity to continue operating correctly even when components fail or experience errors.
        - [**Data Integrity**](#data-integrity) — Evaluates mechanisms ensuring that data remains accurate, complete, and consistent during storage, processing, and transmission.
        - [**Backup and Recovery Procedures**](#backup-and-recovery-procedures) — Measures the effectiveness and frequency of data backups and the ability to restore systems quickly after a failure or data loss.
        - [**Service Consistency**](#service-consistency) — Examines the ability of the infrastructure to provide predictable and stable service performance under varying workloads and operational conditions.
    - [**Performance**](#performance) — This dimension measures the responsiveness, speed, and efficiency of the infrastructure and its services in processing, storing, and retrieving CH data and metadata.
        - [**Response Time**](#response-time) — Measures how quickly the infrastructure and its services respond to user actions or data requests.
        - [**Throughput**](#throughput) — Evaluates the volume of operations, transactions, or data processed by the infrastructure within a given time period.
        - [**Resource Utilization Efficiency**](#resource-utilization-efficiency) — Assesses how effectively the system uses available computing resources (CPU, memory, storage, and network) to deliver optimal performance.
        - [**Scalability Under Load**](#scalability-under-load) — Examines the infrastructure’s ability to maintain or improve performance as the number of users, data volume, or computational demand increases.
    - [**Security**](#security) — This dimension evaluates the mechanisms protecting data, metadata, and services from unauthorized access, alteration, or loss, ensuring confidentiality, integrity, and compliance with relevant security standards.
        - [**Access Control**](#access-control) — Assesses the effectiveness of authentication and authorization mechanisms that manage and restrict user access to systems and data.
        - [**Data Protection**](#data-protection) — Evaluates the safeguards ensuring confidentiality, integrity, and availability of CH data during storage, transfer, and processing.
        - [**Vulnerability Management**](#vulnerability-management) — Measures the processes for identifying, assessing, and mitigating security risks, vulnerabilities, and potential threats within the infrastructure.
        - [**Compliance and Auditing**](#compliance-and-auditing) — Examines adherence to relevant security standards and regulations, and the implementation of regular audits to verify compliance and detect anomalies.

### Digital Service Evaluation Dimensions

- **Level:** 0
- **Display:** Digital Service Evaluation Dimensions

#### Availability

- **Level:** 1
- **Description:** This dimension assesses the extent to which the digital services are continuously operational and accessible, minimizing downtime and ensuring users can reliably access CH resources at any time.
- **Display:** Availability

##### Service Uptime

- **Level:** 2
- **Description:** Measures the proportion of time that the services remain fully operational and accessible to users.
- **Display:** Service Uptime

##### Redundancy and Failover Mechanisms

- **Level:** 2
- **Description:** Assesses the presence and effectiveness of backup systems, load balancing, and failover strategies that ensure service continuity in case of component failure.
- **Display:** Redundancy and Failover Mechanisms

##### Incident Response Time

- **Level:** 2
- **Description:** Evaluates how quickly the infrastructure team can detect, respond to, and resolve outages or service interruptions.
- **Display:** Incident Response Time

##### Monitoring and Alerting

- **Level:** 2
- **Description:** Examines the robustness of monitoring systems and real-time alert mechanisms that track service health and performance.
- **Display:** Monitoring and Alerting

#### Reliability

- **Level:** 1
- **Description:** This dimension evaluates the infrastructure’s ability to deliver consistent and dependable service performance under expected and peak workloads, avoiding system failures and data loss.
- **Display:** Reliability

##### Fault Tolerance

- **Level:** 2
- **Description:** Assesses the infrastructure’s capacity to continue operating correctly even when components fail or experience errors.
- **Display:** Fault Tolerance

##### Data Integrity

- **Level:** 2
- **Description:** Evaluates mechanisms ensuring that data remains accurate, complete, and consistent during storage, processing, and transmission.
- **Display:** Data Integrity

##### Backup and Recovery Procedures

- **Level:** 2
- **Description:** Measures the effectiveness and frequency of data backups and the ability to restore systems quickly after a failure or data loss.
- **Display:** Backup and Recovery Procedures

##### Service Consistency

- **Level:** 2
- **Description:** Examines the ability of the infrastructure to provide predictable and stable service performance under varying workloads and operational conditions.
- **Display:** Service Consistency

#### Performance

- **Level:** 1
- **Description:** This dimension measures the responsiveness, speed, and efficiency of the infrastructure and its services in processing, storing, and retrieving CH data and metadata.
- **Display:** Performance

##### Response Time

- **Level:** 2
- **Description:** Measures how quickly the infrastructure and its services respond to user actions or data requests.
- **Display:** Response Time

##### Throughput

- **Level:** 2
- **Description:** Evaluates the volume of operations, transactions, or data processed by the infrastructure within a given time period.
- **Display:** Throughput

##### Resource Utilization Efficiency

- **Level:** 2
- **Description:** Assesses how effectively the system uses available computing resources (CPU, memory, storage, and network) to deliver optimal performance.
- **Display:** Resource Utilization Efficiency

##### Scalability Under Load

- **Level:** 2
- **Description:** Examines the infrastructure’s ability to maintain or improve performance as the number of users, data volume, or computational demand increases.
- **Display:** Scalability Under Load

#### Security

- **Level:** 1
- **Description:** This dimension evaluates the mechanisms protecting data, metadata, and services from unauthorized access, alteration, or loss, ensuring confidentiality, integrity, and compliance with relevant security standards.
- **Display:** Security

##### Access Control

- **Level:** 2
- **Description:** Assesses the effectiveness of authentication and authorization mechanisms that manage and restrict user access to systems and data.
- **Display:** Access Control

##### Data Protection

- **Level:** 2
- **Description:** Evaluates the safeguards ensuring confidentiality, integrity, and availability of CH data during storage, transfer, and processing.
- **Display:** Data Protection

##### Vulnerability Management

- **Level:** 2
- **Description:** Measures the processes for identifying, assessing, and mitigating security risks, vulnerabilities, and potential threats within the infrastructure.
- **Display:** Vulnerability Management

##### Compliance and Auditing

- **Level:** 2
- **Description:** Examines adherence to relevant security standards and regulations, and the implementation of regular audits to verify compliance and detect anomalies.
- **Display:** Compliance and Auditing
