# **Django-pollApp**
![GitHub Logo](C:\Users\Sheetal Pandey\Projects\Django-Poll-App\logo)

It is a full featured Polling App.
1. It will require a registration to view the existing polls and vote.
2. If voted already, you cannot vote again.
3. A Poll Owner can:


          1. Add Poll
          2. Edit it
          3. Update it
          4. Delete it
          5. Add choice
          6. End it 
4. A user cannot vote if the poll has ended.
5. One can also searcch from the already existing polls.
6. One can filter polls by - name, number of voted, and publish date.   

## For Testing and Developemnet    

### Pre-requisites:
* Python (3.5 or above versions)
* Django (2.0 or up)

### To use the panel (admin) to make superuser
                python manage.py createsuperuser
             
### To run it in local server
                python manage.py runserver
           Go to http://127.0.0.1:8000/home in browser
