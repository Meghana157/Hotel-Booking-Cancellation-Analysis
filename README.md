# Hotel Booking Cancellation Analysis

## Project Overview
This project focuses on analyzing the factors contributing to hotel booking cancellations and providing actionable insights to reduce cancellation rates for two hotel types: **City Hotel** and **Resort Hotel**. High cancellation rates negatively impact revenue and operational efficiency. By identifying key trends and variables influencing cancellations, this analysis aims to help hotels optimize their pricing strategies, marketing efforts, and service quality.

## Business Problem
City Hotel and Resort Hotel have been facing challenges due to high cancellation rates. These cancellations result in reduced revenue and inefficient room utilization. The primary goal of this analysis is to identify the reasons for cancellations and provide business recommendations to mitigate their impact.

## Assumptions
1. No unusual occurrences between 2015 and 2017 significantly impacted the dataset.
2. The data remains relevant for crafting effective strategies.
3. Implementing suggested techniques will not result in unforeseen challenges.
4. Hotels are not currently applying the proposed solutions.
5. Cancellations have the most significant impact on revenue generation.
6. Cancellations leave rooms vacant for the duration of the booking.
7. Clients typically cancel reservations the same year they are made.

## Research Questions
- What variables affect hotel reservation cancellations?
- How can hotels reduce reservation cancellations?
- How can this analysis assist hotels in making pricing and promotional decisions?

## Hypotheses
1. **Higher prices lead to more cancellations.**
2. **Longer waiting lists correlate with higher cancellation rates.**
3. **Most clients book via offline travel agents.**

## Analysis and Findings
1. **Cancellation Percentage**: 
   - 37% of reservations are cancelled, significantly impacting revenue.
   - The remaining 63% are successfully retained.

2. **Hotel Type Comparison**:
   - City Hotels have more bookings compared to Resort Hotels, possibly due to cost differences.

3. **Average Daily Rate (ADR)**:
   - City Hotels generally have lower ADR than Resort Hotels, but rates increase during weekends and holidays.

4. **Monthly Reservations**:
   - August has the highest number of confirmed and cancelled reservations.
   - January experiences the highest cancellation rate.

5. **Impact of Price on Cancellations**:
   - Cancellations are more frequent when ADR is higher, confirming the hypothesis.

6. **Country-wise Cancellations**:
   - **Portugal** has the highest number of cancellations.

7. **Reservation Sources**:
   - 46% of bookings come from online travel agents.
   - 27% of bookings come from groups.
   - Direct bookings constitute only 4%.

## Recommendations
1. **Pricing Strategy**:
   - Adjust pricing strategies to offer discounts in specific locations and during weekends or holidays.

2. **January Campaigns**:
   - Launch targeted marketing campaigns in January to mitigate high cancellation rates.

3. **Service Quality in Portugal**:
   - Focus on improving service quality and customer experience, especially for guests from Portugal.

4. **Enhanced Offers**:
   - Provide promotional discounts and packages to reduce cancellations during peak months.

## Technologies Used
- **Python**: Data cleaning, exploration, and visualization.
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn.
- **Jupyter Notebook**: For exploratory data analysis.
- **Dataset**: Hotel booking data for City and Resort Hotels (2015–2017).

## Installation
To run this project locally:
1. Clone the repository:  
   git clone https://github.com/your_username/hotel-booking-cancellation-analysis.git
