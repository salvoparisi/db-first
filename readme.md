CARS DATABASE

-car_id | BIGINT AUTO_INCREMENT PRIMARY KEY,          
-brand | VARCHAR(100) NOT NULL,                      
-model | VARCHAR(100) NOT NULL,                      
-year | YEAR NOT NULL,                              
-mileage | INT NOT NULL,                            
-?fuel_type | NOT NULL, 
-color | VARCHAR(50) NOT NULL,                      
-price | DECIMAL(10) NOT NULL,                   
-doors | SMALLINT NOT NULL,                           
-engine_capacity | INT NULL,                         
-horsepower | SMALLINT NULL,                                     
-notes | TEXT NULL,                                 
-available | TINYINT DEFAULT 0,                      
-position | VARCHAR(50) NULL,                        
-warranty | TINYINT DEFAULT 0,                       
-language | CHAR(5) DEFAULT 'it-IT'  