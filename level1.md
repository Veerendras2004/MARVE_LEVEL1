# TASKS OF LEVEL 1
***
# TASK 1:  Linux Based Task with Socket.io
**Socket.IO** is a popular JavaScript library that enables real-time, bidirectional communication between web clients (browsers) and servers.
The socket.emit() is used to send data and 
socket.on() is used to receive data.
Repository link : (https://github.com/Veerendras2004/MARVE_LEVEL1/tree/main/socket)

![image](https://i.postimg.cc/ZqnBZMyL/Screenshot-2024-10-02-134345.png)
![image](https://i.postimg.cc/nhP7sxxW/Screenshot-2024-10-02-134506.png)

***

# Task 2: Git Bash and GitHub

 A command-line tool  that provides a Git command-line experience and  shell utilities to interact with Git repositories and execute Git commands.

 # Important Git Commands

```bash
# Configure Git
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

# Initialize Git Repository
git init

# Clone Repository
git clone <repository-url>

# Check Status
git status

# Add files to staging area
git add <file>   # Add a specific file
git add .        # Add all files

# Commit Changes
git commit -m "Your commit message"

# Push changes to remote repository
git push origin <branch-name>

# Pull changes from remote repository
git pull

# Check branch
git branch        # List branches
git checkout <branch-name>  # Switch branch

# Create new branch
git checkout -b <new-branch-name>

# Merge branches
git merge <branch-name>

# View Commit History
git log

# Remove file from staging area
git reset <file>

# Revert to a specific commit
git reset --hard <commit-hash>

# Delete a branch
git branch -d <branch-name>
```



 ***
 
# Task 3: OSI MODEL

**The OSI** (Open Systems Interconnection) model is a conceptual framework that standardizes the functions of a telecommunication or computing system into seven distinct layers, ranging from physical data transmission to application-level interactions.

 (https://app.diagrams.net/#G1krpkJNfbqEldFJOIzlArHEaKNxYSpka7#%7B%22pageId%22%3A%225FSC4iSbLdWom-XH1Pr2%22%7D)



 
 ![image](https://i.postimg.cc/1z0g4XFH/OSIMF.jpg)


***
# Task 4:Encryption Techniques
In this task, I developed a basic encryption and decryption program using Python's PyCrypto library, which supports various cryptographic algorithms. I implemented the AES algorithm in two modes: ECB (Electronic Codebook) and CBC (Cipher Block Chaining).

For the ECB mode, I encrypted the plaintext directly, where each block was processed independently. While this approach is faster, it lacks security due to identical plaintext blocks producing identical ciphertext blocks.

In CBC mode, I used an initialization vector (IV) to enhance security. I padded the plaintext to match the required block size before encrypting, ensuring that each block depended on the previous ciphertext. The ciphertext and IV were saved to a file. For decryption, I retrieved the IV and ciphertext, created a cipher with the same key and IV, and decrypted the message, finally unpadding it to restore the original text.

[![Screenshot-2024-10-27-182238.png](https://i.postimg.cc/FHgnSLn0/Screenshot-2024-10-27-182238.png)](https://postimg.cc/dh3BPLF0)
[![Screenshot-2024-10-27-183455.png](https://i.postimg.cc/wjVsLq51/Screenshot-2024-10-27-183455.png)](https://postimg.cc/MnnT88Fw)
[![Screenshot-2024-10-27-182254.png](https://i.postimg.cc/JnwmhJyZ/Screenshot-2024-10-27-182254.png)](https://postimg.cc/bGR4CZ9w)


 # Task 5: IP Addressing and Protocols

 ## WEB SCRAPING
 Web scraping with Python and BeautifulSoup involves extracting data from websites by parsing HTML content. BeautifulSoup simplifies the process by providing easy-to-use methods for navigating, searching, and modifying the HTML/XML structure, allowing you to extract the specific information you need.

 [![Screenshot-2024-10-02-111318.png](https://i.postimg.cc/brGSYhjH/Screenshot-2024-10-02-111318.png)](https://postimg.cc/fSNR51yJ)

