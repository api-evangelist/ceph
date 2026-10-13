<!-- fetched 2026-10-13 from https://docs.ceph.com/en/latest/radosgw/s3/ by sweep-shape-compat.py; text extracted from the provider's own page -->

Ceph Object Gateway S3 API — Ceph Documentation 
 Ceph Object Gateway 
 Ceph Object Gateway S3 API
 View page source 
 Start Here 
 Installing Ceph 
 Cephadm 
 Ceph Storage Cluster 
 Ceph File System 
 Ceph Block Device 
 Ceph Object Gateway Configuration 
 Administration 
 Authentication 
 APIs AWS IAM 
 AWS S3 Bucket Policy 
 Bucket Logging 
 Cloud Transition 
 Cloud Restore 
 S3-select 
 Server-Side Encryption 
 API 
 Features Support 
 Unsupported Header Fields 
 AWS SNS 
 AWS STS 
 OpenStack Swift 
 Admin Ops API 
 Python Binding 
 Other 
 Ceph Container Storage Interface (CSI) 
 Ceph Manager Daemon 
 Ceph Dashboard 
 Monitoring Overview 
 API Documentation 
 Architecture 
 Developer Guide 
 Ceph Internals 
 Governance 
 Technical Charter 
 Ceph Foundation 
 ceph-volume 
 Crimson (Tech Preview) 
 Ceph Releases (general) 
 Ceph Releases (index) 
 Security 
 Hardware Monitoring 
 Glossary 
 Tracing 
 Ceph Notice
 This document is for a development version of Ceph.
 Report a Documentation Bug 
 Ceph Object Gateway S3 API  
 Ceph supports a RESTful API that is compatible with the basic data access model of the Amazon S3 API .
 Bucket Policy 
 Bucket Logging 
 Cloud Transition 
 Cloud Restore 
 S3-select 
 Server-Side Encryption 
 API  
 Common 
 Authentication 
 Service Ops 
 Bucket Ops 
 Object Ops 
 S3 Control 
 C++ 
 C# 
 Java 
 Perl 
 PHP 
 Python 
 Ruby AWS::SDK Examples (aws-sdk gem ~>2) 
 Ruby AWS::S3 Examples (aws-s3 gem) 
 Features Support  
 The following table describes the support status for current Amazon S3 functional features:
 Feature
 | Status
 | Remarks
 | 
 List Buckets 
 | Supported
 | | 
 Delete Bucket 
 | Supported
 | | 
 Create Bucket 
 | Supported
 | Different set of canned ACLs
 | 
 Bucket Lifecycle 
 | Supported
 | | 
 Bucket Replication 
 | Partial
 | Permitted only across zones
 | 
 Policy (Buckets, Objects) 
 | Supported
 | ACLs & bucket policies are supported
 | 
 Bucket Website 
 | Supported
 | | 
 Bucket ACLs (Get, Put) 
 | Supported
 | Different set of canned ACLs
 | 
 Bucket Location 
 | Supported
 | | 
 Bucket Notification 
 | Supported
 | See S3 Bucket Notifications Compatibility 
 | 
 Bucket Object Versions 
 | Supported
 | | 
 Get Bucket Info (HEAD) 
 | Supported
 | | 
 Bucket Request Payment 
 | Supported
 | | 
 Put Object 
 | Supported
 | | 
 Delete Object 
 | Supported
 | | 
 Get Object 
 | Supported
 | | 
 Object ACLs (Get, Put) 
 | Supported
 | | 
 Get Object Info (HEAD) 
 | Supported
 | | 
 Get Object Attributes 
 | Supported
 | Added in Tentacle
 | 
 POST Object 
 | Supported
 | | 
 Copy Object 
 | Supported
 | | 
 Multipart Uploads 
 | Supported
 | | 
 Object Tagging 
 | Supported
 | See Object Related Operations for Policy verbs
 | 
 Bucket Tagging 
 | Supported
 | | 
 Storage Class 
 | Supported
 | See Storage Classes 
 | 
 Bucket Logging 
 | Supported
 | | 
 Object Ownership 
 | Supported
 | | 
 Bucket PublicAccessBlock 
 | Supported
 | | 
 Account PublicAccessBlock 
 | Supported
 | See S3 Control 
 | 
 Unsupported Header Fields  
 The following common request header fields are not supported:
 Name
 | Type
 | 
 x-amz-id-2 
 | Response
 | 
 Brought to you by the Ceph Foundation
 The Ceph Documentation is a community resource funded and hosted by the non-profit Ceph Foundation . If you would like to support this and our other efforts, please consider joining now .
 Previous Next 
 © Copyright 2016-2026, Ceph authors and contributors. Licensed under Creative Commons Attribution Share Alike 3.0 (CC-BY-SA-3.0).
