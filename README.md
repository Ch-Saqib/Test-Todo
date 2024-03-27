docker build -t todo-app .
docker run -p 0.0.0.0:8000  -e DATABASE_URL="postgresql://Ch-Saqib:4H0iLkyNBpqu@ep-weathered-credit-48841962.us-east-2.aws.neon.tech/Todo-Test?sslmode=require" todo-app
