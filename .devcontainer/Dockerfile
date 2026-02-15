FROM espressif/idf:latest

# Install any extra Linux packages you might need
RUN apt-get update && apt-get install -y \
    python3-pip \
    && rm -rf /var/lib/apt/lists/*

# Automatically source the IDF environment for every new terminal
RUN echo "source /opt/esp/idf/export.sh > /dev/null 2>&1" >> ~/.bashrc

