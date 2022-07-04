---
layout: post
title: "Raspberry Pi"
subtitle: "documentation"
date: 2022-07-03 19:49:15 -0400
background: '/img/posts/06.jpg'
---

# Computers
## Getting Started
### Setting up your Raspberry Pi
#### Connecting a Display
#### SD Cards for Raspberry Pi
#### Optional items
#### Troubleshooting
### Installing the Operating System
#### Using Raspberry Pi Imager
#### Downloading an Image
### Installing over the Network
#### Using Network Installation
### Configuration on First Boot

## Raspberry Pi OS
### Introduction
### Updating and Upgrading Raspberry Pi OS
#### Using APT
#### Using rpi-update
### Playing Audio and Video
#### The OMXPlayer Application
#### How to Play Audio
#### How to Play Video
#### Options During Playback
#### Playing in the Background
### Using a USB webcam
#### Basic Usage
#### Automating Image Capture
#### Time-Lapse Captures
### Useful Utilities
#### tvservice
#### vcgencmd
#### vcdbg
### Python
#### Thonny
#### Basic Python usage
#### Python files in Thonny
#### Using the Command Line
#### Other Ways of Using Python
#### Installing Python Libraries
### GPIO and the 40-pin Header
![](https://www.raspberrypi.com/documentation/computers/images/GPIO-Pinout-Diagram-2.png)
![](https://www.raspberrypi.com/documentation/computers/images/GPIO.png)
#### Voltages
#### Outputs
#### Inputs
#### More
#### GPIO pinout
#### Permissions
#### GPIO in Python

## Configuration
### The raspi-config Tool
#### List of Options
### Configuring Networking
#### Using the Desktop
#### Using the Command Line
#### The DHCP Daemon
#### Static IP Addresses
### Setting up a Headless Raspberry Pi
#### Configuring Networking
#### Configuring a User
### Setting up a Routed Wireless Access Point
#### Before you Begin
#### Install AP and Management Software
#### Set up the Network Router
#### Ensure Wireless Operation
#### Configure the AP Software
#### Running the new Wireless AP
### Setting up a Bridged Wireless Access Point
#### Before you Begin
#### Install AP and Management Software
#### Setup the Network Bridge
#### Ensure Wireless Operation
#### Configure the AP Software
#### Run the new Wireless AP
### Using a Proxy Server
#### Configuring your Raspberry Pi
#### Update the sudoers File
#### Reboot your Raspberry Pi
### HDMI Configuration
#### HDMI Groups and Mode
#### What Modes does my Device Support?
#### Setting a Specific HDMI Mode
#### Setting a Custom HDMI Mode
#### Troubleshooting your HDMI
### Rotating your Display
#### Fake or Full KMS Graphics Driver
#### Legacy Graphics Driver
### Audio Configuration
#### Changing the Audio Output
#### Troubleshooting your HDMI
### External Storage Configuration
#### Mounting a Storage Device
#### Setting up Automatic Mounting
#### Unmounting a Storage Device
### Localising your Raspberry Pi
#### Changing the Language
#### Configuring the Keyboard
#### Changing the Timezone
### Changing the default pin configuration
#### Device Pins During Boot Sequence
#### Providing a Custom Device Tree Blob
#### Sections of the dt-blob
#### Clock Configuration
#### Sample Device Tree Source File
### Device Trees, Overlays, and Parameters
#### Device Trees
#### Device Tree Overlays
#### Using Device Trees on Raspberry Pi
#### Firmware parameters
#### Troubleshooting
### The Kernel Command Line
#### Command Line Options
### Configuring UARTs
#### Raspberry Pi Zero, 1, 2 and 3
#### Raspberry Pi 4 and 400
#### CM1, CM3, CM3+ and CM4
#### Primary UART
#### Secondary UART
#### Primary and Secondary UART
#### Mini-UART and CPU Core Frequency
#### Disabling the Linux Serial Console
#### Enabling Early Console for Linux
#### UARTs and Device Tree
#### PL011 and mini-UART
### Firmware Warning Icons
#### Undervoltage Warning
#### Over Temperature Warning (80-85°C)
#### Over Temperature Warning (over 85°C)
### LED Warning Flash Codes
### Securing your Raspberry Pi
#### Change the Default Password
#### Changing your Username
#### Make sudo Require a Password
#### Updating Raspberry Pi OS
#### Improving SSH Security
#### Install a Firewall
#### Installing fail2ban
### Configuring Screen Blanking
#### On Console
#### On the Desktop
#### Switching off HDMI
### The boot Folder
#### Boot Folder Contents
#### The Overlays Folder

## The config.txt file
### What is config.txt?
#### File Format
#### Advanced Features
### Common Options
#### Common Display Options
#### Common Hardware Configuration Options
### Onboard Analogue Audio (3.5mm Jack)
#### audio_pwm_mode
#### disable_audio_dither
#### enable_audio_dither
#### pwm_sample_bits
### Boot Options
#### start_file, fixup_file
#### start_x, start_debug
#### disable_commandline_tags
#### cmdline
#### kernel
#### arm_64bit
#### arm_control
#### armstub
#### arm_peri_high
#### kernel_address
#### kernel_old
#### ramfsfile
#### ramfsaddr
#### initramfs
#### init_uart_baud
#### init_uart_clock
#### bootcode_delay
#### boot_delay
#### boot_delay_ms
#### disable_poe_fan
#### disable_splash
#### enable_gic (Raspberry Pi 4 Only)
#### enable_uart
#### force_eeprom_read
#### os_prefix
#### overlay_prefix
#### uart_2ndstage
#### upstream_kernel
### GPIO Control
#### gpio
#### enable_jtag_gpio
### Overclocking Options
#### Overclocking
#### Clocks Relationship
#### Monitoring Core Temperature
#### Monitoring Voltage
#### Overclocking Problems
### Conditional Filters
#### The [all] filter
#### Model Filters
#### The [none] filter
#### The [EDID=*] filter
#### The Serial Number Filter
#### The GPIO Filter
#### The [HDMI:*] Filter
#### Combining Conditional Filters
### Legacy Options
### Memory Options
#### gpu_mem
#### gpu_mem_256
#### gpu_mem_512
#### gpu_mem_1024
#### total_mem
#### disable_l2cache
### Licence Key and Codec Options
#### decode_MPG2
#### decode_WVC1
### Video Options
#### Composite Video Mode
#### HDMI Mode
#### Which Values are Valid for my Monitor?
#### Custom Mode
#### LCD Displays and Touchscreens
#### Generic Display Options
#### Other Options
### Raspberry Pi 4 HDMI Pipeline
### Camera Settings
#### disable_camera_led
#### awb_auto_is_greyworld
### Miscellaneous Options
#### avoid_warnings
#### logging_level
#### max_usb_current

## The Linux kernel
### Kernel
#### Updating your Kernel
#### Getting your Code into the Kernel
### Building the Kernel
#### Building the Kernel Locally
#### Cross-Compiling the Kernel
### Configuring the Kernel
#### Preparing to Configure
#### Using menuconfig
#### Saving your Changes
### Patching the Kernel
#### Version Identification
#### Applying Patches
### Kernel Headers

## Remote Access
### Introduction to Remote Access
#### How to Find your IP Address
### Setting up an SSH Server
#### Set up your Local Network
#### Enabling the Server
### Secure Shell from Linux or Mac OS
### Secure Shell from Windows 10
### Passwordless SSH Access
#### Checking for Existing SSH Keys
#### Generate new SSH Keys
#### Copy your Key to your Raspberry Pi
#### Adjust Directory Permissions
### Using Secure Copy
#### Copying Files to your Raspberry Pi
#### Copying Files from your Raspberry Pi
#### Copying Multiple Files
#### Copying a Whole Directory
### Using rsync
### Network File System (NFS)
#### Setting up a Basic NFS Server
#### Configuring an NFS Client
#### A More Complex NFS Server
#### Troubleshooting
### Samba (SMB/CIFS)
#### Installing Samba Support
#### Mount a Folder Shared from Windows
#### Sharing a Folder from your Raspberry Pi
### Virtual Network Computing (VNC)
#### Installing VNC on Raspberry Pi
#### Enabling the VNC Server
#### Connecting to your Raspberry Pi
#### Using Directly Rendered Applications
#### Creating a Virtual Desktop
### Setting up an Apache Web Server
#### Installing Apache
#### Test the Web Server
#### Installing PHP for Apache
### Network boot your Raspberry Pi
#### Client Configuration
#### Ethernet MAC address
#### Server Configuration
#### Using pxetools
### Network booting using IPv6
#### How it works
#### Test Setup
#### Debugging

## Raspberry Pi Hardware
### Schematics and Mechanical Drawings
#### Raspberry Pi 4 Model B
#### Raspberry Pi 3 Model B+
#### Raspberry Pi 3 Model B
#### Raspberry Pi 2 Model B
#### Raspberry Pi 1 Model B+
#### Raspberry Pi 3 Model A+
#### Raspberry Pi 1 Model A+
#### Raspberry Pi Zero
#### Raspberry Pi Zero W
#### Raspberry Pi Zero 2 W
### Product compliance and safety
#### Flammability Rating
#### The Raspberry Pi Compliance Support
#### Powered by Raspberry Pi
#### Approved Design Partners
### Frequency Management and Thermal Control
#### Using DVFS
#### Measuring Temperatures
#### Adding Heatsinks
### Raspberry Pi 4 Boot EEPROM
#### Boot Diagnostics
#### Updating the Bootloader
#### Updating the EEPROM Configuration
#### Automatic Updates
#### Bootloader Release Status
### Boot Diagnostics on the Raspberry Pi 4
### Raspberry Pi Boot Modes
#### Special bootcode.bin-only boot mode
#### bootcode.bin UART Enable
### Boot sequence
### Raspberry Pi 4 Boot Flow
#### First Stage Bootloader
#### Second Stage Bootloader
#### Bootloader Updates
#### Fail-safe OS updates (TRYBOOT)
### Raspberry Pi 4 Bootloader Configuration
#### Editing the Configuration
#### Configuration Properties
#### Configuration Properties in config.txt
#### Secure Boot configuration properties in config.txt
#### Updating to the LATEST / STABLE bootloader
### USB Boot Modes
#### USB Device Boot Mode
#### USB Host Boot Mode
### USB Mass Storage Boot
#### Raspberry Pi 4B and Raspberry Pi 400
#### Compute Module 4
#### Raspberry Pi 3B+
#### Raspberry Pi 2B, 3A+, 3B, CM3, CM3+, Zero 2 W
#### Booting from USB Mass Storage
#### Known Issues
#### Special bootcode.bin-only Boot Mode
#### Hardware Compatibility
#### Multiple Bootable Drives
### Network Booting
#### Debugging Network Boot Mode
#### Known Problems
### GPIO Boot Mode
#### Pin Assignments
#### Boot Flow
### NVMe SSD Boot
#### Required Hardware
#### Required Software
#### Troubleshooting
### HTTP Boot
#### Requirements
#### Keys
#### Secure Boot
### Parallel Display Interface (DPI)
#### GPIO Pins
#### Disable Other GPIO Peripherals
#### Controlling Output Format
#### Controlling Timings and Resolutions
#### Overlays
#### Example config.txt Settings
### General Purpose I/O (GPIO)
#### GPIO Pads
#### Interrupts
#### Alternative Functions
#### Voltage Specifications
### GPIO Pads Control
### Peripheral Addresses
### Industrial use of the Raspberry Pi
#### One-Time Programmable Settings
#### Write and Read Customer OTP Values
#### Locking the OTP Changes
#### Making Customer OTP bits Unreadable
### OTP Register and Bit Definitions
#### OTP Registers
### Power Supply
#### Typical Power Requirements
#### Power Supply Warnings
#### Back-powering
### Serial Peripheral Interface (SPI)
#### SPI Hardware
#### SPI Software
#### Troubleshooting
### Universal Serial Bus (USB)
#### Maximum Power Output
#### Raspberry Pi 4
#### Raspberry Pi Zero, 1, 2 and 3
#### Known USB Issues
### Raspberry Pi Revision Codes
#### Old-style Revision Codes
#### New-style Revision Codes
#### New-style Revision Codes in Use

## Compute Module Hardware
### Datasheets and Schematics
#### Compute Module 4
#### Older Products
### Design Files for CMIO Boards
### Flashing the Compute Module eMMC
#### Steps to Flash the eMMC
#### Setting up the CMIO board
#### Compute Module 4 Bootloader
#### Troubleshooting
### Attaching and Enabling Peripherals
#### BCM283x GPIOs
#### BCM283x Boot Process
#### Device Tree
#### dt-blob.bin
#### ARM Linux Device Tree
#### Device Tree Source and Compilation
#### Device Tree Debugging
#### Examples
### Attaching a Raspberry Pi Camera Module
#### Updating your System
#### Crypto Chip
#### Quickstart Guide
#### Advanced Issues
### Attaching the Official 7-inch Display
#### Quickstart Guide (Display Only)
#### Quickstart Guide (Display and Cameras)
#### Software Support
#### Firmware Configuration

## Processors
### BCM2835
### BCM2836
### BCM2837
### BCM2837B0
### BCM2711
### RP3A0

# Accessories

# Microcontrollers
