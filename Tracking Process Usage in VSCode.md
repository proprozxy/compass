# Tracking Process Usage in VSCode

to start a process with nohup and keep it running in the background

```bash
nohup
```

list all Python processes

```bash
ps aux | grep python
```

if it is using a network port (for example, using TensorBoard or another form of server), find the port number by the PID

```bash
sudo lsof -i -P | grep <PID>
```

monitor process memory usage in real time

```bash
top -p <PID>
```

