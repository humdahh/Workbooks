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

This dashboard uses the following data source.

- The dashboard uses real world fake data to protect privacy.
- Primary source: 'Hospital ER.csv' 
  Source: data.world
  Time Period: April 2019 - October 2020
- Key Variables:
  - `patient_id`
  - `visit_datetime`
  - `age`
  - `gender`
  - `race`
  - `department_referred_to`
  - `wait_time_minutes`
  - `satisfaction_score` (e.g., 1-10)


## How to Open the Dashboard

### Option 1: Download and Open
- [Download ER Dashboard Workbook](workbook/ER_Dashboard.twb)
- Open in Tableau Desktop

### Option 2: View Screenshots
- [Dashboard Overview](docs/images/DB%20Overview.png)
- [View all dashboard screenshots](docs/images/)


## Usage / Notes

- Use filters to change the date range, age groups, or gender bins.
- Hover over marks in charts for tooltips with detailed values.
- The heat map uses weekday and hour to highlight peak demand windows—useful for staffing decisions.
- Satisfaction score is computed as the mean of survey scores; consider showing the median and distribution for fuller context.


## Credits

- Built with Tableau
- Synthetic data created for demonstration purposes (From Real World Fake Data)


## Contact

For questions or contributions, open an issue or contact [@humdahh](https://github.com/humdahh) on GitHub.
