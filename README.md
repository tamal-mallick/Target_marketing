Portuguese banking institution used direct marketing campaign to sell term deposits to their customers. The campaign was mostly based on phone calls and the dataset stores general information about customers, details of contacts made with them and the output variable y which indicates whether a term deposit was subscribed to by the customer or not. There are two datasets –
1. Portuguese Bank Data – TRAIN, and
2. Portuguese Bank Data - TEST

Attribute Information:
Input variables:

bank client data:
1 - age (numeric)
2 - job : type of job (categorical: 'admin.', 'unknown', 'unemployed', 'management', 'housemaid', 'entrepreneur', 'student', 'blue-collar', 'self-employed', 'retired', 'technician', 'services')
3 - marital : marital status (categorical: 'married', 'divorced', 'single'; note: 'divorced' means divorced or widowed)
4 - education (categorical: 'unknown', 'secondary', 'primary', 'tertiary')
5 - default: has credit default? (binary/flag: 'yes', 'no')
6 - balance: average yearly balance, in euros (numeric)
7 - housing: has housing loan? (binary/flag: 'yes', 'no')
8 - loan: has personal loan? (binary/flag: 'yes', 'no')
related with the last contact of the current campaign:
9 - contact: contact communication type (categorical: 'unknown', 'telephone', 'cellular')
10 - day: last contact day of the month (numeric)
11 - month: last contact month of the year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
12 - duration: last contact duration, in seconds (numeric)
other attributes:
13 - campaign: number of contacts performed during this campaign and for this client (numeric, includes
last contact)
14 - pdays: number of days since the last contact with the client from a previous marketing campaign
(numeric, -1 means client was not previously contacted)
15 - previous: number of contacts performed before this campaign and for this client (numeric)
16 - poutcome: outcome of the previous marketing campaign (categorical: 'unknown', 'other', 'failure',
'success')

Dataset: http://archive.ics.uci.edu/ml/datasets/Bank+Marketing
