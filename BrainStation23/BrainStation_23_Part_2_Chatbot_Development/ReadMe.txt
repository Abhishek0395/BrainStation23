In the file PostGreSQL.ipynb I have tried to populate a database with the tata dataset.

Here I have constructed 3 tables which are customers,stocks and invoices. 
Customers has 2 variables which are customer_id and country where customer_id is the primary key.
Stocks has 2 variables which are stockcode and description where stockcode is the primary key.
Invoices has 6 variables which are invoiceid,stockcode,quantity,invoicedate,unitprice and customerid.
Here invoiceid is the primary key. customerid and stockcode are the foreign keys.
I used postgresql as the database and tried to connect it with my python code and tried to populate the database with the dataset.However there were
issues when I tried to insert it. So I could  not transfer the dataset to the database.




I have also given a file named chat.py where I have used streamlit to interact with the chatbot. Please use a valid openai key to use it.
Please use the following command to run the chatbot:
python -m streamlit run chat.py --server.runOnSave True
