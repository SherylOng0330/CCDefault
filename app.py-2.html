#!/usr/bin/env python
# coding: utf-8

# In[1]:


from flask import Flask


# In[2]:


app = Flask(__name__)


# In[3]:


from flask import request, render_template
from keras.models import load_model

@app.route("/", methods=["GET", "POST"])
def index():
    if request.method=="POST":
        Income = request.form.get("Income")
        Age = request.form.get("Age")
        Loan = request.form.get("Loan")
        print(Income, Age, Loan)
        model = load_model("CCDefault")

# account for normalisation using formula (x - x mininum)/(x maximum - x minimum)
        pred = model.predict([[float((float(Income)-20014.48947)/(69995.68558-20014.48947)), float((float(Age)-18.05518851)/(63.97179584-18.05518851)), float((float(Loan)-1.377629593)/(13766.05124-1.377629593))]])
        print(pred)
        s = "The predicted credit card default score is : " + str(pred)
        return(render_template("index.html", result=s))
    else: 
        return(render_template("index.html", result="2"))


# In[ ]:


if __name__=="__main__":
    app.run()


# In[ ]:




