# TypeScript Node SCP Demo for File Transfer 📂🚀  

This repository demonstrates a **TypeScript-based solution** for securely transferring ESS neutron data files using **SCP (Secure Copy Protocol)**. It is designed to integrate with an ingestion pipeline for further processing.

---

## Features ✨  

- **Secure File Transfer**: Uses SCP for transferring files securely.  
- **TypeScript Implementation**: Ensures type safety and clean code.  
- **Integration Ready**: Designed for ESS neutron data ingestion pipelines.  

---

## Prerequisites 🛠️  

- Node.js (14+ recommended).  
- Access to a remote server with SCP enabled.  
- Required packages:
  - `ssh2-sftp-client`  

Install dependencies:  
npm install ssh2-sftp-client  

---

## Installation  

1. Clone the repository:  
   git clone https://github.com/your-username/ts-node-scp-demo.git  
   cd ts-node-scp-demo  

2. Install dependencies:  
   npm install  

---

## Usage 🔧  

1. Update `config.json` with your SCP connection details:  
   - Host  
   - Username  
   - Password or SSH key path  
   - Remote directory  

2. Transfer files via SCP:  
   npm start  

3. Monitor the console for transfer status.  

---

## Configuration  

- **Connection Settings**: Modify `config.json` with your SCP server details.  
- **File Paths**: Adjust source and destination paths in the script.  

---

## File Structure 📂  

- `src/`: TypeScript source code.  
  - `transfer.ts`: Main script for file transfer.  
  - `config.json`: SCP server connection details.  
- `package.json`: Project configuration and dependencies.  
- `README.md`: Documentation for the repository.  

---

## Example Commands  

- Start file transfer:  
  npm start  

---

## Contributing 🤝  

1. Fork the repository.  
2. Create a new branch:  
   git checkout -b feature/your-feature  

3. Commit your changes:  
   git commit -m "Add your feature"  

4. Push the branch:  
   git push origin feature/your-feature  

5. Open a pull request.  

---

## License 📝  

This project is licensed under the MIT License. See the LICENSE file for details.  

---

**Effortlessly transfer files for ESS neutron data ingestion with this SCP demo!** 📂🚀  
