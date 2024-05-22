# Adrastia Audit Reports

This repository contains the audit reports for Adrastia.

## Audits

### v4

#### v4.4.0 - PID controllers, value & error accumulators, and related contracts
- Date: 09-MAY-2024
- Report: [PID-controller-Zellic.pdf](./09-MAY-2024/PID-controller-Zellic.pdf)
- Scope
  - adrastia-core
    - contracts/accumulators/ValueAndErrorAccumulator.sol
    - contracts/accumulators/proto/truefi/AlocUtilizationAndErrorAccumulator.sol
  - adrastia-periphery
    - contracts/accumulators/proto/truefi/ManagedAlocUtilizationAndErrorAccumulator.sol
    - contracts/rates/controllers/PidController.sol
    - contracts/rates/controllers/ManagedPidController.sol
    - contracts/rates/controllers/proto/truefi/TrueFiAlocPidController.sol
    - contracts/rates/transformers/NegativeErrorScalingTransformer.sol
    - contracts/rates/transformers/PositiveErrorScalingTransformer.sol

#### v4.3.0 - External oracle integration and self price accumulation
- Date: 03-MAY-2024 & 11-MAY-2024
- Reports:
  - adrastia-core: [External-Oracles-Omniscia.pdf](./11-MAY-2024/External-Oracles-Omniscia.pdf)
  - adrastia-periphery: [ManagedAdrastiaPriceAccumulator-Omniscia.pdf](./11-MAY-2024/ManagedAdrastiaPriceAccumulator-Omniscia.pdf)
- Scope
  - adrastia-core
    - contracts/oracles/AbstractOracle.sol
    - contracts/accumulators/AbstractAccumulator.sol
    - contracts/accumulators/proto/adrastia/AdrastiaPriceAccumulator.sol
    - contracts/oracles/views/DiaOracleView.sol
    - contracts/oracles/views/PythOracleView.sol
    - contracts/accumulators/PriceAccumulator.sol
  - adrastia-periphery
    - contracts/accumulators/AccumulatorConfig.sol
    - contracts/accumulators/proto/adrastia/ManagedAdrastiaPriceAccumulator.sol

#### v4.2.0 - Complete coverage
- Date: 12-JAN-2024
- Report: [v4.2-Zellic.pdf](./12-JAN-2024/v4.2-Zellic.pdf)
- Scope
  - adrastia-core: All contracts except external libraries and vendor contracts.
  - adrastia-protocol: All contracts except external libraries and vendor contracts.

### v1

#### v1.0.0 - Initial release
- Date: 12-JUL-2022
- Report: [v1.0-Zokyo_compressed.pdf](./12-JUL-2022/v1.0-Zokyo_compressed.pdf)
- Scope
  - adrastia-core: All contracts except external libraries and vendor contracts.
  - adrastia-protocol: All contracts except external libraries and vendor contracts.

