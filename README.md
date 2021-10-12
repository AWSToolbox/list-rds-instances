<p align="center">
    <a href="https://github.com/AWSToolbox/">
        <img src="https://cdn.wolfsoftware.com/assets/images/github/organisations/awstoolbox/black-and-white-circle-256.png" alt="AWSToolbox logo" />
    </a>
    <br />
    <a href="https://github.com/AWSToolbox/list-rds-instances/actions/workflows/pipeline.yml">
        <img src="https://img.shields.io/github/workflow/status/AWSToolbox/list-rds-instances/pipeline/master?style=for-the-badge" alt="Github Build Status">
    </a>
    <a href="https://github.com/AWSToolbox/list-rds-instances/releases/latest">
        <img src="https://img.shields.io/github/v/release/AWSToolbox/list-rds-instances?color=blue&label=Latest%20Release&style=for-the-badge" alt="Release">
    </a>
    <a href="https://github.com/AWSToolbox/list-rds-instances/releases/latest">
        <img src="https://img.shields.io/github/commits-since/AWSToolbox/list-rds-instances/latest.svg?color=blue&style=for-the-badge" alt="Commits since release">
    </a>
    <br />
    <a href=".github/CODE_OF_CONDUCT.md">
        <img src="https://img.shields.io/badge/Code%20of%20Conduct-blue?style=for-the-badge" />
    </a>
    <a href=".github/CONTRIBUTING.md">
        <img src="https://img.shields.io/badge/Contributing-blue?style=for-the-badge" />
    </a>
    <a href=".github/SECURITY.md">
        <img src="https://img.shields.io/badge/Report%20Security%20Concern-blue?style=for-the-badge" />
    </a>
    <a href="https://github.com/AWSToolbox/list-rds-instances/issues">
        <img src="https://img.shields.io/badge/Get%20Support-blue?style=for-the-badge" />
    </a>
    <br />
    <a href="https://wolfsoftware.com/">
        <img src="https://img.shields.io/badge/Created%20by%20Wolf%20Software-blue?style=for-the-badge" />
    </a>
</p>

## Overview

This script will list all of your RDS instances in a given region.

### Installation

Once you have cloned the code you will need to install the required python packages.

```
pip install -r requirements.txt 
```
> The requirements file is in the src directory

### Usage

```shell
./list-rds-instances.py [-r region]
```

### Requirements

You will need a valid set of AWS credentials in order to run this command.

### Results

The script will return the following details for each RDS instances it finds.

* Instance Name
* Instance Class
* Status
* Availability Zone(s)
* Publicly Accessible
* Allocated Storage
* Storage Encrypted
* Engine
* Engine Version
* Performance Insights
