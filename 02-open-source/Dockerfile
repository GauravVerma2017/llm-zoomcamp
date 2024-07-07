# Use the base image for Ollama
FROM ollama/ollama

# Set the working directory
WORKDIR /root/.ollama

# Copy your custom files or scripts if needed
COPY ./ollama_files/ /root/.ollama/

# Install additional dependencies if required
# RUN apt-get update && apt-get install -y some-package

# Expose the necessary port
EXPOSE 11434

# Define the default command
CMD ["./your-custom-startup-script.sh"]
