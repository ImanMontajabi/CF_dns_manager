# ![icons8-orange-48](https://user-images.githubusercontent.com/52942515/227340008-faeeb65b-507e-40cf-b3a7-fd740ee38cb9.png) Cloudflare DNS Record Manager

This Python script allows you to create, list, and delete DNS records in Cloudflare. It is designed to work with Python 3.6 or higher and requires the requests library.
# Dependencies

- [python](https://www.python.org/downloads/) (version 3.6 or higher)
- Libraries
  - `requests`

# Installation and Setup
1. Install Python 3.6 or higher if you haven't already.
2. Create a new folder for the project.
3. Clone the 1CF_dns_manager1 repository into your project folder:
```cmd
git clone https://github.com/ImanMontajabi/CF_dns_manager.git
```
4. Edit the user_id.json file with your Cloudflare account-related information.
5. Obtain a scan.json file from Morteza Bashsiz script/ app that contains your Cloudflare DNS scan data. Save it to your project folder.
6. Open a command prompt or terminal window and navigate to your project folder.
7. Create a Python virtual environment by running:
```python
python -m venv venv
```
8. Activate the virtual environment by running:
```python
.\venv\Scripts\activate
```
9. Install the `requests` library by running:
```python
pip install requests
```
# Usage
**Creating a DNS Record**

To create a new DNS record, run the `create_ip.py` script:
```python
python create_ip.py
```
You will be prompted to enter the IP address, domain name, and record type
# Listing DNS Records
To see a list of your DNS records, run the `list_ip.py` script:
```python
python list_ip.py
```
This will display a table of all of your current DNS records in Cloudflare.
# Deleting a DNS Record
To delete a DNS record, run the `delete_ip`.py script:
```python
python delete_ip.py
```
You will be prompted to enter the domain and record ID of the record you wish to delete.
# License
This project is licensed under the [MIT license](https://github.com/ImanMontajabi/CF_dns_manager/blob/main/LICENSE).





