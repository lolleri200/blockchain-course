x) Tor: The Second-Generation Onion Router:
    - Tor is know to:
    
      - To be an anonymity network designed to protect people's own privacy by preventing the attackers from linking communications or identifying users. The development is prioritized in the following farctors:
      
      1. Deployability: Tor must be practical in the real world, requiring minimal resources (e.g., bandwidth), not imposing heavy liabilities on the operators, and avoiding complex implementations or external software dependencies. It will also avoid requiring 
         non-anonymous users (e.g., websites) to run Tor so no one can access the Tor only websites.
      2. Usability: A user-friendly design is critical for wide adoption, as more users improve anonymity. Tor is designed to work with existing applications, minimizing delays and configuration steps. It is compatible with common
         operating systems, for example: Windows, Linux and MacOS.
      3. Flexibility: Tor's protocol is designed to be flexible and research-friendly, allowing for future improvements and experimentation without reinventing the whole system.
      4. Simple Design: Tor focuses on a simple, well-understood design, avoiding unnecessary complexities. It incorporates well-accepted techniques for anonymity without introducing unproven features that could complicate it's security.

   - The things the Tor is not:
     
      - Not a peer-to-peer, that means that Tor does not aim to be a fully decentralized, peer-to-peer system like some other anonymity networks like: Tarzan or MorphMix, that are still facing with challenges.
      - Not Secure Against End-to-End Attacks, that means that Tor does not fully solve end-to-end attacks like timing or intersection attacks, but some straties, such as users running their own routers can help with that.
      - No Protocol Normalization, that means that Tor does not modify protocols, such as HTTP that helps with obscure differences between users, that requires external tools like Privoxy for anonymity during complex interactions.
      - Not Steganographic, that means that Tor does not attempt to conceal the identity of the users connecting to the network, so it focuses on preventing traffic analysis, and not hiding who is connected to it.

  - Adversary Model:
    
     - Tor will assume an adversary capable of monitoring traffic, controlling some routers, and launching various different attacks like traffic analysis, timing attacks, and compromising routers.
     - Tor is focused on defending traffic analysis attacks, rather than more sophisticated adversaries who might try to fully compromise user identities through end-to-end correlations.
     - Tor aims to make attacks harder, but not impossible.

   De-Anonymisation Attacks on Tor: A Survey:
   
   - Anonymity networks like Tor are used to protect online privacy. Tor is the most popular such network that, ensures anonymity for both users and services.
   - However, Tor has also been misused for illegal activities, such as hosting drug-selling sites, botnet control servers, and censored adult content. This has led governments and law enforcement agencies to explore ways of de-anonymize Tor users,
     disrupt its operations, and bypass its censorship evasion.
   - This kind of survey paper reviews are known attacks on Tor, identifies de-anonymization techniques, and analyzes their effectiveness. It also suggests improvements to Tor and to counter this kind of attacks.

   - Over the past few decades, online services have significantly impacted daily life, raising concerns about how to browse the Internet while maintaining privacy.
   - Privacy is especially crucial for whistle-blowers, such as citizens of totalitarian governments, and sensitive communications within military and business organizations. This need has driven the development of anonymous communication systems.
   - Early systems like Mix-Net, Babel, and Mixminion have faced challenges with high latency, and were not widely adopted. They have now been replaced by low-latency systems that are more practical for current use cases.

   - Tor is a widely used anonymity network that is employing onion routing. Tor is an overlay network, that is built on the Transmission Control Protocol, where the users connections are routed through three voluntary relays to reach a destination servers.
     These key components are:
     
     - Onion Proxy, that is a small software installed on the user's device that facilitates communication with the directory servers, establishes Tor network connections, and handles user application traffic. And it is also called the Tor client.
     - Directory Servers are referred as Trusted servers that maintain and share information about the network’s status, including relay availability, and also exit policies. The online proxy downloads of this consensus document to select relays and establish a secure
       communication circuit.

   Halonen, Ollikainen, Rajala 2023 video:
   
     - The video https://www.youtube.com/watch?v=bDzVevtZiWE about Phisticks is very informative and shows what not to do when leaving a company owned computer. Users should always lock the computer so no one can enter. And also it is important to never plug in an 
       unknown USB stick, because as shown in the video it may contain viruses that can steal your personal information such as important email services passwords.


Sources:
https://css.csail.mit.edu/6.858/2022/readings/tor-design.pdf

https://ieeexplore.ieee.org/ielx7/9739/9621320/09471821.pdf


a) I installed the Tor browser using the wget https://www.torproject.org/dist/torbrowser/14.0.3/tor-browser-linux-x86_64-14.0.3.tar.xz command and extracted the file. And then I ran the Tor Browser Setup file.
   <img width="620" alt="image" src="https://github.com/user-attachments/assets/b8e6457c-47b2-48dd-b374-ca7becc81c4b">
   And then I connected to the tor browser. 
   <img width="1001" alt="image" src="https://github.com/user-attachments/assets/07ca9939-ed60-4e31-b4e5-5ac5c7a07ca4">

b) I decided to use a Tor search engine called Ahmija.
   <img width="748" alt="image" src="https://github.com/user-attachments/assets/c0e1131b-9d20-4ac4-8de1-a6e30ccab074">
   I was searching for human rights or civil rights organization with a Tor search engine:
   <img width="520" alt="image" src="https://github.com/user-attachments/assets/1ce44be7-1dd9-4fd6-9345-b31ed6be93f1">
   <img width="867" alt="image" src="https://github.com/user-attachments/assets/4aa90dd5-9350-4fdc-99dc-f9725afcfc93">
   And found different archived news.
   I searched for Marketplaces in the Tor search engine and the first page I opened has drugs for sale right at the front page...
   <img width="1031" alt="image" src="https://github.com/user-attachments/assets/dc8dd6ea-6d63-42a7-b729-558251223473">
   Next I searched for Fraud in the Tor search engine and ended up at the Dark shop that is there since 2015. The page seems to be selling fake money.
   <img width="742" alt="image" src="https://github.com/user-attachments/assets/6fac70fd-e082-4818-9a40-ce8a2ed0805d">
   Next I searched for Forum in the Tor search engine and found a Forum called Dark Rewviews. And went to a thread called DEEP Questions and Answers.
   <img width="920" alt="image" src="https://github.com/user-attachments/assets/38cdcb5d-1211-49bc-9c3b-1b36d91e7893">
   Most of the threads seems to be ads for a market, hacking services and Bitcoin selling threads.
   <img width="1406" alt="image" src="https://github.com/user-attachments/assets/aa9b9f21-80fc-4320-93ad-66e07be996fd">
   

   



   
   
   

   

   

