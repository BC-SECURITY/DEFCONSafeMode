[1.1]: http://i.imgur.com/tXSoThF.png (twitter icon with padding)
[2.1]: http://i.imgur.com/P3YfQoD.png (facebook icon with padding)
[3.1]: http://i.imgur.com/yCsTjba.png (google plus icon with padding)
[4.1]: http://i.imgur.com/YckIOms.png (tumblr icon with padding)
[5.1]: http://i.imgur.com/1AGmwO3.png (dribbble icon with padding)
[6.1]: http://i.imgur.com/0o48UoR.png (github icon with padding)

[1]: https://twitter.com/bcsecurity1
[2]: http://www.facebook.com/XXXXXXX
[3]: https://plus.google.com/XXXXXXX
[4]: http://XXXXXXX.tumblr.com
[5]: http://dribbble.com/XXXXXXX
[6]: http://www.github.com/BC-SECURITY
[7]: https://www.bc-security.org/blog

 # DEFCON Safe mode
[![alt text][1.1]][1]
[![alt text][6.1]][6]

Keep up-to-date on our blog at [https://www.bc-security.org/blog][7]

## APTs <3 PowerShell and Why You Should Too
When: August 8, 2020 1315-1415  
Where: Red Team Village

Quite often, you may have heard people mention, “Why should you bother learning PowerShell, isn’t it dead?” or “Why not just use C#?” Many individuals in the offensive security field have a common misconception that PowerShell is obsolete for red team operations. Meanwhile, it remains one of the primary attack vectors employed by Advanced Persistent Threats (APTs).

APTs are known for implementing sophisticated hacking tactics, techniques, and procedures (TTPs) to gain access to a system for an extended period of time. Their actions typically focus on high-value targets, which leave potentially crippling consequences to both nation-states and corporations. It is crucial that Red Teams accurately emulate real-world threats and do not ignore viable attack options. 

For this talk, we will walk through how many threat actors adapt and employ PowerShell tools. Our discussion begins with examining how script block logging and AMSI are powerful anti-offensive PowerShell measures. However, the implementation of script block logging places a technical burden on organizations to conduct auditing on a substantial amount of data. While AMSI is trivial to bypass for any capable adversary. Finally, we will demonstrate APT-like PowerShell techniques that remain incredibly effective against the latest generation of network defenses.

* [Slides](./Red%20Team%20Village%20-%20APTs%20Love%20PowerShell%20and%20You%20Should%20Too.pdf)

## Starkiller
When: August 8, 2020 1000-1200   
Where: DEF CON Demo Lab

The ultimate goal for any security team is to increase resiliency within an organization and adapt to the modern threat. Starkiller aims to provide red teams with a platform to emulate Advanced Persistent Threat (APT) tactics. Starkiller is a frontend for the post-exploitation framework, PowerShell Empire, which incorporates a multi-user GUI application that interfaces with a remote Command and Control (C2) server. Empire is powered by Python 3 and PowerShell and includes many widely used offensive security tools for Windows, Linux, and macOS exploitation. The framework's flexibility to easily incorporate new modules allows for a single solution for red team operations. Both red and blue teams can utilize Starkiller to emulate and defend against the most used APT attack vectors.

### Resources
* [Blog - Introduction to Starkiller](https://www.bc-security.org/post/an-introduction-to-starkiller/)
* [GitHub - Starkiller](https://github.com/BC-SECURITY/Starkiller/)
* [Slides](./DEFCON%2028%20Demo%20Lab%20-%20Starkiller.pdf)
