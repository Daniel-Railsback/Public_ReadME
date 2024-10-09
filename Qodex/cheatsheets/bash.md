# **Bash Command Cheat Sheet**

## 1. **File and Directory Commands**

### **`ls`** – List Files and Directories
```bash
ls               # List files in the current directory
ls -l            # List with detailed file information (permissions, size, etc.)
ls -a            # Include hidden files
ls -lh           # Human-readable file sizes
```

### **`cd`** – Change Directory
```bash
cd /path/to/directory    # Navigate to directory
cd ..                    # Go up one directory level
cd ~                     # Go to home directory
```

### **`mkdir`** – Create a New Directory
```bash
mkdir new_directory      # Create a directory
mkdir -p path/to/dir     # Create nested directories
```

---

## 2. **File Manipulation**

### **`cp`** – Copy Files
```bash
cp file.txt /destination      # Copy file to destination
cp -r /source /destination    # Copy directories recursively
```

### **`mv`** – Move or Rename Files
```bash
mv old_name.txt new_name.txt  # Rename a file
mv file.txt /destination      # Move file to a different directory
```

### **`rm`** – Remove Files or Directories
```bash
rm file.txt                   # Remove file
rm -r directory/              # Remove directory and contents
rm -rf directory/             # Force remove directory (use cautiously)
```

---

## 3. **File Viewing and Searching**

### **`cat`** – View File Content
```bash
cat file.txt                  # View file content
cat file1.txt file2.txt        # Concatenate multiple files
```

### **`less`** – View File Content in Pages
```bash
less file.txt                 # View file in pages, navigate with arrows
```

### **`grep`** – Search Inside Files
```bash
grep "pattern" file.txt       # Search for a pattern in a file
grep -r "pattern" directory/  # Search recursively in directory
grep -i "pattern" file.txt    # Case-insensitive search
```

### **`find`** – Find Files by Name
```bash
find /path -name "filename"   # Find files by name in path
find . -type f -name "*.txt"  # Find all .txt files in the current directory
```

---

## 4. **Network and Download Commands**

### **`wget`** – Download Files from the Web
```bash
wget https://example.com/file.zip    # Download a file from URL
wget -c https://example.com/file.zip # Continue interrupted download
```

### **`curl`** – Transfer Data from URLs
```bash
curl http://example.com            # Fetch a URL’s content
curl -O http://example.com/file.zip # Download a file
```

---

## 5. **System Information and Monitoring**

### **`top`** – View Running Processes
```bash
top                         # Show system processes and CPU usage
```

### **`df`** – Disk Usage
```bash
df -h                       # Display disk usage in human-readable form
```

### **`du`** – Estimate File/Directory Space Usage
```bash
du -h file_or_directory/     # Show disk usage of file or directory
```

### **`free`** – Memory Usage
```bash
free -h                     # Display memory usage (RAM and swap)
```

---

## 6. **Permissions**

### **`chmod`** – Change File Permissions
```bash
chmod 755 file.sh           # Give the file owner full access, others read & execute
chmod +x script.sh          # Make a script executable
```

### **`chown`** – Change File Owner
```bash
chown user:group file.txt   # Change ownership of file to user and group
```

---

## 7. **Archive and Compression Commands**

### **`tar`** – Create or Extract Archives
```bash
tar -czvf archive.tar.gz /path/to/directory  # Create a compressed archive
tar -xzvf archive.tar.gz                     # Extract compressed archive
```

### **`zip/unzip`** – Compress and Extract Files
```bash
zip archive.zip file.txt    # Create a zip file
unzip archive.zip           # Extract a zip file
```

---

## 8. **Process Management**

### **`ps`** – Display Running Processes
```bash
ps aux                       # Show all running processes with details
```

### **`kill`** – Terminate a Process
```bash
kill [PID]                   # Terminate process by PID
kill -9 [PID]                # Forcefully terminate a process
```

---

## 9. **Miscellaneous**

### **`echo`** – Display a Line of Text
```bash
echo "Hello, World!"         # Print text to the terminal
```

### **`history`** – Show Command History
```bash
history                      # List all previous commands
```

### **`alias`** – Create Shortcuts for Commands
```bash
alias ll='ls -la'            # Create an alias 'll' for 'ls -la'
```

---

## 10. **Script Execution**

### **`bash`** – Execute a Script
```bash
bash script.sh               # Run a bash script
```

---

This cheat sheet covers essential Bash commands for everyday tasks.

