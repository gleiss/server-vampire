# This repository is DEPRECATED/UNMAINTAINED

# server-vampire
A simple Python-server which wraps around Vampire and can be used as backend for the Saturation Visualization of Vampire.

# Setup
## Step 1 - Install Vampire
Download the Vampire source and build it:
```
git clone https://github.com/vprover/vampire
cd vampire
make vampire_rel
```

## Step 2 - Download Vampire server
```
git clone https://github.com/gleiss/server-vampire
cd server-vampire
```

# Running the server
Run the server from the server-vampire directory using
```
python3 ./src/app.py --vampire path/to/vampire/executable
```

The running server will answer requests at port http://127.0.0.1:5000/
