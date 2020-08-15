We are building a machine learning model for spam SMS message classification, then create an API for the model, using Flask.

I used Naive Bayes classifiers for e-mail filtering. They typically use bag of words features to identify spam e-mail.

We create a folder for this project called deploying spam filter , this is the directory tree inside the folder.

spam.csv
app.py
templates/
        home.html
        result.html
static/
        style.css


The sub-directory templates is the directory in which Flask will look for static HTML files for rendering in the web browser

Once you have done all of the above, you can start running the API by either double click appy.py , or executing the command from the Terminal:

cd deploying spam filter
python app.py

Now you could open a web browser and navigate to http://127.0.0.1:5000/, we would see a website page.