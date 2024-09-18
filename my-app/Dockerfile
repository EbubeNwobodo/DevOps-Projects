# Step 1: Use an official base image
FROM node:14

# Step 2: Set the working directory inside the container
WORKDIR /app

# Step 3: Copy the application code into the container
COPY . /app

# Step 4: Install the necessary dependencies
RUN npm install

# Step 5: Expose the port your app runs on (Assuming the app runs on port 3000)
EXPOSE 3000

# Step 6: Define the command to run the application
CMD ["npm", "start"]
