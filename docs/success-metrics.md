# Success Metrics and KPI Targets

The following KPIs define MVP success criteria and must be tracked from day one.

## KPI Targets

1. **Forecast accuracy improvement vs baseline**
   - **Target:** Improve forecast accuracy by **at least 15%** versus the agreed pre-portal baseline model within two full budget cycles post go-live.
   - **Measurement:** MAPE (or selected forecast error metric) compared against historical baseline runs.

2. **Budget-cycle time reduction**
   - **Target:** Reduce end-to-end budget cycle duration by **30%** versus the current process baseline by the second cycle after launch.
   - **Measurement:** Calendar days from kickoff to final approved budget.

3. **% department requests submitted via portal**
   - **Target:** Reach **90%+** of department budget/forecast requests submitted through the portal (not email/spreadsheet) within 90 days of MVP go-live.
   - **Measurement:** Portal-submitted request count divided by total requests.

4. **Time-to-scenario analysis turnaround**
   - **Target:** Deliver standard scenario analysis results within **24 hours** for 85% of requests by the end of the first quarter post-launch.
   - **Measurement:** Time from scenario request submission to published scenario output.

5. **Override frequency and approval latency**
   - **Target:**
     - Keep manual override rate at or below **10%** of generated recommendations.
     - Achieve median override approval latency of **< 2 business days**.
   - **Measurement:** Override event logs and approval workflow timestamps.

6. **User adoption by persona**
   - **Target:** Within 90 days of MVP go-live:
     - Finance Analysts: **85% weekly active usage**
     - Department Managers: **75% monthly active usage**
     - Executives/Approvers: **70% monthly active usage**
   - **Measurement:** Persona-mapped active users divided by total enabled users per persona.

## Dashboard Instrumentation Requirement

Dashboard instrumentation for **each KPI above is required by MVP go-live**. Instrumentation must include:

- KPI definition metadata (owner, formula, baseline, target, and refresh cadence).
- Event/log capture needed to compute KPI numerators and denominators.
- Role-based dashboard views with trend lines and target-threshold indicators.
- Data quality checks and alerting for stale/missing KPI inputs.
- Auditability of KPI calculations and source event lineage.
