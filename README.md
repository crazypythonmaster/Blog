This project comes from djangogirls tutorial.
============================================


1.Install python	  
	windows:download from		
			https://www.python.org/downloads/release/python-343			 
	ubunto		 
	    sudo apt-get install python3.4  

2.Set up virtual environment  
	windows: C:\Users\Name\djangogirls> C:\Python34\python -m venv myvenv 	
	ubunto: python3 -m venv myvenv  	
3.Install django  
	pip install django==1.8		
4.Config Database               	
	python manage.py makemigrations blog            
	python manage.py migrate blog                   
5.Create superuser      
	(myvenv) ~/djangogirls$ python manage.py createsuperuser        
6.Run                                           
        python manage.py runserver      
	
