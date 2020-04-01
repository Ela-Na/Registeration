'''                                                                                                                    
Writer: Elaheh                                                                                                   
Date: 16/9/2019                                                                                                        
Subject: Registration in 2 classes within a time range                                                                 
'''                                                                                                                    
                                                                                                                       
                                                                                                                       
import datetime                                                                                                        
                                                                                                                       
today = datetime.date.today()                                                                                          
margin = datetime.timedelta(30)                                                                                        
if today - margin <= datetime.date(2019, 11, 29) <= today + margin is True:                                            
                                                                                                                       
fName = str(input("enter your first name"))                                                                            
for x in fName:                                                                                                        
    if type(x) == int:                                                                                                 
        print("enter letter")                                                                                          
lName = str(input("enter your last name"))                                                                             
for x in lName:                                                                                                        
    if type(x) == int:                                                                                                 
        print("enter letter")                                                                                          
sid = str(input("enter your student number"))                                                                          
for x in lName:                                                                                                        
    if type(x) != int:                                                                                                 
        print("enter number")                                                                                          
mobile = int(input("enter your mobile number"))                                                                        
for x in mobile:                                                                                                       
    if type(x) != int:                                                                                                 
        print("enter a number")                                                                                        
    else:                                                                                                              
        if x[0] != 0:                                                                                                  
            print("error, wrong mobile")                                                                               
email = str(input("enter your email"))                                                                                 
if "@" not in email:                                                                                                   
    print("wrong email")                                                                                               
                                                                                                                       
                                                                                                                       
                                                                                                                       
                                                                                                                       
fStudy = str(input("enter your field of study"))                                                                       
if fStudy == "Math" or "math":                                                                                         
    listfnames = ['']                                                                                                  
    listlnames = ['']                                                                                                  
    listsids = ['']                                                                                                    
    listmobiles = ['']                                                                                                 
    listemails = ['']                                                                                                  
    listfnames.append(fName)                                                                                           
    listlnames.append(lName)                                                                                           
    listsids.append(sid)                                                                                               
    listmobiles.append(mobile)                                                                                         
    listemails.append(email)                                                                                           
                                                                                                                       
                                                                                                                       
    class Math:                                                                                                        
        fName = None                                                                                                   
        lName = None                                                                                                   
        sid = None                                                                                                     
        mobile = None                                                                                                  
        email = None                                                                                                   
        count = 0                                                                                                      
                                                                                                                       
        def __init__(self, fName, lName, sid, mobile, email):                                                          
                                                                                                                       
            self.fName = fName                                                                                         
            self.fName = lName                                                                                         
            self.sid = sid                                                                                             
            self.mobile = mobile                                                                                       
            self.email = email                                                                                         
            count += count                                                                                             
                                                                                                                       
                                                                                                                       
        def listMath(self):                                                                                            
                listfnames.append(self.fName)                                                                          
                listfnames.append(self.lName)                                                                          
                listfnames.append(self.sid)                                                                            
                listfnames.append(self.mobile)                                                                         
                listfnames.append(self.email)                                                                          
                                                                                                                       
        def listChange(self):                                                                                          
            if today - margin <= datetime.date(2019, 11, 29) <= today + margin is True:                                
                                                                                                                       
                                                                                                                       
                                                                                                                       
elif fStudy == "Biology" or "biology":                                                                                 
        fName = None                                                                                                   
        lName = None                                                                                                   
        sid = None                                                                                                     
        mobile = None                                                                                                  
        email = None                                                                                                   
        count = 0                                                                                                      
                                                                                                                       
        def __init__(self, fName, lName, siD, mobile, email):                                                          
                                                                                                                       
            self.fName = fName                                                                                         
            self.fName = lName                                                                                         
            self.sID = sId                                                                                             
            self.mobile = mobile                                                                                       
            self.email = email                                                                                         
            count +=                                                                                                   
                                                                                                                       
else:                                                                                                                  
    print("You have entered wrong field")                                                                              
                                                                                                                       
                                                                                                                       
                                                                                                                       
                                                                                                                       
                                                                                                                       
if today - margin <= datetime.date(2019, 11, 29) <= today + margin is True:                                            
                                                                                                                       
    listMathFnames = [fName]                                                                                           
                                                                                                                       
    if fStudy is "Math":                                                                                               
                                                                                                                       
        listMath = []                                                                                                  
                                                                                                                       
                                                                                                                       
else:                                                                                                                  
    print("The registration is ended")                                                                                 
                                                                                                                       
'''                                                                                                                    
d1 = date(2019, 11, 29) - date.today()                                                                                 
d2 = datetime.timedelta(30)                                                                                            
date(2019, 11, 29) - date.today() < timedelta(30)                                                                      
date(2019, 12, 29) - date.today() < timedelta(30)                                                                      
                                                                                                                       
'''                                                                                                                    
