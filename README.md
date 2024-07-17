##**PyPhisher Phishing Attack Documentation**

This repository documents my use of the PyPhisher tool to simulate phishing attacks on my own system. I utilized the Gmail and Instagram options provided by PyPhisher.

This README includes all the steps from installation to execution, along with screenshots of each step.

Installation
Follow these steps to set up PyPhisher:
  git clone https://github.com/KasRoudra/PyPhisher.git
  
  cd PyPhisher
  
  pip install -r requirements.txt

If in case you recieve an error message prompting 'File is not a zip file!', NO WORRIES!

 git clone https://gitlab.com/KasRoudra/PyPhisher.git

  cd PyPhisher
  
  pip install -r requirements.txt

##**I peformed 2 attacks on my own system:**
    
  ##1: Gmail Phishing Attack
  
  Run PyPhisher:
  
  python pyphisher.py
  
  Select the Gmail Phishing Template:
  
  From the menu, select the Gmail option by entering its corresponding number. 
  
  Enter Shadow URL:
  
  You will be prompted to enter a shadow URL. For Gmail, enter the actual Gmail login URL:
  
  Enter Redirection URL:
  
  Enter the redirection URL, which is also the Gmail login URL:
  
  Generate the Phishing URL:
  
  PyPhisher will generate a phishing URL. The output will look something like this:

  Share the Phishing URL:
  
  Copy the generated URL and access it on your own system. Monitor the terminal for captured credentials.
    


