# OPTIGA&trade; TPM

## Quick navigation

<a href="https://www.infineon.com/cms/en/product/security-smart-card-solutions/optiga-embedded-security-solutions/optiga-tpm">
    <img src="https://github.com/Infineon/optiga-tpm/blob/main/pictures/tile-about.jpg" width="192" height="144">
</a>
<a href="https://www.infineon.com/cms/en/product/security-smart-card-solutions/optiga-embedded-security-solutions/optiga-tpm/#!documents">
    <img src="https://github.com/Infineon/optiga-tpm/blob/main/pictures/tile-docs.jpg" width="192" height="144">
</a>
<a href="https://github.com/Infineon/optiga-tpm#tools">
    <img src="https://github.com/Infineon/optiga-tpm/blob/main/pictures/tile-tools.jpg" width="192" height="144">
</a>
<a href="https://github.com/Infineon/optiga-tpm#resources">
    <img src="https://github.com/Infineon/optiga-tpm/blob/main/pictures/tile-resources.jpg" width="192" height="144">
</a>

## Description

The OPTIGA™ TPM 2.0 is a ready-to-use security building block, which is fully compliant with the Trusted Computing Group (TCG) specifications, to protect the platform integrity and authenticity of connected devices. It can also be used to protect encryption keys, and sensitive data so that attackers and malware can't access or tamper with that data.

All OPTIGA™ TPM 2.0 products are based on Infineon's advanced hardware security technology and certified according to common criteria and FIPS security certification, making them an ideal solution for PC, servers, network infrastructure equipment (e.g., gateways, routers, wireless access points and switches) and other IoT devices with strong security requirements.

**Why is software-only security often not enough?**

Keeping secret keys safe and well secured is at the heart of IoT security. See below why **OPTIGA™ TPM** is the preferred choice for this challenge.

<img src="https://github.com/Infineon/optiga-tpm/raw/main/pictures/summary.png">
 
## Key Features and Benefits

* High-end security controller with advanced cryptographic algorithms implemented in hardware (e.g. RSA & ECC256, SHA-256)
* Common Criteria (EAL4+) and FIPS security certification
* Flexible integration thanks to SPI, I2C or LPC interface support
* Reduced risk based on proven technology
* Fast time to market through concept reuse
* Easy integration into all platform architectures and operating systems (Windows, Linux & derivatives)

## Use Cases

* Automatic device onboarding (e.g.,  AWS Greengrass and Azure IoT edge)
* Device health attestation
* Device identity for network access control
* Secret (configuration data, IP, and etc) protection
* Secured communication with TLS
* Secured firmware update
* Secured key storage
* Verification of device authenticity

## Resources

Here you will find a list of relevant resouces which can can help you to study and learn TPM2.0.

### Tools

CMD-line and GUI tools running on Linux:

1. [ELTT2 - Infineon Embedded Linux TPM Toolbox 2 for TPM 2.0](https://github.com/Infineon/eltt2) for a quick TPM startup
   - Startup tool with basic functions in CMD-line
   - Can be compiled on Linux, other OS, and embedded platforms
2. [OPTIGA™ TPM 2.0 Explorer GUI tool for Raspberry Pi](https://github.com/Infineon/optiga-tpm-explorer)
   - The ease of use of GUI has made it possible for all users in general, regardless of experience or knowledge, to access all kinds of OPTIGA™ TPM 2.0 features and use cases for commonly use

### Open Source Host Code

OPTIGA™ TPM 2.0 host code and documentations are now available as open source repository on GitHub:

1. [AWS IoT Greengrass Hardware Security Integration](https://github.com/Infineon/amazon-greengrass-hsi-optiga-tpm)
2. [PKCS11 token creation](https://github.com/Infineon/pkcs11-optiga-tpm)
3. [TPM-based remote attestation](https://github.com/Infineon/remote-attestation-optiga-tpm)
4. [TPM 2.0 integration for PSoC 6 Wi-Fi BT Prototyping Kit to enable TPM backed onboarding to AWS IoT Core](https://github.com/Infineon/psoc6-aws-iot-optiga-tpm)
5. [TPM 2.0 used with EK based onboarding](https://github.com/Infineon/ek-based-onboarding-optiga-tpm)
6. [TPM 2.0 backed Linux Trusted and Encrypted Keys](https://github.com/Infineon/linux-trusted-key-optiga-tpm)
7. [TPM 2.0 in U-Boot on Raspberry Pi 4](https://github.com/joholl/rpi4-uboot-tpm)
8. [Extend measurements to TPM 2.0 PCR in U-Boot on Raspberry Pi 4](https://github.com/wxleong/tpm2-uboot-rpi4)
9. [TPM 2.0 command reference and code examples](https://github.com/Infineon/optiga-tpm-cheatsheet)
10. [Guide to Integrating TPM 2.0 with the Android Open Source Project (AOSP)](https://github.com/Infineon/optiga-tpm-aosp)

### Application notes

These documents are intended for customers who want to evaluate how to start with the TPM software integration for their target applications:

1. [Integration of an OPTIGA™ TPM SLx 9670 TPM2.0 with SPI Interface in a Raspberry Pi® 4 Linux environment](https://www.infineon.com/dgdl/Infineon-OPTIGA_SLx_9670_TPM_2.0_Pi_4-ApplicationNotes-v07_19-EN.pdf?fileId=5546d4626c1f3dc3016c3d19f43972eb)
2. [Integration of TLS Functionality for OPTIGA™ TPM SLx 9670 TPM 2.0](https://www.infineon.com/dgdl/Infineon-OPTIGA_TPM_SLx9670_TPM_2.0-ApplicationNotes-v01_00-EN.pdf?fileId=5546d46271bf4f920171c5598a3a0e7b)
3. [Integration of an OPTIGA™ TPM SLx 9670 TPM2.0 with SPI Interface in a Raspberry Pi® 3 Linux environment with integrated TPM Driver](https://www.infineon.com/dgdl/Infineon-App-Note-SLx9670-TPM2.0_Embedded_RPi_DI_SLx-ApplicationNotes-v01_03-EN.pdf?fileId=5546d46267c74c9a01684b96e69f5d7b)
4. [Integration of an OPTIGA™ TPM SLx 9670 TPM2.0 with SPI Interface in a Raspberry Pi® 3 Linux environment with TPM Driver Patch](https://www.infineon.com/dgdl/Infineon-App-Note-SLB9670-TPM2.0-and-RaspberryPi-3-ApplicationNotes-v01_20-EN.zip?fileId=5546d46265257de8016537f329595e5c)

