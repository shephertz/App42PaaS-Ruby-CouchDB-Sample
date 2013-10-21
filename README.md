App42PaaS-Ruby-CouchDB-Sample
=============================

Sample Ruby App with CouchDB for App42 PaaS Platform

## Getting Start with App42

1. Setup infrastructure for required environment
2. Create service
3. Deploy a Ruby application

### Setup infrastructure for required environment

    $ app42 setupInfra   
    
### Create service

    $ app42 createService
    
DB Configure for Production environment (application_root_dir/config/database.yml) 

    protocol: 'http'                                                 
    host: < host >                  # VM IP  
    port: < port >                  # VM Port  
    prefix: < database name >       # Database Name a/c to prefix and suffix   
    suffix: production              # Database Name a/c to  prefix and suffix  
    username: < user_name >         # User Name  
    password: '< password >'        # Password   
    
### Deploy a Ruby application

    $ app42 deploy

#### Get application details:

    $ app42 appInfo --app AppName    
    
Visit your application:

