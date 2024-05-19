# Analysing Healthcare Dataset using SQL

- SELECT COUNT(*) FROM Healthcare;
   ![image](./Public/Count.png)
  
- select max(age) as Maximum_Age from Healthcare;
  ![image](./Public/Maximum_Age.png)

- Select round(avg(age),0) as Average_Age from Healthcare;
   ![image](./Public/Avg_Age.png)

- SELECT AGE, COUNT(AGE) AS Total
FROM Healthcare
GROUP BY age
ORDER BY AGE DESC;
<img width="379" alt="image" src="https://github.com/ShivamNIT/Data-Analysis-SQL/assets/97026504/a95500f9-a680-4fc6-936d-73fdd450bcbb">

- SELECT AGE, COUNT(AGE) AS Total
FROM Healthcare
GROUP BY age
ORDER BY Total DESC,age DESC;
![image](./Public/Age_Count2.png)

