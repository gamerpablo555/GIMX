# GIMX – Experimental Nacon PS4 Authentication Support

Experimental fork of **GIMX** adding support for using a **Nacon Wired Compact Controller** for PS4 authentication.

> [!WARNING]
> This is an experimental modification.
> It is not an official GIMX release and may contain bugs or compatibility issues.

## About

This fork adds experimental PS4 authentication support for:

- **Controller:** Nacon Wired Compact Controller
- **USB VID:PID:** `146b:0603`
- **Platform:** PlayStation 4
- **Base project:** GIMX

The goal of this modification is to allow the Nacon controller to be used as the authentication controller when using GIMX with a PS4.

## Changes

The main modifications are located in:

- `core/controller.c`
- `core/connectors/usb_con.c`

These changes add the controller-specific handling required for the Nacon Wired Compact Controller and its PS4 authentication process.

## Hardware tested

This modification has been developed/tested with:

**Nacon Wired Compact Controller**

```text
VID: 146b
PID: 0603
VID:PID: 146b:0603
