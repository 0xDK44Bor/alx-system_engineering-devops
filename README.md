![image](https://user-images.githubusercontent.com/105258746/188767412-2ac881ad-4583-491c-9f86-fa210d23a9db.png)

# ALX System Engineering & DevOps

This repository contains my ALX Software Engineering System Engineering/DevOps projects.  
It covers the full progression from Linux shell fundamentals to networking, server configuration, infrastructure design, debugging, monitoring, and API scripting.

## Repository Overview

- **Program track:** ALX Software Engineering (System Engineering & DevOps)
- **Main focus areas:** Linux, Bash scripting, networking, web stack operations, debugging, infrastructure, automation, APIs
- **Project layout:** one directory per project (`0x00` to `0x1B`, plus `command_line_for_the_win`)
- **Typical deliverables:** shell scripts, Puppet manifests, Python automation scripts, diagrams, and technical write-ups

## Technology and Tools Used

- Bash shell scripting
- Linux/Ubuntu server administration
- SSH, Nginx, HAProxy, MySQL, UFW
- Puppet configuration management
- Python API scripting (`requests`, JSON/CSV export)
- Regex with Ruby (Oniguruma)
- Datadog monitoring setup

## Complete Project Map

| Directory | Topic | What it covers |
| --- | --- | --- |
| `0x00-shell_basics` | Shell Basics | Navigation, file handling, and foundational shell commands |
| `0x01-shell_permissions` | Shell Permissions | File ownership, permissions, and execution rights |
| `0x02-shell_redirections` | Shell Redirections | Input/output redirection, filters, and pipelines |
| `0x03-shell_variables_expansions` | Variables & Expansions | Environment variables, aliases, initialization files |
| `0x04-loops_conditions_and_parsing` | Loops & Parsing | Bash loops, conditions, and text parsing |
| `0x05-processes_and_signals` | Processes & Signals | Process management, signals, and job control |
| `0x06-regular_expressions` | Regular Expressions | Pattern matching with Ruby regex scripts |
| `0x07-networking_basics` | Networking Basics #0 | Core networking concepts, OSI/TCP-IP fundamentals |
| `0x08-networking_basics_2` | Networking Basics #1 | Localhost, IP addressing, and network-oriented Bash tasks |
| `0x09-web_infrastructure_design` | Infrastructure Design | Architecture diagrams for single, distributed, and secured stacks |
| `0x0A-configuration_management` | Configuration Management | Puppet manifests for automating server state |
| `0x0B-ssh` | SSH | Key generation, SSH client config, and secure remote access |
| `0x0C-web_server` | Web Server | Nginx setup, deployment scripts, and basic web serving |
| `0x0D-web_stack_debugging_0` | Web Stack Debugging #0 | First-line debugging for broken web stack behavior |
| `0x0E-web_stack_debugging_1` | Web Stack Debugging #1 | Root-cause analysis and shell-based production fixes |
| `0x0F-load_balancer` | Load Balancing | HAProxy setup and backend balancing behavior |
| `0x10-https_ssl` | HTTPS / SSL | SSL termination, domains, and HTTP-to-HTTPS redirects |
| `0x11-what_happens_when_your_type_google_com_in_your_browser_and_press_enter` | System Design Explanation | End-to-end request lifecycle write-up and diagrams |
| `0x12-web_stack_debugging_2` | Web Stack Debugging #2 | Permissions/process debugging in constrained environments |
| `0x13-firewall` | Firewall | Traffic filtering and safe inbound rule configuration |
| `0x14-mysql` | MySQL | Primary/replica setup and backup scripting |
| `0x15-api` | API | REST data retrieval and export to JSON/CSV |
| `0x16-api_advanced` | API Advanced | Recursive pagination and Reddit API querying tasks |
| `0x17-web_stack_debugging_3` | Web Stack Debugging #3 | Advanced debugging with traces and Puppet fixes |
| `0x18-webstack_monitoring` | Monitoring | Datadog agent setup and metric dashboard/alarm tasks |
| `0x1A-application_server` | Application Server | Gunicorn + Nginx deployment for AirBnB clone backend |
| `0x1B-web_stack_debugging_4` | Web Stack Debugging #4 | Performance and limit tuning via Puppet |
| `command_line_for_the_win` | CLI Challenge | Command-line challenge screenshots and task evidence |

## How to Explore This Repository

1. Start with `0x00` through `0x03` for shell fundamentals.
2. Continue into process/networking projects (`0x04` to `0x08`).
3. Review infrastructure and ops projects (`0x09` onward).
4. Open each module's local `README.md` for project-specific requirements and task details.

## Notes

- Most executable task files are intended for Ubuntu-based environments.
- Some projects depend on remote ALX-provided servers (web-01, web-02, lb-01, etc.).
- This repository is primarily educational and demonstrates hands-on DevOps progression through incremental projects.

