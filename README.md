Personal Information

Name: Zeyi Li

Student number: s3958095

Student email address: s3958095@rmit.student.edu

Picture:![image](https://user-images.githubusercontent.com/110008240/184533802-adeae1df-cd29-4102-b6d3-b2509ba2030b.png)

Nationality and culture: China

Languages spoken: Chinese and English

One fact about yourself: Keeping pets is one of my hobbies. Two cats and one dog make my life full of fun.

Interest in IT 

I watched The Matrix when I was a child, and then I thought the colorful computer code interface was too excellent, so I wanted to be the kind of hacker who could be like the one in the movie. Although I scratch my scalp stupidly facing a few lines of code every day, it will give me a great sense of accomplishment after completing a program. 

Furthermore, my interest in gaming has sparked my interest in IT. There are often many cheaters in some games, so normal players have no game experience. I want to contribute to the anti-cheat program in the future.

I chose RMIT because it is located in the city center, which is very convenient for travel and daily life. IT is an excellent course in RMIT, and the employment rate is also very high.I would like to learn something about data science and cybersecurity at RMIT.

Ideal Job 
https://www.seek.com.au/job/58064326?type=standout#sol=a21006d66983a55f7bb87a25dd886011ef2a73e

![image](https://user-images.githubusercontent.com/110008240/184797165-4f8f2871-6cd9-40a3-94c2-39898f524b61.png)

Implementing, managing, and administering digital security solutions and enhancing security measures to meet the shifting needs of the organization are the responsibilities of cybersecurity engineers. Information is gathered from a number of sources by cybersecurity experts in order to recognize, evaluate, and report security occurrences and use both preventative and corrective methods to safeguard networks, systems, and information from harm. I can be a part of an energetic team that protect all internal and online system operations makes this position appealing to me.

The job need: the TCP/IP network firewall, routing, and switching knowledge, working with one or more hyperscalers and having experience with cloud foundation technologies and CIS Controls or NIST security frameworks, knowledge of anti-malware systems, cryptography, authentication, and authorization, experience with online filtering, mobile device security, email security, and other application level security measures, knowledge in many scripting languages and DevOps for Linux, Windows, and macOS, to secure sensitive information, having experience on configuring and hardening systems, understanding of federation technologies and principles. 

Currently, I have basic TCP/IP network firewall, routing, and switching knowledge, the cryptography knowledge and learning the security test now.

In college, I can get the knowledge of anti-malware systems, cryptography, authentication, and authorization, I can select some course about cybersecurity like security test, web security. And do some programs in course. When I graduate or in third year I go to some big company to practice and get the experience about cloud foundation technologies and CIS Controls or NIST security frameworks.

Personal Profile 
1.The results of an online Myers-Briggs test:
https://www.16personalities.com/profiles/1ba6396754ced

![image](https://user-images.githubusercontent.com/110008240/184796984-25348d92-4b1a-401c-bf13-e96d24c76b38.png)

2.The results of an online learning style test:

![image](https://user-images.githubusercontent.com/110008240/184797011-ccb9cab2-5606-4f4e-9439-7c5b4e5c11c4.png)

3.The results of Big Five Personality test. 

![image](https://user-images.githubusercontent.com/110008240/184797043-649b0704-b1c6-4f84-8f93-1167e0919279.png)


The results of these tests have allowed me to understand myself better and that I am a very introverted person. In a team, I should be bolder to communicate with others, express my thoughts more, and become more outgoing, instead of not communicating with others. When forming a team, it is very important to be good at communication, each doing their own things without communication is not a team at all. Only by discussing, expressing and accepting opinions together and working together is an excellent team.

Project Idea 

For this project, I plan to use an old mobile phone and an old computer to make a set of AC+AP devices to support the wireless network at home. This is a simple and feasible plan, and the mobile phone can connect to the network through the network cable and turn on the hotspot to achieve wireless network coverage. Old computers can install soft routing and plugins to achieve the functions of AC. I think this is a fascinating idea, because there is no need to pay extra for expensive AC+AP equipment, and it is more environmentally friendly to use old mobile phones and old computers at home.

A few months ago, I spent $2,000 to install a set of AC+AP equipment for my house, which achieved full WiFi coverage in the whole house, but I think this is an unnecessary expense, and the effect of these pieces of equipment is not worth the price. At the same time, I cleaned up the room and found a few old mobile phones. Looking at them, I did not know what they were used for. It was a pity that they were useless. Suddenly, I had a flash of inspiration. The phone can turn on the hotspot to receive the signal. Can't it be used as a WiFi booster, but will it be unstable? I looked at my old computer again and found a device on the Internet that could connect the mobile phone to the network cable. Then I can use the old computer to install a soft router as an AC, and the mobile phone is connected to the network cable as an AP, forming a network for ordinary households. 

My idea is similar to the effect of the existing AC+AP networking solution, but it does not need to spend too much money to achieve WiFi coverage in the whole house without dead ends, which is suitable for large villas or large flats. Wherever you go, the mobile WiFi can be switched seamlessly. In other words, the whole house is covered by the same WiFi, but different AP devices send different rooms. Using a mobile phone as an AP device not only gives the old mobile phones in the home new uses, but can also be used as an intelligent control panel to control the smart home in each room. As the central AC, the old computer needs to install the Windows system, then install the virtual machine on it, and install the soft routing in the virtual machine, such as OpenWRT. This is a highly playable soft routing system, which can install many plugins. The most intuitive function is significantly increasing the network speed, which can reach the upper limit of the operator's bandwidth (wired network). In addition, a VPN can be installed on the soft router so that the devices in the network can use the VPN to surf the Internet at the same time, without each device being required. All of them have a separate VPN. In other words, the entire network is in a VPN environment, which is very convenient to use. For families with many smart homes, there is no upper limit for the use of soft routing, and the capacity of conventional routers may be bottlenecked.

Install the Windows system on an old computer (at least 4 GB of memory and 128 GB of solid-disk space). Virtualizing an OpenWRT as a soft router through Hyper-V, 2 cores and 1G memory is enough. The host and the virtual machine are connected through a virtual network card, and the host accesses the Internet through the virtual machine. The on-board network card and PCI-E network card of the host are directly connected to OpenWRT, and then one network port is connected to the optical cat bridge, and the Internet is dialed up through OpenWRT, and the other network port is connected to the wireless router as a wireless AP. The advantage of Hyper-V is convenience, which is much more convenient than docker or VMWare Workstation. This host does not need to be connected to the monitor nor to the keyboard because it is rarely a problem. As an AP mobile phone, you need a two-in-one network cable charging adapter (as shown in Figure), and then you need to write software that can call the network cable of the interface and open the hotspot to realize data exchange.

![image](https://user-images.githubusercontent.com/110008240/184797202-b0d6dd25-be58-4a47-ab47-5662c57adf8e.png)


If the project is successful, people who like to toss and have specific professional knowledge can use my solution to DIY their own whole-house AC+AP networking. However, due to the limitation of mobile phone power, the WiFi coverage range may not be as far as professional AP devices, or it may not be stable and need further improvement. The heating of the mobile phone is also a problem, but it can be solved by installing a fan that cools the mobile phone. In addition, the power consumption of this solution will be higher than the usual AC+AP solution, and it will cost more in electricity bills. This development allows the old mobile phones and old computers at home to be used, which is more environmentally friendly.
