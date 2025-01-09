# Weather-Dashboard

In this project we will be building a weather dashboard which collects data from weather API keys and stores it in AWS S3 bucket.

### Steps to be followed :-

1.Clone the repository from the below link
```sh
https://github.com/Ajay-Kumar2103/30Days_DevOps_Challenge_Day1.git
```

2. Install the dependencies from requirements.txt
   
   ```sh
   pip install -r requirements.txt
   ```

3. Configure the environment variables in a file (.env)

   ```sh
   OPENWEATHER_API_KEY=<your_api_key>
   AWS_BUCKET_NAME=<your_bucket_name>
   ```
   Note: Get your API key here (https://home.openweathermap.org/api_keys)

4. Configure AWS credentials
   ```sh
   aws configure
   ```

5. Finally, Run the python script
```sh
python3 src/weather_dashboard.py
```
