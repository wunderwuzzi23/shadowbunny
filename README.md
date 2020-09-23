# Beware of the Shadowbunny
## Leveraging virtual machines (VMs) during lateral movement

**********************************************************

### What is the Shadowbunny?

"A Shadowbunny is a virtual machine (VM) instance that is deployed on a compromised host to provide an adversary persistence and at the same time evade detections. The VM itself does not have any security monitoring and is entirely attacker controlled."

https://www.urbandictionary.com/define.php?term=shadowbunny

Real world adversaries have been using VMs as well, including the [Ragnar Locker Ransomware](https://news.sophos.com/en-us/2020/05/21/ragnar-locker-ransomware-deploys-virtual-machine-to-dodge-security/), and it's time to shine more light on this, so that we have better chances of detecting such attacks.

### Resources

* [PenTest Magazine](https://pentestmag.com/product/pentest-healthcare-security/) features an article of mine about using virtual machines (VMs) during lateral movement to establish persistence and evade detections.
* "Beware of the Shadowbunny" presentation at [BSides Singapore 2020](https://bsidessg.org/speaker/johann-rehberger/). 
* Detailed [blog post about the Shadowbunny TTP](https://embracethered.com/blog/posts/2020/shadowbunny-virtual-machine-red-teaming-technique/)
* The Wiki page in this github repo: https://github.com/wunderwuzzi23/shadowbunny/wiki/Beware-of-the-Shadowbunny
* [Ragnar Locker Ransomware Deep-dive](https://news.sophos.com/en-us/2020/05/21/ragnar-locker-ransomware-deploys-virtual-machine-to-dodge-security/)

There will be updates once in a while with more technical details, read it first at https://embracethered.com.



## Disclaimer
Penetration testing requires authorization from proper stakeholders. Information in this post is provided for research and educational purposes to advance understanding of attacks and countermeasures to help improve the security posture of  infrastructure and systems. 

```
                / \
                / _ \
               | / \ |
               ||   || _______
               ||   || |\     \                       The SHADOWBUNNY :)
               ||   || ||\     \              
               ||   || || \    |             ...is hiding in virtual machines.
               ||   || ||  \__/
               ||   || ||   ||
                \\_/ \_/ \_//
               /   _     _   \
              /               \
              |    O     O    |
              |   \  ___  /   |                           
             /     \ \_/ /     \
            /  -----  |  --\    \
            |     \__/|\__/ \   |
            \       |_|_|       /
             \_____       _____/
                   \     /
                   |     |
```
*ASCII Art from https://www.asciiart.eu/animals/rabbits*



### References
* https://embracethered.com/shadowbunny-ttp-pt.html
* https://pentestmag.com/product/pentest-healthcare-security/
* https://attack.mitre.org/techniques/T1062/
* https://wunderwuzzi23.github.io/blog/posts/2020/shadowbunny-ttp-pentest-magazine/
* https://twitter.com/wunderwuzzi23


