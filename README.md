# Call_centre_analysis
Project Aim:
The aim of the this project is to leverage data visualization to enhance decision-making by identifying key trends and insights from call centre operations. 
This includes:
- Creating a dashboard to analyze call trends over time, providing actionable insights into performance patterns and customer interactions.
- Developing a dashboard focused on churn analysis and customer retention strategies, helping to understand factors contributing to churn and identifying opportunities to   
  improve customer loyalty.
- Through these dashboards, the project seeks to optimize call centre efficiency and improve customer satisfaction.
  ## Tools used
  Power BI - For data manipulation and data cleaning.
  As this project is part of the PWC Power BI simulation, the data provided is already cleaned hence I skipped the data cleaning part.
  ### TASK 1(Dahboard 1):
  - Create a Power BI dashboard for a telecom company to help them understand their customers and improve their services. The dashboard should include important measurements
  (called KPIs) that show how well the company is doing in key areas.
  ## Data description
1. Call Id: A unique identifier for each call made to or from the call centre.
2. Agent: The name or ID of the call centre agent handling the call.
3. Date: The date when the call occurred.
4. Time: The time when the call started.
5. Topic: The main reason or subject of the call (e.g., billing, technical issue, general inquiry).
6. Answered (Y/N): Indicates whether the call was answered by an agent (Y for Yes, N for No).
7. Resolved: A field showing whether the issue raised during the call was resolved (likely a Yes/No or similar value).
8. Speed of Answer in Seconds: The time (in seconds) it took for the call to be answered by an agent.
9. AvgTalkDuration: The average duration (in seconds or minutes) that the agent spent talking during the call.
10. Satisfaction Rating: A score (likely numeric) given by the customer to rate their satisfaction with the call or service provided.
    ## Data manipulation
    Columns added:
    Measures calculated:
    ## Preview of the dashboard created:

    ![image](https://github.com/user-attachments/assets/b2ea2835-ef1d-4b18-86fe-559977a15f94)

### Task 2: Customer Retention and churn analysis 
### Data description 
1. customerID: Unique identifier for each customer.
2. gender: Gender of the customer (e.g., Male, Female).
3. SeniorCitizen: Indicates if the customer is a senior citizen (0 for No, 1 for Yes).
4. Partner: Indicates if the customer has a partner (Yes/No).
5. Dependents: Indicates if the customer has dependents (Yes/No).
6. tenure: Number of months the customer has stayed with the company.
7. PhoneService: Indicates if the customer has a phone service (Yes/No).
8. MultipleLines: Indicates if the customer has multiple phone lines (Yes, No, or No phone service).
9. InternetService: Type of internet service (e.g., DSL, Fiber optic, No).
10. OnlineSecurity: Indicates if the customer has online security service (Yes/No/No internet service).
11. OnlineBackup: Indicates if the customer has online backup service (Yes/No/No internet service).
12. DeviceProtection: Indicates if the customer has device protection (Yes/No/No internet service).
13. TechSupport: Indicates if the customer has tech support service (Yes/No/No internet service).
14. StreamingTV: Indicates if the customer has streaming TV service (Yes/No/No internet service).
15. StreamingMovies: Indicates if the customer has streaming movies service (Yes/No/No internet service).
16. Contract: Type of contract (e.g., Month-to-month, One year, Two year).
17. PaperlessBilling: Indicates if the customer has opted for paperless billing (Yes/No).
18. PaymentMethod: Payment method (e.g., Bank transfer, Credit card, Electronic check, Mailed check).
19. MonthlyCharges: The monthly charges incurred by the customer.
20. TotalCharges: Total charges incurred by the customer to date.
21. numAdminTickets: Number of administrative support tickets raised by the customer.
22. numTechTickets: Number of technical support tickets raised by the customer.
23. Churn: Indicates if the customer has churned (Yes/No).
    ## Data Manipulation
    ### Measures calculated
    ## Preview of the dashboard created:
    
    ![image](https://github.com/user-attachments/assets/8588a539-f1b9-4883-91c5-e62193d9b20c)

    
