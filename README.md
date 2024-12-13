# user_engagement_dashboard
# Cooking Order Data Analysis Project


---

## Project Overview

### Objective:
- Analyze customer behavior and preferences.


### Data Sources:
- **UserDetails**: Contains user demographic information.
- **CookingSessions**: Logs of cooking sessions, including session ratings.
- **OrderDetails**: Information about orders, including dish names and ratings.

---

## Steps to Analyze Data

1. **Data Cleaning**:
   - Remove duplicates in all sheets.
   - Ensure consistent date formats in `SessionDate` and `OrderDate` columns.
   - Handle missing values using appropriate techniques.

2. **Data Merging**:
   - Use Power Query in Excel:
     - Merge `CookingSessions` with `UserDetails` on `UserID`.
     - Merge the resulting data with `OrderDetails` on `SessionID`.

3. **Analysis**:
   - **Popular Dishes**:
     - Use a Pivot Table to calculate total orders and average ratings for each dish.


4. **Visualizations**:
   - Bar Chart: Total orders, avg order rating by top dishes.
   - Area chart: Number of sessions by users







