- Stwórz Realm o nazwie training

- Stwórz nowego clienta
    - Client ID: products-backend
    
- Skonfiguruj klienta
    - training->Clients->Settings
        - Valid Redirect URIs: http://localhost:8080/*
        - Base URL: http://localhost:8080
        
- Stwórz role
    - training->Roles
        - Role name: user
        
    - training->Roles
        - Role name: admin
        
- Stwórz użytkowników
    - training->Users
        - Username: client
        
    - training->Users
        - Username: employee  
          
- Skonfiguruj użytkowników
    - training->Users->client->Credentials
        - Password: 123
        - Password Confirmation: 123
        - Temporary: off    
 
    - training->Users->client->Role Mappings
        - Assigned Roles: user   
        
    - training->Users->employee->Credentials
        - Password: 123
        - Password Confirmation: 123
        - Temporary: off   
         
    - training->Users->employee->Role Mappings
        - Assigned Roles: admin       
      
- Skonfiguruj możliwość rejestracji użytkowników
    - training->Realm settings->Login/Email
    
- Ustaw motyw dla ekranu logowania
    - training->Realm settings->Themes
        - Login Theme: training-theme