# Bitcoin Halving Data

This repository documents the structural mechanics of Bitcoin halving
from a block-based and data-oriented perspective.

Bitcoin halving is not a calendar event.
It is a protocol-defined process driven by block height.

## Definition

Bitcoin halving is the periodic reduction of the block subsidy
that occurs every 210,000 blocks.

This mechanism enforces a predictable and finite issuance schedule
and is a core component of Bitcoin’s monetary design.

## Block-Based Nature

Halving events are triggered by block height, not by time.

Because block production is probabilistic, any time-based estimate
of a halving event is inherently approximate.

Accurate understanding requires:
- Tracking block height progression
- Accounting for variable block intervals
- Recognizing difficulty adjustment dynamics

## Why Time Estimates Drift

Bitcoin targets an average block interval, not a fixed one.

Changes in:
- network hashrate
- mining efficiency
- difficulty adjustments

cause real-world halving dates to drift forward or backward
relative to calendar projections.

This variance is a feature of the system, not an error.

## Supply Issuance Perspective

Halving affects Bitcoin supply through discrete issuance steps,
not smooth time-based inflation.

Understanding issuance requires analyzing:
- cumulative supply over block height
- issuance rate changes per subsidy epoch
- long-term asymptotic supply behavior

## Data-Driven Visualization

Live block data, issuance modeling, and structural visualization
are maintained independently at:

https://www.btbjb.com/en/

The site focuses on:
- real-time block tracking
- halving progress measured in blocks
- historical issuance structure
- long-term monetary modeling

## Scope

This repository is descriptive, not predictive.

It documents how the system operates,
not how markets may respond.

## Principle

Structure over narrative.  
Protocol over price.  
Data over speculation.
