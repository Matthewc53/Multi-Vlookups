# Multi-Vlookups
using python to hard code multiple excel vlookups
1. Read in source file and edge output
![image](https://github.com/Matthewc53/Multi-Vlookups/assets/31051617/1dc5accb-455f-4022-8bfb-4b8e3ace8ee6)

2. Create slice for each carrier requested
![image](https://github.com/Matthewc53/Multi-Vlookups/assets/31051617/bf41ae07-678a-4597-93e1-c35019c4559e)

3. Perform right join to combine the two data files(We are using the Primary Reference column as out Unique identifier)
![image](https://github.com/Matthewc53/Multi-Vlookups/assets/31051617/42ccfb00-8036-4b19-8044-ee2b8ce523b0)

4. Add in new linehaul column for each carrier
![image](https://github.com/Matthewc53/Multi-Vlookups/assets/31051617/1eff8fd4-a4fb-4d2c-be0c-8abe692b3dbc)

5. Select only the columns we want in our output
![image](https://github.com/Matthewc53/Multi-Vlookups/assets/31051617/34d8f9c0-8e93-469b-aa06-81ab92d758b4)

6. combine all carrier selections into one file
![image](https://github.com/Matthewc53/Multi-Vlookups/assets/31051617/2f5f1ac8-7395-4653-a2e6-0f4f4020a258)

7. output to excel file to copy paste directly into source file(it will output to the same directory you opened python in)
![image](https://github.com/Matthewc53/Multi-Vlookups/assets/31051617/c845fc62-2615-440f-8fbf-0dbc8bc13f82)

