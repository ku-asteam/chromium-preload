# Chromium preload

This is a repository for chromium preload function 

## Introduction

This software is a implementation of aSTEAM Project (Next-Generation Information Computing Development Program through the National Research Foundation of Korea (NRF) funded by the Ministry of Science and ICT). 
The repository is consist of 3 patches. 
- Chromium_Structure_Tester patch is is to check some data in structure using in chromium
- Preload_Scanner_Process_Tester patch is to check preload processs flow
- Script_Priority_change patch is to change priority of requesting script files to be preloaded

## Requirements and Dependencies

- ubuntu 16.04 LTS
- [Chromium source and build](https://chromium.googlesource.com/chromium/src/+/master/docs/linux/build_instructions.md)
- patch sequence : chromium structure tester -> preload scanner process tester -> script priority change

## Instructions

- download [Chromium](https://chromium.googlesource.com/chromium/src/+/master/docs/linux/build_instructions.md) first, then build
- patch -pNUM < 'patch file name' (follow sequece written in requirements)
