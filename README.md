# FaceBook-Api-Clique-Analyzer
**About**
The goal of this project is create a windowed application that provides basic facebook login features, aswell as clique analysis and information exportion (txt/xml).
this project also has a Sequence/Class diagrams for the sake of documentation


**The Methods**

We use C# Form class and FacebookWrapper api features aswell as threading for user friendly interaction with the program.
* Design - a windows form, the UI which mainly interacts with the Facade class
* Facade - a class library, has 3 main classes which correspond to the 3 tabs in the UI design, allows the user to interface with facebook(wrapper) easily and securely
* Builder - a class library, dictates which format and amount the cliques will be exported
* Proxy - a class library, saves a proxy of the "member" class, saving unnecessary calls to facebook if we find the same member in diffrent cliques
* logic and utility - clique data creation and analysis, respectively
![image](https://user-images.githubusercontent.com/78749321/134714620-069cb8a5-363c-442e-b28e-fd0efa8a408f.png)

![image](https://user-images.githubusercontent.com/78749321/136249027-7db5aa7d-e853-4d48-91f7-3a53971c3509.png)



