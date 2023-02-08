#simple mail transfer protocol
import smtplib as er #smtplib module
with er.SMTP('smtp.gmail.com',587) as mki:#context manager
    mki.ehlo()#secure layer
    mki.starttls()#secure layer
    mki.ehlo()#secure layer
    mki.login('user','passs')#credintails
    subject='hai iam from python programming language...'#subject of mail
    body='i am ready to send gmail'#mail body
    msg=f'subject:{subject}\n\n{body}'#alignment
    mki.sendmail('from','to@gmail.com',msg)#sending processs
    print('ok..successfully send..') #jsut conformation
