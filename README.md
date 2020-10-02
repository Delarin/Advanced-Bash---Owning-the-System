# Advanced-Bash---Owning-the-System

# Scenario

This project is based on the "offense informs defense" philosophy, which is used to protect the system from attack by thinking like an attacker.

We remotely access a victim's target machine, maintain access using a backdoor, and crack sensitive passwords in the /etc directory.

This is achieved by escalating privilege to root known as owning the system, maintain access, and exfiltrate data.

Also installing a backdoor to reconnect to the exploited machine.

Two machines were setup, the Target Machine and the Attacker Machine.

We then, run SSH session from the Attacker Machine to log into the Target machine --> ssh [username of target machine]@[ip address of target machine] -p 22

We then swap to root user by entering the command sudo -s

We then perform the following steps.

# Steps

Step 1: Shadow People

Step 2: Smooth Sailing

Step 3:  Testing Your Configuration Update

Step 4: Crack All the Passwords
