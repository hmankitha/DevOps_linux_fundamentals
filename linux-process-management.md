# Linux Process Management

Processes are programs or tasks running on a Linux system. 
Learning how to view and manage processes is important, especially when a system is slow or unresponsive.

---

## Viewing Processes

- `ps aux` : Show all running processes with details.
- `top` : Display real-time system information and processes.
- `htop` : An interactive process viewer (needs installation).

---

## Managing Processes

- `kill process_id` : Stop a process using its ID.
- `pkill process_name` : Stop a process using its name.
- `sleep 100 &` : Run a process in the background.
- `jobs` : List background processes.
- `fg` : Bring a background process to the foreground.
- `bg` : Resume a stopped process in the background.

---

## Tips

- Always check which process you are killing to avoid stopping important system tasks.
- Use `top` or `htop` to monitor system resources and CPU usage.
