# BankManagerProject
An Bank Management Related data prediction, on deposite prediction with individual.
The data inside the data is shown follow: 
1.	age (numeric)
2.	job: type of job (categorical: 'admin.','blue-collar', 'entrepreneur', 'housemaid', 'management', 'retired','self-employed', 'services', 'student', 'technician', 'unemployed', 'unknown')
3.	marital: marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)
4.	education: (categorical: 'basic.4y', 'basic.6y', 'basic.9y', 'high.school', 'illiterate', 'professional.course', 'university.degree', 'unknown')
5.	housing: has housing loan? (categorical: 'no','yes','unknown')
6.	loan: has personal loan? (categorical: 'no','yes','unknown')
7.	contact: contact communication type (categorical: 'cellular','telephone')
8.	month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
9.	day_of_week: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')
10.	duration: last contact duration, in seconds (numeric).
11.	campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
12.	pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
13.	poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')
14.	nr.employed: number of employees - quarterly indicator (numeric)

Objective: Subscribed - has the client subscribed a term deposit? (binary: 'yes','no')


All the python packages required by the project: 
      Matplotlib
      Seaborn 
      Numpy
      Pandas
      Scipy

  a Requiemnt file has also been uploaded, install the virtual env package using: 

    $ pip install virtualenv
    $ virtualenv -p [path] [VM Name]
    (* Please use Python 3 and not Python 2!)
    
  And then activate that environment and install from your requirements.txt which you have included in your version control:
    
    $ source [path]/bin/activate

    (VMNAME) $ pip install -r requirements.txt





