# Microsoft Azure LogicApps Workshop - Data processing

## Exercise 1 : Filtering data

1. Crate Logic App that is triggered by HTTP GET.
2. Crate **Parse JSON** action from **Data Operations** connector. Use 'sample payload to generate schema' function to generate schema based on following [file](Sample.json)
3. Save result to variable named json.
   
   ![Variable](_img/Variable.png)]

4. Filter colors from json array that start with "b" using **Filter array** activity.
   
   ![StartsWith](_img/StartsWith.png)

5. Save result to HTML table and send with Email.
   
   ![HTML](_img/HTML.png)

## Exercise 2 : Transform data

1. Create parallel branch under variable declaration.
2. Use **Select** activity to perform data transformation.
   
   ![Select](_img/Select.png)

3. Save result to CSV file.
   
   ![CSV](_img/CSV.png)

4. Send both HTML and CSV (as an attachment) via email.
   
   ![Send](_img/Send.png)

## [UP](./../README.md)
