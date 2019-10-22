# server-vampire
A simple Python-server which wraps around Vampire and can be used as backend for the Saturation Visualization of Vampire.

# Setup
## Step 1 - Install Vampire
### Alternative 2: 
Download the Vampire source and build it yourself:
```
git clone https://github.com/vprover/vampire
cd vampire
make vampire_rel
```

### Alternative 2: 
Get a (reasonably-recent) Vampire binary from https://github.com/vprover/vampire/releases


## Step 2 - Install the Vampire server
Download the Vampire-server and install it using pip3:

```
git clone https://github.com/gleiss/server-vampire
cd server-vampire
pip3 install -r requirements.txt
```

# Running the server
Run the server from the server-vampire directory using
```
python3 ./src/app.py --vampire path/to/vampire/executable
```

The running server will answer requests at port http://127.0.0.1:5000/
