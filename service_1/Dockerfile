# Use the official Golang image as the base
FROM golang:1.22

# Set the working directory inside the container
WORKDIR /app

# Copy all Go files into the container
COPY . .

# Build the Go app
RUN go build -o service1 main.go

# Expose port 8001 for this service
EXPOSE 8001

# Command to run the app
CMD ["./service1"]
