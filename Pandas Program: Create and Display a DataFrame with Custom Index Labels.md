# Pandas Program:  To write a CSV file from a Python list.
## 🎯 Aim
To write a list of records into a CSV file with a header using Python, and then read it back.


## 🧠 Algorithm
1.Import the csv module.

2.Define the header and the list of rows.

3.Open a CSV file in write mode and write the header and rows using csv.writer.

4.Open the CSV file in read mode to verify content.

5.Read and print the header and rows using csv.reader.




## 💻 Program :
```.py
import csv
data = eval(input())

header = ['Name', 'Age', 'Site', 'Location']


with open("write_to_csv.csv", 'w', newline='') as file:
    writer = csv.writer(file)
    writer.writerow(header)  # Writing the header
    writer.writerows(data)  # Writing the data rows

rows = []
```

## Output :
![Screenshot 2025-04-29 180652](https://github.com/user-attachments/assets/f68f4931-bbac-465d-bc12-e201dbfda605)

![image](https://github.com/user-attachments/assets/189ff128-d33c-4d4d-a609-335e72dc9dd0)

## Result :
The program successfully writes the list to a CSV file with the given header and reads it back correctly.









