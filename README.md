<!--
 ___ _            _ _    _ _    __
/ __(_)_ __  _ __| (_)__(_) |_ /_/
\__ \ | '  \| '_ \ | / _| |  _/ -_)
|___/_|_|_|_| .__/_|_\__|_|\__\___|
            |_| 
-->
![](https://docs.simplicite.io//logos/logo250.png)
* * *

`SalesForce` module definition
==============================

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=simplicite-modules-SalesForce&metric=alert_status)](https://sonarcloud.io/dashboard?id=simplicite-modules-SalesForce)

### Introduction

**SalesForce** integration remote business objects examples.

### Import

To import this module:

- Create a module named `SalesForce`
- Set the settings as:

```json
{
	"type": "git",
	"origin": {
		"uri": "https://github.com/simplicitesoftware/module-salesforce.git"
	}
}
```

- Click on the _Import module_ button

### Configure

There is one system parameter to configure:

- The `SALESFORCE_CREDENTIALS` in which you must set your SalesForce credentials

> **Note**: it is possible to ovveride these default parameters per user using corresponding user parameters.

`SFAccount` business object definition
--------------------------------------

SalesForce _Account_ object.

**Note**: the objet fields are retreived from SalesForce metadata at runtime

### Fields

| Name                                                         | Type                                     | Required | Updatable | Personal | Description                                                                      |
|--------------------------------------------------------------|------------------------------------------|----------|-----------|----------|----------------------------------------------------------------------------------|

`SFCase` business object definition
-----------------------------------

SalesForce _Case_ object.

**Note**: the objet fields are retreived from SalesForce metadata at runtime

### Fields

| Name                                                         | Type                                     | Required | Updatable | Personal | Description                                                                      |
|--------------------------------------------------------------|------------------------------------------|----------|-----------|----------|----------------------------------------------------------------------------------|

`SFContact` business object definition
--------------------------------------

SalesForce _Contact_ object.

**Note**: the objet fields are retreived from SalesForce metadata at runtime

### Fields

| Name                                                         | Type                                     | Required | Updatable | Personal | Description                                                                      |
|--------------------------------------------------------------|------------------------------------------|----------|-----------|----------|----------------------------------------------------------------------------------|

