"# najehcare" 
Instructions to Run the NajehCare Project  

1. **Download the Repository**: Clone or download the repository
2. **Install Composer**: Ensure Composer is installed on your system.  
3. **Run Migrations**: Execute the command below to set up the database tables:  
   php artisan migrate  
4. **Seed Specializations**: Run the following seeder to populate the `Specializations` table, which is necessary for doctors and clients to select a specialization during account creation or appointment scheduling:  
   php artisan db:seed --class=SpecializationSeeder  
5. **Start the Development Server**: Use this command to serve the application:  
   php artisan serve  

Once the application is running, both doctors and clients will be able to select specializations and proceed with their respective functionalities.  
