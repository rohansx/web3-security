# WEB3 SECURITY
The [web3-security](https://github.com/rohansx/web3-security) repository is a collection of resources and code related to the topic of web3-security. The goal of this project is to provide guidance and tools to the Developers, Pentesters, Bug Hunters and security enthusiasts on web3 stack.

---

### **Steps to install and run in localhost**
### **I. Clone the repository**
- Open the terminal and navigate to the directory where the repository has to be cloned.
- Execute the below command to clone the repository.
    ```bash
    git clone https://github.com/rohansx
    ```
    > **Note :** *Replace the <repository_url> with the URL of this repository (https://github.com/rohansx/web3-security.git or [git@github.com:rohansx/web3-security.git](git@github.com:rohansx/web3-security.git))*

### **II. Install mdbook** 
- [mdbook](https://github.com/rust-lang/mdBook) is a command-line utility to create modern online books from markdown files.
- The prerequisites for installing *[mdbook](https://github.com/rust-lang/mdBook)* are *[Rust](https://www.rust-lang.org)* and *[cargo](https://doc.rust-lang.org/cargo/)* *(a rust package manager).*
- Execute the below commands to install *[Rust](https://www.rust-lang.org)* and *[cargo](https://doc.rust-lang.org/cargo/).*
    ```bash
    #sample code to install rust and cargo in ubuntu
    sudo apt-get update
    ```
    ```bash
    #install rust
    sudo apt install rustc
    ```
    ```bash
    #install cargo
    sudo apt -y install cargo
    ```
    > **Note :** *Skip the above step if Rust and cargo are installed already.*
- Execute the below command to install latest ***mdbook***
    ```bash
    #command to install mdbook
    cargo install --git https://github.com/rust-lang/mdBook.git mdbook
    ```
- Wait for the installation process to complete. *mdbook* will be installed once all the process completes.

### **III. Serve the application on localhost**
- Open the terminal and navigate to cloned repository.
- Execute the below command to serve the application on localhost.
    ```bash
    mdbook serve --open
    ```
- On executing the above command the application will be automatically opened in the default web browser, running on ***http://localhost:3000*** or any respective url and port.

*By following the above steps, you should be able to clone the repository, install mdbook and run the application on localhost.*
