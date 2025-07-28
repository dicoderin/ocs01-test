## Latest task on octra 

Note : github codespace uses Linux commands 

1. Install Rust
macOS/Linux: 
```curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source $HOME/.cargo/env```   

 Windows: Download and install from https://www.rust-lang.org/tools/install (choose 64-bit or 32-bit based on your system).   

2. clone the repo enter the directory then build (Rust is required for the build to work (because of the cargo command). ```git clone https://github.com/octra-labs/ocs01-test.git```
```cd ocs01-test```
```cargo build --release```   

3.Copy the contract interface

macOS/Linux:
```cp EI/exec_interface.json .```     

Windows:```copy EI\exec_interface.json .```    

4. Create your wallet.json
File using nano wallet.json a new file will be created then type or paste  your details. 
Then use ctrl +0 to save then enter to exit. 

note your wallet.json file must be in the same dir as ``exec_interface.json.``   

5. Run the app
mac/linux: ```./target/release/ocs01-test```

windows: ```target\release\ocs01-test.exe``` 

 when done proceed with step 2 and 3 here https://discordapp.com/channels/1038740318255841280/1186941987719495720/1399143680899547298
