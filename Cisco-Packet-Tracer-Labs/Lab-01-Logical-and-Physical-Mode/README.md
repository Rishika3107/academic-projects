# Lab 01 — Logical and Physical Mode Exploration (Cisco Packet Tracer)

## Objective
The purpose of this lab was to understand the difference between logical
and physical network representations, and why both perspectives are
necessary for secure and reliable network operations.

---

## Conceptual Background

In real-world networks:
- The logical view shows how devices communicate
- The physical view shows where devices exist, how they are connected,
  and what physical constraints apply

Security and availability issues often arise not from incorrect logical
design, but from overlooked physical dependencies.

This lab demonstrated how the same network can appear correct logically
while hiding risks physically.

---

## What Was Done in the Lab

### Step 1: Logical Topology Analysis
- Examined the logical connections between routers, switches, and end devices
- Identified communication paths and dependency chains
- Verified expected packet flow between nodes

---

### Step 2: Physical Mode Exploration
- Switched to physical mode to observe device placement
- Analyzed how geographical separation and cabling impact fault tolerance
- Observed how a single physical failure point could affect multiple
  logical connections

---

### Step 3: Validation and Observation
- Confirmed that logical connectivity does not guarantee physical resilience
- Observed how physical constraints influence troubleshooting decisions

---

## Key Learnings

- Logical diagrams simplify understanding but can hide real risks
- Physical design directly affects security, redundancy, and recovery
- Network documentation must include both views to be operationally useful

---

## Security Perspective

From a security standpoint, physical topology:
- Defines the true attack surface
- Influences monitoring and access control decisions
- Determines blast radius during failures or attacks

Ignoring physical layout can lead to blind spots in both defense and response.

---

## Summary

This lab shifted my understanding of networks from abstract connectivity
to real-world infrastructure awareness, which is essential for both
network security and incident response.
