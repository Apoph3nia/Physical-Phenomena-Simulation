# Physical-Phenomena-Simulation

Unity Editor Version: 6000.2.0b8

In Unity Hub > Installs (TAB) > Install Editor > Pre-releases > Select Unity 6000.2.0b8 (Beta)

Note: Or wherever you find the required version.

# Project opening process

Unzip the .zip file.

In Unity Hub > Projects (TAB) > Add > Add project from disk > Select the folder of the project.


# Set-up

File > Build Profiles > Select the Physical Phenomena Simulation > Press the Switch Profile button.
<img width="912" height="763" alt="image" src="https://github.com/user-attachments/assets/d7db6951-950c-49ec-a149-7abdc73bd0aa" />


#  AI Assistant Setup

Go on https://huggingface.co/ and Sign-up / Log-in. 

Profile > Access Tokens > Create new Access Token > Make sure the field Type is set to Fine-grained > On the Inference options check them all > Create Token > Copy the token.


In Unity you can assign that token on the Inspector tab of the AI Assistant Object (in its AIAssistant.cs script). You need to do that for both Simulation_1 & Simulation_2 scenes which are located in Assets > Scenes.

<img width="304" height="258" alt="image" src="https://github.com/user-attachments/assets/10ca6cad-08a2-4eb7-b382-63191d318808" />

<img width="639" height="308" alt="image" src="https://github.com/user-attachments/assets/98b5201a-4912-4b09-acd8-6da8a4c1e02c" />

<img width="612" height="913" alt="image" src="https://github.com/user-attachments/assets/577ccab8-bd1c-41b2-b7c2-7231fcc9cd91" />



You also need to request access to a selected model from huggingface. For example, for https://huggingface.co/meta-llama/Meta-Llama-3-8B-Instruct, you need to fill a form, like name-surname, date of birth, etc., and submit it. It usually doesn't take too long for them to grant you access. Now you can start using it.
