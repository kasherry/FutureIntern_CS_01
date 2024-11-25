# Kali Linux Tasks

## Tools Installed
1. **Nikto**: Web vulnerability scanning.
2. **Nmap**: Network scanning.
3. **SQLmap**: SQL injection testing.

## Results
Reports are located in the `reports/` directory.

### Steps to Reproduce
1. Install Kali Linux or use an existing environment.
2. Run the following tools:
   - **Nikto**: `nikto -h http://testphp.vulnweb.com/`
   - **Nmap**: `nmap -A http://testphp.vulnweb.com/`
   - **SQLmap**: `sqlmap -u http://testphp.vulnweb.com/ --dbs`
3. Save results in respective files.
