# PC Hardware Research and Testing

## AMD 9800X3D Clock Behavior Analysis

### Test Configuration
- CPU: AMD 9800X3D
- Testing Tool: OCCT
- Configurations Tested:
  - ECLK Tuning, value was 105
  - PBO with Negative Curve Optimizer

### Findings

#### Clock Stretching Observations with ECLK

During OCCT stress testing with ECLK tuning, potential clock stretching was observed:
- Core Clock vs. Effective Clock delta: ~70MHz at 105 ECLK
- This larger delta suggests potential clock stretching occurring under load
- May indicate the CPU is unable to maintain stable operation at the requested frequency

#### PBO with Negative Curves Performance

When testing with PBO and negative curve optimization:
- Core Clock vs. Effective Clock delta: ≤30MHz
- Much tighter correlation between requested and actual clock speeds
- Suggests more efficient and stable operation

### Analysis

The difference in clock behavior between ECLK and PBO tuning methods indicates that ECLK might be forcing higher frequencies that the CPU cannot fully sustain under load. The smaller delta with PBO negative curves suggests this method might provide more reliable real-world performance despite potentially lower absolute frequency values.

### Methodology Notes

- All testing performed under consistent ambient temperature conditions
- OCCT stress test run for extended periods to ensure stability
- Core and Effective clock speeds monitored using OCCT
- Multiple test runs performed to verify consistency of results

### Future Research

Additional testing planned:
- Adjust from ECLK 105 to ECLK 104 and see if it was due to the requested core clocks. ECLK 105 can hit 5.6+ under the sustained test it was 5.3 roughly all core.
- Adjusting steps of the PBO as well to see if the effective clock size discrepancy adjusts.

---
*Last Updated: January 17, 2025*
