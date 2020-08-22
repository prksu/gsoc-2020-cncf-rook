# Google Summer of Code 2020 - Rewrite NFS Operator to use controller-runtime - Rook (CNCF)

## Project Abstract

> This project aims to implement controller-runtime for Rook nfs-operator and addresses several issues along with it. Currently, Rook nfs-operator only simply watches an event of CustomResource from an informer. Controller-runtime is a good library for building an operator which incorporates the best-practice controller principles.  

## General Info

Name: Ahmad Nurus Shobah    
Email: ahmadnurus.sh@gmail.com  
Github: [prksu](https://github.com/prksu)   
Twitter: [@ahmadnurus](https://twitter.com/ahmadnurus)

## Project Mentors

- Ashish Ranjan ([ashishranjan738](https://github.com/ashishranjan738))   
- Jared Watts ([jbw976](https://github.com/jbw976))   
- Rohan Gupta ([rohan47](https://github.com/rohan47))   

## Links

[Project on GSoC site](https://summerofcode.withgoogle.com/projects/#5111726279753728)  
[Project Proposal](proposal/proposal.pdf)  
[Project Proposal Draft](https://docs.google.com/document/d/1mSO6KygBhl7-ZxFQ1oSpWW8EE_BvjMgju6U36PsNF2o/edit?usp=sharing)  
[Feature request for this project](https://github.com/rook/rook/issues/4950)  
[Progress Tracker (Google Document)](https://docs.google.com/document/d/1dgecQAZvTpK8eiX3Y53tEb1GjirZHWeeYpafcxgOw88/edit#)

## Pull Requests and Issues made to the `rook` organization

*The following list is automatically generated using https://github.com/nikhita/github-contrib.*

**Repository: rook**

Total Pull Requests Created: 8
1. [rook/rook#6112](https://github.com/rook/rook/pull/6112) - nfs: design nfs quota
2. [rook/rook#5863](https://github.com/rook/rook/pull/5863) - nfs: nfs provisioner controlled by operator
3. [rook/rook#5854](https://github.com/rook/rook/pull/5854) - doc: update nfs openshift scc documentation
4. [rook/rook#5830](https://github.com/rook/rook/pull/5830) - doc: design nfs provisioner controlled by operator
5. [rook/rook#5785](https://github.com/rook/rook/pull/5785) - nfs: fix nfs issue on openshift
6. [rook/rook#5650](https://github.com/rook/rook/pull/5650) - nfs: implement controller-runtime in nfs operator
7. [rook/rook#5567](https://github.com/rook/rook/pull/5567) - design: nfs operator using controller-runtime
8. [rook/rook#5541](https://github.com/rook/rook/pull/5541) - design: rename nfs object kind

Total Issues Opened: 1
1. [rook/rook#5788](https://github.com/rook/rook/issues/5788) - nfs: support disk quota for NFS server

Total Pull Requests Reviewed: 4
1. [rook/rook#5637](https://github.com/rook/rook/pull/5637) - nfs: changing the loglevel into INFO
2. [rook/rook#5554](https://github.com/rook/rook/pull/5554) - nfs: changed cmd run
3. [rook/rook#5064](https://github.com/rook/rook/pull/5064) - convert the CockroachDB controller to the controller-runtime
4. [rook/rook#5045](https://github.com/rook/rook/pull/5045) - ceph: Adding support for admission controllers