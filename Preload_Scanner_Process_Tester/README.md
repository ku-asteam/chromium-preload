# Preload_Scanner_Process_Tester

Preload Scanner Process Tester for checking flow in preload process

## Introduction

This software is a implementation of aSTEAM Project (Next-Generation Information Computing Development Program through the National Research Foundation of Korea (NRF) funded by the Ministry of Science and ICT). The function of this software is to check preload processs flow

## Requirements and Dependencies

- ubuntu 16.04 LTS
- [Chromium source and build](https://chromium.googlesource.com/chromium/src/+/master/docs/linux/build_instructions.md)
- patch sequence : chromium structure tester -> preload scanner process tester -> script priority change

## Instructions

- download [Chromium](https://chromium.googlesource.com/chromium/src/+/master/docs/linux/build_instructions.md) first, then build
- patch -pNUM < 'patch file name' (follow sequece written in requirements)
