<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/glanceneuro/.github/main/profile/logo-darkmode.png">
  <img src="https://raw.githubusercontent.com/glanceneuro/.github/main/profile/logo.png" alt="GLANCE — Gigabit Low-latency Acquisition for Neuroscience & Closed-loop Experiments" width="680">
</picture>

by the [Kemere Lab](https://kemerelab.com) at [Rice University](https://neuroengineering.rice.edu)

</div>

An open FPGA data-acquisition system for **Intan RHD2000-style neural recording
chips**, built on a **MicroZed** (Xilinx Zynq-7020) with a custom carrier PCB —
up to **256 channels at 30 ksps**, streamed over the network one sample per
datagram for closed-loop latency, with an on-FPGA LFP band and network-controlled
DAC stimulation.

## Repositories

| Repo | What | License |
|---|---|---|
| [**glance-neuro**](https://github.com/glanceneuro/glance-neuro) | Programmable logic, bare-metal firmware, Python host client, docs | MIT |
| [**glance-neuro-plugin**](https://github.com/glanceneuro/glance-neuro-plugin) | Open Ephys source plugin | GPL-3.0 |
| [**glance-neuro-hardware**](https://github.com/glanceneuro/glance-neuro-hardware) | KiCad carrier board | CERN-OHL-P |
