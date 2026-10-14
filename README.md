# Quant Portfolio Lab
### Quantitative Finance · Machine Learning · CI/CD

**An end-to-end quantitative research and engineering portfolio project.**

Quant Portfolio Lab integrates financial econometrics, portfolio optimization, risk analysis, machine learning, and automated software validation in a modular Python workflow.

## Research Objective

Evaluate equity portfolios through complementary approaches: expected returns, conditional volatility, optimal allocation, downside risk, and out-of-sample validation. The project also demonstrates reproducible development practices through Git and GitHub Actions.

## Quantitative Methodologies

| Component | Methodology |
|---|---|
| Market risk | CAPM and IPC market beta |
| Conditional volatility | GARCH(1,1), Student-t innovations |
| Portfolio construction | Minimum variance and maximum Sharpe |
| Scenario analysis | 10,000 historical bootstrap simulations |
| Tail risk | VaR and Expected Shortfall, 95% and 99% |
| Validation | Rolling VaR backtesting and Kupiec coverage test |
| Machine learning | Random Forest forecasting five-session realized volatility |

## Selected Results

The research universe contains Bimbo, Grupo México, and Walmex.

| Metric | Minimum variance | Maximum Sharpe |
|---|---:|---:|
| Historical annual return | 13.69% | 15.03% |
| Historical annual volatility | 21.95% | 34.16% |
| Daily VaR 95% | 2.203% | 3.280% |
| Daily Expected Shortfall 95% | 2.912% | 4.454% |

The maximum-Sharpe solution is concentrated in Bimbo. These figures are historical or bootstrap-based estimates, not guaranteed future performance.

## CI/CD and Software Quality

GitHub Actions runs automated tests using synthetic financial data, independent of private historical files.

**Latest documented validation:** 6 tests passed, 0 failures, 0 errors.

Coverage includes financial calculations, Markowitz constraints, Monte Carlo, VaR/ES, CAPM, GARCH, and Random Forest.

Experiment metadata is captured locally in structured JSON. CI evidence includes dependency versions and the evaluated Git commit.

## Evidence and Presentation

Financial figures, project architecture, and screenshots of the GitHub Actions CI dashboard will be added to this public showcase. The underlying implementation remains private.

## Source Code Access

The complete Python implementation is maintained in a private repository. Technical reviewers and recruiters may request a controlled review through LinkedIn or an agreed professional contact channel. Access is granted individually at the owner's discretion.

## Scope and Limitations

This is an analytical research and portfolio demonstration, not investment advice or a production investment platform. Institutional concentration constraints, additional statistical diagnostics, market stress integration, production model monitoring, and deployment remain future work.

## Documentación del proyecto

**Presentación técnica y resultados cuantitativos**

Consulta el documento de Quant Portfolio Lab, que incluye modelos financieros, optimización de carteras, simulación de riesgos y validación.

[Ver documento de Quant Portfolio Lab](presentacion/Quant%20Portfolio%20Lab%20_%20Reporte.pdf)

## Validación automatizada

El proyecto incorpora GitHub Actions y un CI Dashboard con seis pruebas aprobadas, cero fallas y cero errores, utilizando datos sintéticos.

El código fuente completo se conserva en un repositorio privado y su revisión puede solicitarse mediante contacto profesional.
