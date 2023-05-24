# Contextual-Integrity
Contextual Integrity –  One of the least understood and contentious threats to privacy in the age of information technologies is the practice of public surveillance and sensitive data exchange. 
Carpenter and Dittrich’s suggestion for a reframing of research protection principles from “human subjects” to “human harming” reveals a path toward closing this particular conceptual gap. In each conceptual gap described above, avenues for reconciling the ethical dilemma and the goals of the research projects can potentially be found. To help provide a possible path for researchers, Nissenbaum’s (2004, 2010) theory of “privacy as contextual integrity” is a useful heuristic to guide ethical decision-making in big data research projects. Contextual integrity is a benchmark theory of privacy, a conceptual framework that links the protection of personal information to the norms of personal information flow within specific contexts. Rejecting the traditional dichotomy of public versus private information, the theory of contextual integrity ties adequate privacy protection to the preservation of informational norms within specific contexts, providing a framework for evaluating the flow of personal information between agents to help identify and explain why certain patterns of information flow are acceptable in one context, but viewed as problematic in another.


Steps involve modeling the existing and new contexts, allowing to whether the new process significantly violates the entrenched norms of the context. 
Describe Information Flows:
The first step in applying contextual integrity’s decision heuristic is to identify the flows of information manifest in the context
Identify the Prevailing Context:
Identify Information Subjects, Senders, and Recipients
In the context of online platform, information subjects are the users of the site who have created accounts and provided profile information. The senders of information are users who make their profiles visible to other users. And the recipients include the online service, other users of the service, and, to a lesser extent, the public who might have access to a limited set of profile data via search engines.
We Identified  the Transmission Principles as:
Transmission principles are the rules that govern information sharing within a particular context and become the basis for context-specific informational norms. 
1.Approriateness : Defines what information is appropriate to revel with in the particular context and capturing how people discriminate in the kinds of information they are sharing according to the context of that relation
2.The norm of flow distribution : This argues that the distribution of information should and must maintain context and clear valid consent in which the information has been shared.
Detail the Entrenched Information Norms
Entrenched informational norms describe the existing practices that prevail in a given context, encompassing the flows of information, transmission principles, and expectations of the actors involved. 
1.Following the norms of a contextual approach to privacy
2.Emphasis on understanding and respecting the conditions and context of the induvial decision to disclose data
3.The concept of network privacy- that individuals lack full control over how and what information about them is shared online and the privacy is collaboratively managed by both induvial and the other users of the platform
This highlights how the features of various platforms afford different outcomes, with some sites affording high visibility of content and others affording a greater degree of obscurity. It is suggested that the collective nature of privacy in these spaces leads users to engage in a variety of privacy management strategies and constant curation of connections and content and use more private platforms for sensitive disclosures
4.Context matters not only in understanding an individual’s privacy needs and behaviors but also in addressing regulatory challenges in a globalized world. Like PIPEDA (Personal information protection act), GDPR, HIPPA
These regulations focus on direct and pre-emptive regulation of the collection of personal data and its purposes. 


FRAMEWORK / WORKING MODEL :
Proposed Model :
Using python, I have used basic encryption and decryption techniques using hashing to store the encrypted message on the server.
This helps in encrypting the user’s personal data and storing the encrypted data on the server side
With strong access controls and user privileges, the Administrator will hold accountable for the security and protection of the data.
Organizations can still be able to provide the service with minimal information with decrypted data.

When the user enters the information, the information is encrypted
Using various cryptographic methods, we can use the key to decrypt the data when needed.
This encrypted message is stored in the server avoiding risks of a data breach.
To verify the user, the company can either use OTP for online assistance or biometrics for banking and health care.
Given that it has decrypted the IDs and is aware of which have been requested, the server has the option of returning messages that are encrypted.
The way our system is currently being used. Alternatively, the server might return a list of IDs and the client could send a second request for the messages themselves.


We use tuple mapping to update, search or store the information. 
Let me explain this mapping with an example, Alice will use the keywords ( that is personal information or data) to be stored, using symmetric encryption this program will produce hashes of the keywords with a secret key. Bob(an associate from the company) stores this information of Alice’s file on the server. IF Alice wants to retrieve her information, she sends the hash of the keyword she needs. Using the hash, bob maps to the files in the server. Hashing technique generates unique hashes for every keyword and is character sensitive. Using these hash cipher keywords, bob will send the corresponding files to Alice. 
