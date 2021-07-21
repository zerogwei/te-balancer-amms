# te-balancer-amms
Repository for containing all my working documents for the TE Balancer AMM research group

## NOTE:
Ideally the codebase would reference the balancerv2cad python library found [here](https://github.com/metavisionlabs/balancerv2cad), however I temporarily copied in the codebase with some modifications to particular methods to fit my needs.
I would like to revert back to referencing the library again in the future.

### Data
| Dataset | Description | Source |
|----------|-------------|----------|
| data/Binance_ETHUSDT_minute.csv | 1-Minute granular ETHUSDT pricing history data | http://www.cryptodatadownload.com/data/binance/ |

### Notebooks
| Notebook | Description |
|----------|-------------|
| Math_Challenges.ipynb | Contains 'minimal' python implementation using vanilla, Pandas, Numpy etc. |
| Python_Lib_Example.ipynb | Utilises the balancerv2cad python library to provide an approach to the Challenge math problems and further modeling |
| playground.ipynb | WIP - Playing around with ETL on-chain data ingestion |
| v2_simulation.ipynb | Dynamic Weights adjusting AMMs simulation notebook |