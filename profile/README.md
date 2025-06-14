# The Quixote Project - Tilting at the Travails of Cybersecurity

## _Under construction...._

## Overview

Welcome to the Quixote Project, an initiative dedicated to bringing to
Linux the first major change in how to approach operating system
security, since the introduction of Mandatory Access Controls (MAC's)
almost 50 years ago.

A fundamental objective of Quixote is to lower the barriers to the
development of mandatory access controls that precisely describe the
security behavior of a workload.  It does so by providing
infrastructure that allows development teams to use Continuous
Integration and Continuous Delivery (CI/CD) pipelines to generate
precise descriptions of the security behavior that a workload will be
allowed to later exhibit when the workload is placed into production.

Quixote is specifically designed to meet the needs of containerized
workloads and to lower the barriers to implementing remote attestation
and integrity controls that are needed to support Confidential
Computing (COCO) platforms.

Quixote is based on the fundamental concept that the security behavior
of a workload can be mathematically modeled, just like all other
physical processes.  This approach allows development teams to
implement security architectures that range from fully deterministic
models to those based on machine learning and artificial intelligence
models.

Quixote implements the concept of Trusted Security Event Modeling
(TSEM) based on the the Quixote Task Identity Model.  This task
identity model creates a description of each security relevant event
that a workload exhibits that is based on the cryptographic identity
of the executable code that generates the event.

This provides a framework for simplifying the implementation of supply
chain software security.  Unit testing of a workload, in a verified
build environment, yields a cryptographically signed security model
that constrains the workload to only the security behaviors that were
exhibited in the trusted build environment.  Any subsequent
modification to the software package or its execution environment
would result in security behavior that would be flagged as
inconsistent with its description.
