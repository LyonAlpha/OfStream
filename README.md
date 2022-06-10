# <span style="color: white">__OFSTREAM__</span>

### *Output File Stream*

#### Under Experimentation, Not Fully Developed As Of 2022

Developed by ST 2022

## Installation

```console
pip install ofstream
```


## How To Use - <span style="color: red">[Alpha Version]</span>

*__Using The File Functions__*

```python
from ofstream import <function_name>
function_name('<file_name.txt>', '<filetext>', '<other_parameters>')
# And ... Done!
```
*__An Example__*

```python
from ofstream import write_file
write_file('myfile.txt', 'mytextstring!')
# And ... Done!
```

### The Logger - <span style="color: red">[*__Extreme__ Alpha Version*] </span>

```python
from ofstream import Log

# Create Instance/Log

log = Log('<log_name>', '<log_message>', '<log_level>', '<log_file>', True)

# The Boolean Is Whether It Should Print The Log Message Onto The Screen Or Not
# And ... Done!
```

*__An Example__*

```python
from ofstream import Log

# Create Instance/Log

servercrash = Log('VaultLog', 'Server Crashed!', 'CRITICAL', 'servercrashes.log', False)

# There Is A 'default' Parameter For The Log File; It Will Create A Log File With The Current Date 
# And ... Done!
```
