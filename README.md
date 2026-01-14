Dataset Description
The dataset contains employee-related information including:
   Employee ID
   Age
   Gender
   Department
   Job Role
   Education Field
   Monthly Salary
   Years at Company
   Attrition Status


Data Cleaning & Preparation
   The following steps were performed:
     Removed duplicate employee records
     Handled missing values
     Standardized salary ranges
     Categorized age groups and salary slabs
     Verified data accuracy and consistency
      KPIs & Calculations Used

Below are the key metrics and formulas used to build the dashboard:

1. Total Employee Count

      Formula (Excel):
      =COUNTA(EmployeeID)

2. Attrition Count

      Formula (Excel):
      =COUNTIF(Attrition,"Yes")

3. Attrition Rate (%)

        Formula (Excel):
        =Attrition_Count / Total_Employees * 100

4. Average Age

        Formula (Excel):
        =AVERAGE(Age)

5. Average Salary

    Formula (Excel):
    =AVERAGE(MonthlySalary)

6. Average Years at Company

        Formula (Excel):
        =AVERAGE(YearsAtCompany)


Categorization Formulas Used
Age Group Classification
            =IF(Age<=25,"18-25",
             IF(Age<=35,"26-35",
             IF(Age<=45,"36-45",
             IF(Age<=55,"46-55","55+"))))



Salary Slab Classification
        =IF(MonthlySalary<=5000,"Up to 5K",
         IF(MonthlySalary<=10000,"5K-10K",
         IF(MonthlySalary<=15000,"10K-15K","15K+")))    


Dashboard Visuals Created
  KPI Cards (Employee Count, Attrition Rate, Average Salary)
  Bar Charts (Attrition by Age, Salary, Job Role)
  Pie Chart (Attrition by Education)
  Line Chart (Attrition by Years at Company)
  Gender Distribution
  Tools Used
  Microsoft Excel / Power BI
  Pivot Tables
  Pivot Charts
  Conditional Formatting
  Data Validation Techniques

Key Learnings
  Hands-on experience with HR data analysis
  Practical understanding of attrition metrics
  Improved skills in data cleaning, transformation, and visualization
  Ability to convert raw HR data into actionable business insights


# HR-ANALYTICS-DASHBOARD
HR Analytics Dashboard analyzing employee attrition trends across age, salary, education, job role, and experience using data visualization.
