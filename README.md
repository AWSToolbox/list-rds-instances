<h1 align="center">
	<a href="https://github.com/WolfSoftware">
		<img src="https://raw.githubusercontent.com/WolfSoftware/branding/master/images/general/banners/64/black-and-white.png" alt="Wolf Software Logo" />
	</a>
	<br>
	List all RDS Instances
</h1>


<p align="center">
	<a href="https://travis-ci.com/AWSToolbox/list-rds-instances">
		<img src="https://img.shields.io/travis/com/AWSToolbox/list-rds-instances/master?style=for-the-badge&logo=travis" alt="Build Status">
	</a>
	<a href="https://github.com/AWSToolbox/list-rds-instances/releases/latest">
		<img src="https://img.shields.io/github/v/release/AWSToolbox/list-rds-instances?color=blue&style=for-the-badge&logo=github&logoColor=white&label=Latest%20Release" alt="Release">
	</a>
	<a href="https://github.com/AWSToolbox/list-rds-instances/releases/latest">
		<img src="https://img.shields.io/github/commits-since/AWSToolbox/list-rds-instances/latest.svg?color=blue&style=for-the-badge&logo=github&logoColor=white" alt="Commits since release">
	</a>
	<a href="LICENSE.md">
		<img src="https://img.shields.io/badge/license-MIT-blue?style=for-the-badge&logo=read-the-docs&logoColor=white" alt="Software License">
	</a>
	<br>
	<a href=".github/CODE_OF_CONDUCT.md">
		<img src="https://img.shields.io/badge/Code%20of%20Conduct-blue?style=for-the-badge&logo=read-the-docs&logoColor=white" />
	</a>
	<a href=".github/CONTRIBUTING.md">
		<img src="https://img.shields.io/badge/Contributing-blue?style=for-the-badge&logo=read-the-docs&logoColor=white" />
	</a>
	<a href=".github/SECURITY.md">
		<img src="https://img.shields.io/badge/Report%20Security%20Concern-blue?style=for-the-badge&logo=read-the-docs&logoColor=white" />
	</a>
	<a href=".github/SUPPORT.md">
		<img src="https://img.shields.io/badge/Get%20Support-blue?style=for-the-badge&logo=read-the-docs&logoColor=white" />
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

## Contributors

<p>
	<a href="https://github.com/TGWolf">
		<img src="https://img.shields.io/badge/Wolf-black?style=for-the-badge" />
	</a>
</p>

## Show Support

<p>
	<a href="https://ko-fi.com/wolfsoftware">
		<img src="https://img.shields.io/badge/Ko%20Fi-blue?style=for-the-badge&logo=ko-fi&logoColor=white" />
	</a>
</p>
