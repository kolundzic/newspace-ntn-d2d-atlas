# RTT and Propagation

## 1. Propagation baseline
Propagation delay is bounded by the speed of light; LEO is significantly lower than GEO, but remains non-trivial for real-time services.

## 2. RTT decomposition (conceptual)
RTT ≈ (uplink propagation + downlink propagation) + processing + routing

## 3. Implication
- messaging tolerates intermittent windows and higher variance,
- voice/data require stricter continuity and latency distributions.

## 4. References (starter)
- Dragorad Milovanović: New Space SatCom / NTN&D2D (project page)
