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
<a href="https://github.com/Infineon/optiga-tpm#application-notes">
    <img src="https://github.com/Infineon/optiga-tpm/blob/main/pictures/tile-appnotes.jpg" width="192" height="144">
</a>

## Description

The OPTIGA™ TPM 2.0 is a ready-to-use security building block, which is fully compliant with the Trusted Computing Group (TCG) specifications, to protect the platform integrity and authenticity of connected devices. It can also be used to protect encryption keys, and sensitive data so that attackers and malware can’t access or tamper with that data.

All OPTIGA™ TPM 2.0 products are based on Infineon’s advanced hardware security technology and certified according to common criteria and FIPS security certification, making them an ideal solution for PC, servers, network infrastructure equipment (e.g., gateways, routers, wireless access points and switches) and other IoT devices with strong security requirements.

**Why is software-only security often not enough?**
Keeping secret keys safe and well secured is at the heart of IoT security. See below why OPTIGATM TPM is the preferred choice for this challenge. 

<img src="https://github.com/Infineon/optiga-tpm/raw/main/pictures/summary.png">
 
## Key Features and Benefits

* High-end security controller with advanced cryptographic algorithms implemented in hardware (e.g. RSA & ECC256, SHA-256)
* Common Criteria (EAL4+) and FIPS security certification
* Flexible integration thanks to SPI, I2C or LPC interface support
* Reduced risk based on proven technology
* Fast time to market through concept reuse
* Easy integration into all platform architectures and operating systems (Windows, Linux & derivatives)

## Use Cases

* Verification of device authenticity
* Device identity for network access control
* Automatic device onboarding (e.g.,  AWS Greengrass and Azure IoT edge)
* Secured communication with TLS 
* Device health attestation

## Tools

1. [ELTT2 - Infineon Embedded Linux TPM Toolbox 2 for TPM 2.0](https://github.com/Infineon/eltt2) for a quick TPM startup 
    - Can be compiled on Linux, other OS, and embedded platforms
    - Startup tool with basic functions

## Application Notes

### OPTIGA™ TPM SLx 9670
1. [AWS IoT Greengrass Hardware Security Integration](https://github.com/Infineon/amazon-greengrass-hsi-optiga-tpm)
2. [PKCS11 token creation](https://github.com/Infineon/pkcs11-optiga-tpm)
3. [TPM-based remote attestation](https://github.com/Infineon/remote-attestation-optiga-tpm)
4. [TPM 2.0 integration for PSoC 6 Wi-Fi BT Prototyping Kit to enable TPM backed onboarding to AWS IoT Core](https://github.com/Infineon/psoc6-aws-iot-optiga-tpm)
5. [TPM 2.0 used with EK based onboarding](https://github.com/Infineon/ek-based-onboarding-optiga-tpm)
6. [TPM 2.0 backed Linux Trusted and Encrypted Keys](https://github.com/Infineon/linux-trusted-key-optiga-tpm)
7. [TPM 2.0 in U-Boot on Raspberry Pi 4](https://github.com/joholl/rpi4-uboot-tpm)
8. [Extend measurements to TPM 2.0 PCR in U-Boot on Raspberry Pi 4](https://github.com/wxleong/tpm2-uboot-rpi4)

## Documentation and Other Application Notes

For high level description and some important excerpts from the documentation please refer to [documents](https://www.infineon.com/cms/en/product/security-smart-card-solutions/optiga-embedded-security-solutions/optiga-tpm/?redirId=39899#!documents).
