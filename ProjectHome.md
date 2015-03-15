This is a project hoping to create a standard interconnect for high speed delta-sigma digital signals, 1 bit up to 8 bit, speeds as high as 24.576Mhz (512fs), using LVDS. This interconnect is hoping to be an open alternative to the SDIF-2/3 Standard from Sony.

**Phases of Development**

  * Choose an LVDS chip-set from a major IC manufacturer (Maxim, TI, AD, etc.)
  * Design alpha PCB's for 1 Channel Receive / Send
  * Test performance of alpha PCB
  * Beta PCB Design / Build, 2 channels Receive / Send
  * Test performance of Beta PCB
  * First Release Candidate PCB Design / Build
  * Test Performance of Release Candidate
  * If Jitter > 4" I2S, Build RC 2, if Jitter < 4" I2S RC 1 becomes release 1.0

**Minimum Specification of Release 1.0**

  * up to 24.576Mhz
  * 1-8 bit depth
  * Jitter not to exceed I2S specification
  * 2 channels minimum of 6/8-bit, ideally 8 channels of 6-bit. would allow 16-48 channels of 1-bit.
  * Cat7 S/STP (Screened Shielded Twisted Pair), idealy 4 pairs or less (ethernet).
  * serializer / deserializer will be needed for ethernet (12bits for 2 channels of 6-bit, 48bits for 8-channels of 6-bit or 6 channels of 8-bit) will need evaluation of jitter.