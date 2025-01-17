---
uid: Connector_help_Nevion_Flashlink_Frame_-_SDI-EO-D
---

# Nevion Flashlink Frame - SDI-EO-D

This exported connector shows data from an SDI-EO-D module in a Nevion Flashlink frame.

## About

This is an **SNMP** connector that is automatically generated by the parent connector [Nevion Flashlink Frame](xref:Connector_help_Nevion_Flashlink_Frame).

### Version Info

| **Range** | **Description** | **DCF Integration** | **Cassandra Compliant** |
|------------------|-----------------|---------------------|-------------------------|
| 2.0.3.x          | Basic range.    | No                  | Yes                     |

### Product Info

| Range | Supported Firmware Version |
|------------------|-----------------------------|
| 2.0.3.x          | 5.0.4                       |

## Installation and configuration

### Creation

This connector is used by DVE child elements that are **automatically created** by the parent connector [Nevion Flashlink Frame](xref:Connector_help_Nevion_Flashlink_Frame).

## Usage

### General Page

This page contains general information about an SDI-EO-D module, including:

- Type
- Card Status
- Chassis Number
- Slot Number
- Label
- Alarm Status
- Alarm Trap
- Alarm Count
- Main Element Name

### Laser Page

This page displays the **Laser Table**, which contains information about laser parameters.

It also allows you to view the Laser **Num**, **Wavelength**, **Power** and **Type**, as well as to configure the **Config**, **Status** and **Alarms**.

### Signal Input Page

This page displays the **EQ Table**, which contains information about EQ parameters.

It also allows you to view the **Num** and **Status**, as well as to configure **Config** and **Alarms**.

### Voltage Page

This page displays the **Voltage Table**, which contains information about voltage measurements.

It also allows you to configure the **Upper** and **Lower Limit** and **Alarms**, as well as to view the **Nominal** effect and the **Value** in Volts and Watts.

### Temperature Page

This page displays the **Temperature Table**, which contains information about temperature measurements.

It also allows you to configure the **Nominal** value, **Upper** and **Lower Limit** and **Alarms**, as well as to view the actual temperature **Value**.
