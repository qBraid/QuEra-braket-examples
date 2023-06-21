# QuEra-braket-examples
Public repository for examples created by QuEra.

[<img src="https://qbraid-static.s3.amazonaws.com/logos/Launch_on_qBraid_white.png" width="150">](https://account.qbraid.com?gitHubUrl=https://github.com/qBraid/QuEra-braket-examples.git)

## Using these examples on qBraid

### Amazon Braket examples

- Launch https://lab.qbraid.com, or click the **Launch on qBraid** button above.
- [Install](https://docs.qbraid.com/en/latest/lab/environments.html#install-environment) and [activate](https://docs.qbraid.com/en/latest/lab/notebooks.html#add-remove-kernels) the **Amazon Braket** environment
- [Set notebook kernel](https://docs.qbraid.com/en/latest/lab/notebooks.html#switch-notebook-kernel) (top-right) to ``Python 3 [Braket]``
- [Enable qBraid Quantum Jobs](https://docs.qbraid.com/en/latest/lab/quantumjobs.html#quantum-jobs) from inside the notebook with the following command:

```
!qbraid jobs enable amazon_braket
```

### Bloqade examples

- Launch the dedicated Bloqade qBraid Lab image
- To use Bloqade with Julia:
    - Open notebook and set kernel to ``Julia 1.8.5``
- To use Bloqade with Python:
    - Activate the **Bloqade** environment
    - Open notebook and set kernel to ``Python 3 [Bloqade]``

