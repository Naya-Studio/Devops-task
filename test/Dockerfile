# Use an image that includes Node.js and Playwright
FROM mcr.microsoft.com/playwright:next

# Set the working directory inside the container
WORKDIR /usr/src/app

# Copy the test files into the container
COPY . .

# Install dependencies
RUN npm install

# Override the default command with a shell session
CMD ["/bin/bash"]
