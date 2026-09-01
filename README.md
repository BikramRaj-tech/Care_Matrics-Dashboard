## Care_Matrics-Dashboard
## 1. Project Title
   
CareMetrics: Hospital Operations and Patient Flow Analytics Dashboard

## 2. Short Description

CareMetrics is an interactive healthcare analytics project developed to help hospital administrators monitor patient flow, operational efficiency, capacity utilization, and service bottlenecks.

The project consolidates hospital data related to patients, appointments, admissions, diagnostics, billing, discharge, and beds into a Power BI-ready analytical dataset. Interactive dashboards provide insights into patient volume, waiting times, diagnostic turnaround time, bed occupancy, doctor workload, congestion risk, and departmental performance.

The objective is to transform raw hospital operational data into clear, actionable insights that can support better resource allocation and operational decision-making.

## 3. Tech Stack
Technology	-  Purpose

Microsoft  -  Excel	Data storage, data cleaning and initial analysis

Python	 -    Data generation, cleaning, transformation and analysis

Pandas	  -   Data manipulation and preprocessing

Power BI	 -   Interactive dashboard and visualization

Power Query	 -   Data transformation and consolidation

DAX	    -     KPI calculations and analytical measures

CSV / XLSX	-  Data storage and Power BI input

## 4. Data Source

The project uses a synthetic hospital operations dataset containing 5,000 patient/encounter records.

The data is organized into multiple operational tables:

Patients

Appointments

Admissions

Diagnostics

Billing

Discharge

Beds


The datasets are consolidated into a PowerBI_Unified table for analysis and dashboard development.

Main data fields include:

Patient ID

Encounter ID

Doctor ID

Department

Appointment Date

Appointment Time

Waiting Time

Consultation Time

Diagnostic Turnaround Time

Billing Delay

Discharge Delay

Length of Stay

Bed Occupancy

Congestion Risk

Bottleneck Score

## 5. Features / Highlights

📊 Executive Overview

Provides a high-level view of hospital performance through:

Total Patients

Total Encounters

Average Waiting Time

Average Length of Stay

Bed Occupancy

Completed Appointment Percentage

Patient volume by department

Monthly patient volume

Congestion risk distribution

🚑 Patient Flow & Bottleneck Analysis

Identifies delays throughout the patient journey:

Average waiting time

Consultation time

Diagnostic turnaround time

Billing delay

Discharge delay

Patient flow delay by process

Department-level waiting time

Congestion risk analysis

Peak patient-volume hours

🏥 Capacity & Resource Optimization

Helps identify resource and capacity constraints:

Bed occupancy analysis

Beds by department

Doctor workload

Patients per doctor

Patient demand vs. bed capacity

Capacity utilization status

Department demand by hour

High-congestion areas

📈 Leadership & Operations Scorecard

Provides management-level insights through:

Department performance ranking

Operational bottleneck score

Congestion risk by department

Average delay across patient-flow stages

Department operations scorecard

Overall operational status

Priority areas for improvement

## 6. Dashboard Pages


| Page       | Dashboard                         | Main Purpose                          |
| ---------- | --------------------------------- | ------------------------------------- |
| **Page 1** | Executive Overview                | Overall hospital performance          |
| **Page 2** | Flow Bottleneck Analysis          | Identify patient-flow delays          |
| **Page 3** | Capacity & Resource Optimization  | Analyze beds and resource utilization |
| **Page 4** | Leadership & Operations Scorecard | Support management decisions          |

## 7. Key KPIs

The project calculates important operational KPIs using DAX, including:

Total Patients

Total Encounters

Average Waiting Time

Average Consultation Time

Average Diagnostic TAT

Average Billing Delay

Average Discharge Delay

Average Length of Stay

Bed Occupancy

Patients per Doctor

High Congestion %

Bottleneck Score

## 8. Interactive Features

The Power BI report includes:

Date range slicer

Department slicer

Congestion-risk filter

Interactive charts

KPI cards

Drill/filter interactions

Conditional formatting

Department comparisons

Monthly and hourly analysis

Navigation between dashboard pages

## 9. Key Outcome

The final dashboard transforms raw hospital records into an interactive operational intelligence solution that helps identify:

Where patients are waiting, where processes are slowing down, where capacity is constrained, and which departments require management attention.

## 10. Screenshorts / Demos of Dashboard

Show what the dashboard looks like.

Example:
