---
title: Commands most used
---

# Commands most used

## List item

it is recommended to update the system packages to the latest versions available:

```bash
yum update -y && yum upgrade -y
```

## Install package

    yum install package-name

## Reinstall package
 
When the package was not installed properly:

    yum reinstall package-name

## Update package

We can update an specific package:

     yum update package-name

## Remove package
 
     yum remove package-name

## Information about package
 
When we want to know its version, size, release, etc:

    yum info te package-name

## History

To see all the yum commands executed before the last use of history command:

    yum history
