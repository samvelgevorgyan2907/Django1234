# Django1234
Python programming


------------------------------------------------------------------------------------------------
|                                                                                              |
|                                         DJANGO                                               | 
|                                                                                              |
------------------------------------------------------------------------------------------------
Սկսելու համար պետք է install անենք venv-ը python-ի modul-ների միջից                            
1) py -m venv venv                                                                             
------------------------------------------------------------------------------------------------
Ակտիվացնում ենք venv-ը                                                                         
2) ./venv/Scripts/acivate.bat                                                                  
------------------------------------------------------------------------------------------------
venv-ի մեջ install ենք անում pip-ը                                                             
3) py -m pip install --upgrade pip                                                             
------------------------------------------------------------------------------------------------
pip-ի միջոցով install ենք անում django-ն                                                       
4) py -m pip install Django                                                                    
------------------------------------------------------------------------------------------------
Պրոեկտ ստեղծելու համար գրում ենք՝                                                              
5) py -m django startproject core                                                              
------------------------------------------------------------------------------------------------
Մտնում ենք core-ի մեջ                                                                          
6) cd core                                                                                     
------------------------------------------------------------------------------------------------
Ստեղծում ենք application                                                                       
7) py manage.py startapp main                                                                  
------------------------------------------------------------------------------------------------
Ավելացնում ենք app-ի անունը settings-ներում                                                    
------------------------------------------------------------------------------------------------
app-ի folder-ի մեջ ստեղծում ենք urls.py անունով file                                           
------------------------------------------------------------------------------------------------
core-urls.py file-ը կցում ենք app-ի main-ի urls.py file-ին                                                                       
------------------------------------------------------------------------------------------------
Ինչ-որ բան կայքում ցույց տալու համար, գրում ենք views.py ֆայլում                               
------------------------------------------------------------------------------------------------
 Աշխատացում ենք manage.py file-ը                                                               
8) py manage.py runserver                                                                      
------------------------------------------------------------------------------------------------