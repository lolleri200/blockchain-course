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
     - Tor aims attacks harder, but not impossible.
