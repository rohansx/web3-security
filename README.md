# WEB3 SECURITY
Resources for web3 security 

### **Steps to install and run in localhost**
### **I. Clone the repository**
- Open the terminal and navigate to the directory where the repository has to be cloned.
- Execute the below command to clone the repository.
    ```bash
    git clone <repository_url>
    ```
    > **Note :** *Replace the <repository_url> with the URL of the repository that has to be cloned.*

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