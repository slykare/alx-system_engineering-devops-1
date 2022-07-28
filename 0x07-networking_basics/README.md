# Regular expression

## Resources

* [OSI model](https://alx-intranet.hbtn.io/rltoken/k2uCsynicuNbu1cAQhXqVQ)
* [Different types of network](https://alx-intranet.hbtn.io/rltoken/XW3ZGm5Ya_a8XVDXcAKT_A)
* [LAN network](https://alx-intranet.hbtn.io/rltoken/en370-Hrwgi_GUvFcg3bKg)
* [WAN network](https://alx-intranet.hbtn.io/rltoken/Ah1EKqnINR85lM4P2WnLSw)
* [Internet](https://alx-intranet.hbtn.io/rltoken/Lwh9xQxFD4dWh5sIApXI1g)
* [MAC address](https://alx-intranet.hbtn.io/rltoken/j-Wp-YRvFTVP04SpIeRzHQ)
* [What is an IP address](https://alx-intranet.hbtn.io/rltoken/HaZZvrmGaQ3U7ZLDYgZb6w)
* [Private and public address](https://alx-intranet.hbtn.io/rltoken/OPJCZYuWSEXLIZOqU9Uc0A)
* [IPv4 and IPv6](https://alx-intranet.hbtn.io/rltoken/M8g-egWLlldTl6Y0QECdwA)
* [Localhost](https://alx-intranet.hbtn.io/rltoken/7lj-zoZQ7xFTkj4MTyos_g)
* [TCP and UDP](https://alx-intranet.hbtn.io/rltoken/uJbs8E9-FyATfsELpmtTIg)
* [TCP/UDP ports List](https://alx-intranet.hbtn.io/rltoken/4PYkqDfOvIZZb9aUPGOOzQ)
* [What is ping /ICMP](https://alx-intranet.hbtn.io/rltoken/3zBgO6r2M1Q8lUVt9g8aJw)
* [Positional parameters](https://alx-intranet.hbtn.io/rltoken/ZbMHH3jmxFhcrbigVy15iw)

## Tasks 🚨 🚨 🚨

0.  __OSI model:__ OSI (Open Systems Interconnection) is an abstract model to describe layered communication and computer network design. The idea is to segregate the different parts of what make communication possible.

        It is organized from the lowest level to the highest level:

        a. The lowest level: layer 1 which is for transmission on physical layers with electrical impulse, light or radio signal

        b. The highest level: layer 7 which is for application specific communication like SNMP for emails, HTTP for your web browser, etc

    Keep in mind that the OSI model is a concept, it’s not even tangible. The OSI model doesn’t perform any functions in the networking process. It is a conceptual framework so we can better understand complex interactions that are happening. Most of the functionality in the OSI model exists in all communications systems.
![OSI Model](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2018/6/4e6a0ad87a65d7054248.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220728%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220728T052254Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=8db6bef983dfe0f562a72123dfcc6a478fadbe48f535b06a09c46453f79298b2)

    The image bellow describes more concretely how you can relate to every level.

![TCP/UDP IP and ICMP](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/0fc96bd99faa7941b18bcae4c5f90c6acd11791d.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220728%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220728T052254Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=8d8a532de4ea783b2d93c177dc8fdd5ed6e86dd025538957d1477d18922d7936)

1. __Types of network:__ LAN connect local devices together, WAN connects LANs together, and WANs are operating over the Internet.

![Internet WAN LAN](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/4b995d4f8078b44afa968d68a98035d2bd7e8fac.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220728%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220728T052254Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a48ef2f9a15d0e40758b784d4795c21f1b52f42de3e5ed5e527611b0b45c826a)

2. __MAC and IP address:__

![MAC and IP](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/1e348ba3bcbb094b02922f821ffeb3d8c5438b7b.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220728%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220728T052254Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=833e60613fe9ace54baed09d8d2960c2282c80153d6eb198c7a4f63c65432bab)

3. __UDP and TCP:__ Let’s fill the empty parts in the drawing above.

![UDP and TCP](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/3d92e3c4a470f8ecf4c73db511fcbbadaa002e1c.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220728%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220728T052254Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=b533ac99f859511d3f4628eac26e92e9d49ccce754256abb286e1660c57ddef8)

4. __:__ Once packets have been sent to the right network device using IP using either UDP or TCP as a mode of transportation, it needs to actually enter the network device.

    If we continue the comparison of a network device to your house, where IP address is like your postal address, UDP and TCP ports are like the windows and doors of your place. A TCP/UDP network device has 65535 ports. Some of them are officially reserved for a specific usage, some of them are known to be used for a specific usage (but nothing is officially declared) and the rest are free of use.

        While the full list of ports should not be memorized, it is important to know the most used ports, let’s start by remembering 3 of them:

        a. 22 for SSH
        b. 80 for HTTP
        c. 443 for HTTPS

        Note that a specific [IP + port = socket](https://alx-intranet.hbtn.io/rltoken/tMKODilbDVpB8EgfIRDJVw).

        Write a Bash script that displays listening ports:
            a. That only shows listening sockets
            b. That shows the PID and name of the program to which each socket belongs

5. __Is the host on the network:__ The Internet Control Message Protocol (ICMP) is a protocol in the Internet protocol suite. It is used by network devices, to check if other network devices are available on the network. The command ping uses ICMP to make sure that a network device remains online or to troubleshoot issues on the network.

        Write a Bash script that pings an IP address passed as an argument.

        Requirements:
            a. Accepts a string as an argument
            b. Displays Usage: 5-is_the_host_on_the_network {IP_ADDRESS} if no argument passed
            c. Ping the IP 5 times


## Author(s) Info

Name 👨🏽‍💻: __Lawrence OTIENO__

* Fields: Software Development 💻, Data Analysis 📊, Digital Marketing 💹, Data Entry 📑.

* Languages: Python (__Django__, Flask), JavaScript (__Angular__, React), C programming, R programming.

* Website visit: [🌐My Portfolio](https://lawiotieno.github.io/portfolio)

* MORE INFO 🌐: [More Links🔗 Here](https://shor.by/lawi)

## Support/Donate

You can support our work in many ways, including buying us coffee ☕️.  
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/N4N26PU7L)

* Help us continue coding...

<!-- [Buy Me Coffee ☕️](https://ko-fi.com/streetgrandmaster) -->

## Contact Information

For any Support or Feedback, fill free to contact:

* Email at [📧lawifirst@gmail.com](mailto:lawifirst@gmail.com)
* Phone on [📞+254708581688](tel:+254708581688)

> Open for any collaboration, recommendation and update suggestions.

## LICENSE

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](/LICENSE)

<!-- [MIT License](https://choosealicense.com/licenses/mit/) -->
