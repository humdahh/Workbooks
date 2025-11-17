# ER Dashboard (Tableau)

A Tableau-based Emergency Room (ER) dashboard built using realistic, synthetic data. The dashboard visualizes ER visits and operational metrics to help understand patient volumes, wait times, satisfaction, and referral patterns.

## Key Views

- **Overview metrics**: Total number of ER patients over a selected time range.
- **Demographics**: Patient counts stratified by gender and age groups.
- **Operational metrics**: Average wait time in the ER and patient satisfaction score (survey-based).
- **Weekly heat map**: Displays the busiest times in the ER across days of the week and hours of the day.
- **Race distribution**: Bar chart showing patient race breakdown.
- **Department referrals**: Bar chart showing which departments patients were referred to from the ER.

## Data

- The dashboard uses realistic but synthetic (fake) data to protect privacy.
- Typical fields included:
  - `patient_id` (synthetic)
  - `visit_datetime`
  - `age`
  - `gender`
  - `race`
  - `department_referred_to`
  - `wait_time_minutes`
  - `satisfaction_score` (e.g., 1-5)
  - `arrival_mode` (e.g., walk-in, ambulance)

*If you plan to connect real data, remove any personally identifiable information (PII) and follow applicable privacy regulations.*

## Files

- Place your Tableau workbook (`.twb` or `.twbx`) in the repository (example: `/workbook/ER_Dashboard.twbx` or `/docs/ER_Dashboard.twbx`).
- Optionally include screenshots in `/docs/images/` (example: `docs/images/overview.png`, `docs/images/heatmap.png`).

## How to Open the Dashboard

1. **Tableau Desktop or Tableau Reader**: Open the `.twbx` or `.twb` file directly.
2. **Tableau Public**: If you publish the workbook there, link the Tableau Public URL in this README.
3. **Static Previews**: View exported PNGs or PDF files located in `/docs/images` or `/docs/exports`.

## Usage / Notes

- Use filters to change the date range, age groups, or gender bins.
- Hover over marks in charts for tooltips with detailed values.
- The heat map uses weekday and hour to highlight peak demand windows—useful for staffing decisions.
- Satisfaction score is computed as the mean of survey scores; consider showing the median and distribution for fuller context.

## Suggested Enhancements

- Add role-based dashboards for clinicians vs administrators.
- Add trend forecasting for patient volumes.
- Integrate hospital systems (HL7/FHIR) using a secure ETL pipeline (for real deployments).
- Add export options for CSV/PDF reports.

## Credits

- Built with Tableau
- Synthetic data created for demonstration purposes

## License

Choose a license for the repository (MIT recommended) and update this README and add a LICENSE file accordingly.

## Contact

For questions or contributions, open an issue or contact [@humdahh](https://github.com/humdahh) on GitHub.
