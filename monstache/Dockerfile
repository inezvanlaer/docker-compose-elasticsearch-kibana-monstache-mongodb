# Use an official Python runtime as a parent image
FROM ubuntu

#Create folder
RUN mkdir monstache

# Set the working directory to /app
WORKDIR /monstache

# Copy the current directory contents into the container at /app
COPY . /monstache

# Install any needed packages specified in requirements.txt
RUN apt-get update

# Set privilege 
RUN chmod a+x -R /monstache

# Run app.py when the container launches
CMD ["top"]
