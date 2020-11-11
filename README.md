# papermc updater
 A papermc updater script written in Python
## Requirements

On **Windows**:  
	https://www.python.org/downloads/  
	https://www.java.com/de/download/manual.jsp

```shell
pip install requests
```
On **Linux**:
```bash
sudo apt install python3
sudo apt install default-jre
sudo apt install python3-pip
pip3 install requests
```
## Usage
On **Windows**:  
copy the **update.bat**,**start.bat**,**serverupdatescript.py**,and **runserverscript.py** to the place where you want your server/where your server is  
double click the **update.bat** and follow any prompts given  
when it's done,double click **start.bat** and follow any prompts given.  
***Your server should be starting up. If not, https://github.com/szabi1035/papermc-updater/issues***  

On **Linux**:  
copy the **update.sh**,**start.sh**,**buildtools_update.py**,and **runserverscript.py** to the place where you want your server/where your server is  
**First** You have to make the scripts executable by cd'ing to the directory and opening a terminal then typing:
```bash
chmod +x update.sh
chmod +x runserver.sh
```
*Then*
```bash
./update.sh
./runserver.sh
```  
  
***COPY LINE BY LINE***  
***Your server should be starting up. If not, https://github.com/szabi1035/papermc-updater/issues***


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
