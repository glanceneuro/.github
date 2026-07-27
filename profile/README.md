<table><tr>
<td valign="middle"><img src="https://raw.githubusercontent.com/glanceneuro/.github/main/profile/logo.png" height="60" alt="GLANCE logo"></td>
<td valign="middle">

# GLANCE
**G**igabit **L**ow-latency **A**cquisition for **N**euroscience & **C**losed-loop **E**xperiments

</td>
</tr></table>

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
