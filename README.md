# Behavioral Trap, Perturbation Trigger: Integrated Adversarial Scenarios for Autonomous Driving

## Visualize Scenario

```
safety-critical scenarios/
│
├── scenario1
    ├── RAW.gif
    ├── PGD.GIF
    ├── CAT.GIF
    ├── PDIAG.gif
├── scenario2
├── scenario3
├── ......
```

Each scenario includes the following visualizations:

- **RAW.gif**: Baseline replay of the original, unmodified scenario.
- **PGD.gif**: Digital adversarial attack generate safety-critical scenario.
- **CAT.gif**: Physical adversarial attack generate safety-critical scenario.
- **PDIAG.gif**: Safety-critical scenario generated via the **PDIAG** method.

## Data Preparation

Download the pre-trained trajectory prediction model DenseTNT and pre-trained adversarial policy which is used in Perturbation Trigger phase of PDIAG in https://drive.google.com/drive/folders/10Ns2Fd5SfV7DLJE79lrpSNXtgncrUhPV?usp=sharing