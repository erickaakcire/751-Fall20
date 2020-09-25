# Working with twarc data

After you have your jsonl file from from a twarc search, clone this repository to your local machine. In terminal/console wherever you want the 751-Fall20 folder to be located:

`git clone [paste the url your copied from the code button above]`

Put the twarc jsonl file you downloaded into the main 751-Fall20 folder on your computer.

To make it into a CVS file you can import into Google Sheets:

`./utils/json2csv.py your-file-name.jsonl > your-file-name.csv`

To make it into a Gephi file you can do network analysis with:

`./network.py your-file-name.jsonl your-file-name.gexf --users`

Gephi tutorial (there are many, but here is one): https://www.youtube.com/watch?v=2FqM4gKeNO4
