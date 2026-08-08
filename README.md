# white-rabbit-sync

White Rabbit sub-nanosecond clock synchronization reference design (PTP/gPTP based).

## Overview

Reference implementation of White Rabbit style sub-nanosecond clock synchronization built on top of PTP/gPTP, covering message handling, link delay and asymmetry compensation, and a phase measurement/control loop. Built as a portfolio piece; not derived from any employer or client codebase.

## Planned Features

PTP/gPTP message exchange handling. Link delay and asymmetry compensation. Sub-nanosecond phase detector and digital control loop.

## Architecture

See docs/ARCHITECTURE.md for the design write-up and docs/BLOCK_DIAGRAM.md for the block diagram.

## Repository Structure

docs/ contains architecture and block diagram documentation. src/rtl/ contains SystemVerilog and Verilog source. src/tb/ contains testbenches and the verification environment.

## Status

Work in progress, portfolio reference implementation.

## Tools

SystemVerilog, Verilog, QuestaSim

## License

MIT, see LICENSE
