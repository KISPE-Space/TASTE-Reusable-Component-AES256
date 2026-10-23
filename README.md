---
title: taste-AES256
created: '2026-10-23T07:40:56.593Z'
modified: '2026-10-23T07:54:35.184Z'
---

# taste-AES256
TASTE AES-256 component based on tiny-AES, developed as a part of "Model-Based Execution Platform for Space Applications" project (contract 4000146882/24/NL/KK) financed by the European Space Agency.

This repository contains a TASTE component that wraps the tiny-AES library (https://github.com/kokke/tiny-AES-c). The tiny-AES library has been configured to use a 256-bit key and implement Electronic Cook Book (ECB) mode of operation only. Three TASTE test projects are also provided for Linux, SAMV71 and SAMRH71 targets. The component is ready for (re)use within ESA's [TASTE MBSE Toolchain](https://taste.tools/). The component needs an user provided bridge between the component and the rest of TASTE system to properly handle ASN.1 data types.
