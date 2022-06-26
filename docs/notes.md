# How to create a SSH Key
`ssh-keygen -t rsa -b 4096 -C "<EMAIL ADDRESS>"`

# Eval your SSH key
`eval "$(ssh-agent -s)"`

# Copy our public key
`ssh-copy-id "<EMAIL ADDRESS>"`