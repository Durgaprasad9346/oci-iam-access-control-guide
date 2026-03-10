# oci-iam-access-control-guide
OCI IAM deep dive covering users, groups, policies, dynamic groups, instance principals and advanced access patterns in Oracle Cloud Infrastructure.

## Overview

Identity and Access Management (IAM) is the security foundation of Oracle Cloud Infrastructure (OCI). It controls authentication and authorization for users, services, and applications interacting with cloud resources.

OCI IAM allows administrators to define who can access resources and what actions they can perform through policies, groups, and dynamic access mechanisms.

This repository provides an in-depth explanation of OCI IAM components and advanced access patterns used in enterprise cloud environments.

---

## Core IAM Components

OCI IAM consists of several key components:

- Compartments
- Users
- Groups
- Policies
- Dynamic Groups
- Instance Principals
- Resource Principals

These components work together to implement secure access control across OCI services.

---

## IAM Access Flow

Typical access flow:


User
│
▼
OCI IAM
│
▼
Group Membership
│
▼
Policy Evaluation
│
▼
Access to OCI Resource



---

## Repository Structure

The repository contains detailed documentation for the following IAM concepts:

- IAM Overview
- Compartment hierarchy
- Users and groups
- IAM policy syntax
- Dynamic groups and instance principals
- Advanced IAM access patterns

---

## Learning Outcome

After exploring this guide, readers will understand how to design secure IAM policies and implement advanced authentication mechanisms in OCI environments.
