# Working with twarc data

Pull this repository to your local machine

In the terminal/console, navigate to your local folder 751-Methods- then

`git pull`

Put the twarc jsonl file you downloaded into the main 751-Methods- folder on your computer.

To make it into a CVS file you can import into Google Sheets:

`./utils/json2csv.py your-file-name.jsonl > your-file-name.csv`

To make it into a Gephi file you can do network analysis with:

`./network.py your-file-name.jsonl your-file-name.gexf --users`

Gephi tutorial (there are many, but here is one): https://www.youtube.com/watch?v=2FqM4gKeNO4
