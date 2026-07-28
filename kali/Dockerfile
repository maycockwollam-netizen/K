FROM kalilinux/kali-rolling

# Update Kali
RUN apt-get update && apt-get upgrade -y

# Install basic security tools
RUN apt-get install -y \
    nmap \
    metasploit-framework \
    burpsuite \
    sqlmap \
    nikto \
    hydra \
    john \
    hashcat \
    net-tools \
    tcpdump \
    curl \
    wget \
    git \
    vim \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /root
CMD ["/bin/bash"]
