
|  Framework  | Pipeline type | Method of optimization |             Input data             |          Scale          |       Features       | Source |
|-------------|---------------|------------------------|------------------------------------|-------------------------|----------------------|--------|
| TPOT        | Variable      | GP                     | Tabular                            | Multiprocessing, Rapids | Code generation      | https://github.com/EpistasisLab/tpot |
| H2O         | Fixed         | Grid Search            | Tabular, Texts                     | Hybrid                  | -                    | https://github.com/h2oai/h2o-3 |
| AutoSklearn | Fixed         | SMAC                   | Tabular                            | -                       | -                    | https://github.com/automl/auto-sklearn |
| ATM         | Fixed         | BTB                    | Tabular                            | Hybrid                  | -                    | https://github.com/HDI-Project/ATM |
| FEDOT       | Variable      | GP + hyperopt          | Tabular, Timeseries, Images, Texts | -                       | Composite pipelines  | https://github.com/nccr-itmo/FEDOT |
| AutoGluon   | Fixed         | Fixed Defaults         | Tabular, Images, Texts             | -                       | NAS, AWS integration | https://github.com/awslabs/autogluon |
| LAMA        | Fixed         | Optuna                 | Tabular, Texts                     | MLSpace                 | Profiling            | https://github.com/sberbank-ai-lab/LightAutoML |
| NNI         | Fixed         | Bayes                  | Tabular, Images                    | Hybrid, Kubernetes      | NAS, WebUI           | https://github.com/microsoft/nni |

