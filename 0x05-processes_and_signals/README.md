# Processes and signals

## Resources

* [Linux PID](https://alx-intranet.hbtn.io/rltoken/zh33PXDR6w_qyu7zXUezmw)
* [Linux process](https://alx-intranet.hbtn.io/rltoken/px2TdWSjVO8i9SB5gHchAw)
* [Linux signal](https://alx-intranet.hbtn.io/rltoken/0NIee0VXMrEp36CFR85GIA)
<!-- * []() -->

## Tasks 🚨 🚨 🚨

0.  __What is my PID:__ Write a Bash script that displays its own PID.

1. __List your processes:__ Write a Bash script that displays a list of currently running processes. Requirements: Must show all processes, for all users, including those which might not have a TTY,, Display in a user-oriented format,, Show process hierarchy

2. __Show your Bash PID:__ Using your previous exercise command, write a Bash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process. Requirements: You cannot use pgrep,, The third line of your script must be # shellcheck disable=SC2009 (for more info about ignoring shellcheck error here)

3. __Show your Bash PID made easy:__ Write a Bash script that displays the PID, along with the process name, of processes whose name contain the word bash. Requirements: You cannot use ps

4. __To infinity and beyond:__ Write a Bash script that displays To infinity and beyond indefinitely. Requirements: In between each iteration of the loop, add a sleep 2

5. __Don't stop me now!:__ We stopped our 4-to_infinity_and_beyond process using ctrl+c in the previous task, there is actually another way to do this. Write a Bash script that stops 4-to_infinity_and_beyond process. Requirements: You must use kill

6. __Stop me if you can:__ Write a Bash script that stops 4-to_infinity_and_beyond process. Requirements: You cannot use kill or killall

7. __Highlander:__ Write a Bash script that displays: To infinity and beyond indefinitely,, With a sleep 2 in between each iteration,, I am invincible!!! when receiving a SIGTERM signal.
Make a copy of your 6-stop_me_if_you_can script, name it 67-stop_me_if_you_can, that kills the 7-highlander process instead of the 4-to_infinity_and_beyond one.

8. __Beheaded process:__ Write a Bash script that kills the process 7-highlander.

9. __Process and PID file:__ Write a Bash script that: Creates the file /var/run/myscript.pid containing its PID,, Displays To infinity and beyond indefinitely,, Displays I hate the kill command when receiving a SIGTERM signal,, Displays Y U no love me?! when receiving a SIGINT signal,, Deletes the file /var/run/myscript.pid and terminates itself when receiving a SIGQUIT or SIGTERM signal

10. __Manage my process:__ Read: [&](https://alx-intranet.hbtn.io/rltoken/R4YSgPT1k0PhWCrB0TYzoQ), [init.d](https://alx-intranet.hbtn.io/rltoken/sVqN4oNYYO6ojS4ctT02Jw), [Daemon](https://alx-intranet.hbtn.io/rltoken/kCoQ5aYO3towdDQFVPcfNg), [Positional parameters](https://alx-intranet.hbtn.io/rltoken/TJ2rxUwRsnM1mJQHSCnOQA). Write a manage_my_process Bash script that: Indefinitely writes I am alive! to the file /tmp/my_process,, In between every I am alive! message, the program should pause for 2 seconds. __:__ Write Bash (init) script 101-manage_my_process that manages manage_my_process. (both files need to be pushed to git)

11. __Zombie:__ Read: [What a zombie process is](https://alx-intranet.hbtn.io/rltoken/Tb86ZoSxR6ORCKYlZaYzHw). Write a C program that creates 5 zombie processes.

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

