# Installation Name Candidates

**This repository provides names to be used for new Giant Swarm installations.**

**Note:** There is no guarantee that the names provided here are actually still available. Giant Swarm staff must run additional checks to ensure that a name is unused.

## What is an installation

A Giant Swarm installation is the combination of a management cluster, bastion hosts, and some more components. Depending on your viewpoint, you may or may not count workload clusters in as part of the installation.

## What is an installation name

The installation name is a unique identifier for the installation. It becomes part of the DNS zone for the installation.

The installation name cannot be changed throughout the lifecycle of an installation.

## How to claim a name

1. Look for a name in one of the `.txt` files.

2. Create a pull request that removes the name you want to claim from the list. Please use the title format `Claim installation name 'NAME'` where `NAME` is the name you claim.

3. Get approval from a repository maintainer.

4. Merge the pull request (or let a maintainer merge it).
