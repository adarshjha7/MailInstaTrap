

```markdown
# **PyPhisher Phishing Attack Documentation**

#### This repository documents my use of the PyPhisher tool to simulate phishing attacks on my own system.
 **I utilized the Gmail and Instagram options provided by PyPhisher.**

This README includes all the steps from installation to execution, along with screenshots of each step.

## **Installation**

Follow these steps to set up PyPhisher:

```bash
git clone https://github.com/KasRoudra/PyPhisher.git
cd PyPhisher
pip install -r requirements.txt
```

If you receive an error message prompting 'File is not a zip file!', NO WORRIES!

```bash
git clone https://gitlab.com/KasRoudra/PyPhisher.git
cd PyPhisher
pip install -r requirements.txt
```

## **I performed 2 attacks on my own system:**

### **1: Gmail Phishing Attack**

1. **Run PyPhisher**:
   ```bash
   python pyphisher.py
   ```

2. **Select the Gmail Phishing Template**:
   From the menu, select the Gmail option by entering its corresponding number.

3. **Enter Shadow URL**:
   You will be prompted to enter a shadow URL. For Gmail, enter the actual Gmail login URL:
   ```
   https://accounts.google.com/signin
   ```

4. **Enter Redirection URL**:
   Enter the redirection URL, which is also the Gmail login URL:
   ```
   https://accounts.google.com/signin
   ```
![pyphisher5](https://github.com/user-attachments/assets/6f8de06f-5496-4221-9c1a-4b6c8d04eea6)

5. **Generate the Phishing URL**:
   PyPhisher will generate a phishing URL. The output will look something like this:
   ```
   Phishing URL: http://example.com/gmail
   ```
![gmailpyphisher8](https://github.com/user-attachments/assets/f2ece5af-a5be-4447-8745-50a27ba46384)

6. **Share the Phishing URL**:
   Copy the generated URL and access it on your own system. Monitor the terminal for captured credentials.
   ![Gmailpyphisher0](https://github.com/user-attachments/assets/4349cf72-c54f-4ced-9db2-64da111bd870)


### **2: Instagram Phishing Attack**

1. **Run PyPhisher**:
   ```bash
   python pyphisher.py
   ```

2. **Select the Instagram Phishing Template**:
   From the menu, select the Instagram option by entering its corresponding number.

3. **Enter Shadow URL**:
   Enter the actual Instagram login URL:
   ```
   https://www.instagram.com/accounts/login/
   ```

4. **Enter Redirection URL**:
   Enter the Instagram login URL:
   ```
   https://www.instagram.com/accounts/login/
   ```
![IGpyphisher3](https://github.com/user-attachments/assets/6559f078-dae1-4e5a-81fc-85ee783d5af5)

5. **Generate the Phishing URL**:
   PyPhisher will generate a phishing URL. The output will look something like this:
   ```
   Phishing URL: http://example.com/instagram
   ```
   ![pyphisher5](https://github.com/user-attachments/assets/02f28194-aea7-4cdb-82d1-093a77c5b283)

![IGpyphisher7](https://github.com/user-attachments/assets/c327dc45-5994-4310-8a0c-0cbc0590b230)


6. **Share the Phishing URL**:
   Copy the generated URL and access it on your own system. Monitor the terminal for captured credentials.
   
![IGpyphisher6](https://github.com/user-attachments/assets/613f1f6b-4db8-4af9-8e8a-fc508ef5bfb1)
