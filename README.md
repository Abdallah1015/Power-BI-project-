# WhatsApp Group Analysis with Power BI

This project analyzes a WhatsApp group chat dataset using Power BI to uncover insights about user activity, message content, and interaction patterns.

## Dataset

The dataset includes the following columns:
- **Date:** The date when the message was sent.
- **Time:** The time when the message was sent.
- **User:** The name of the user who sent the message.
- **Message:** The content of the message.

## Goals

The main objectives of this analysis are:
1. Identify the most and least active users.
2. Determine the times of day and days of the week when the group is most active.
4. Visualize user interactions and response times.

## Steps

### 1. Data Preparation
- Import the dataset into Notepad and use semi colon to separate them then save and import into power BI.
- Clean and format the data using Power Query Editor.

### 2. Calculations and Measures
- Create measures to count messages and identify active users.
- Extract additional insights such as the day of the week from the Date column.

### 3. Visualization
- Create various charts and visuals to represent the data:
  - Bar chart for user activity.
  - Donut chart for total messages by year.
  - Line chart for activity over time.
  - Heat map for total messages by time.

### 4. Interactive Reports
- Combine visuals into an interactive report.
- Use slicers to filter data by date.

## How to Use

### Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/desktop/)

### Steps to Run the Analysis
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/whatsapp-analysis.git
   ```
2. **Open Power BI:**
   - Launch Power BI Desktop.
3. **Load the Data:**
   - Open the provided Power BI file (`whatsapp_analysis.pbix`) in Power BI Desktop.
4. **Explore the Report:**
   - Navigate through the different report pages to explore the insights.
   - Use slicers and filters to interact with the data.

## Visualizations

### User Activity
- **Bar Chart:** Shows the number of messages sent by each user.

### Temporal Analysis
- **Line Chart:** Shows message trends over time (daily, weekly, monthly).
- **Heat Map:** Visualizes activity by hour and day.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

## Acknowledgments
- Thanks to the Power BI community for their helpful resources and tutorials.
