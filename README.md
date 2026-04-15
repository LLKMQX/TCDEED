EEG Emotion Dataset (Coming Soon)
This repository is intended to present an upcoming EEG-based emotion recognition dataset and its associated code.

This dataset was collected using a 60-channel ESI NeuroScan system and contains multi-channel EEG signals recorded from participants under audiovisual stimuli. It is intended to support research in affective computing and brain–computer interfaces. All experiments were approved by the ethics committee, and written informed consent was obtained from all participants. 

The dataset and related code will be released on a public platform after the official publication of the associated paper, accompanied by the necessary experimental description and user guidelines.

This dataset contains EEG data from 15 participants. Each participant’s data file is named numerically from 1 to 15 and saved in .mat format. Within each participant’s .mat file, there are 15 segments of EEG data, named data_1 to data_15. The corresponding emotion labels are [0, 0, 0, 0, 0, 1, 1, 1, 1, 1, 2, 2, 2, 2, 2], where 0, 1, and 2 represent different emotion categories. It should be noted that the presentation order of emotional stimuli during the experiment was not fixed as shown above; however, during data organization, samples belonging to the same emotion category were grouped together for subsequent processing. All data have undergone standardized preprocessing procedures.
<img width="782" height="511" alt="Data_TCDEED" src="https://github.com/user-attachments/assets/52b87e55-92ce-4e7a-8ab8-ceef6f23e148" />


The electrode distribution is shown in the figure below.
![EEG_Channels](https://github.com/user-attachments/assets/19603db8-1ef0-43ec-97a1-02b7d47dd49b)

📌 Status:
Currently under embargo until paper publication. The data and full documentation will be released here soon.

If you're interested or have any questions, feel free to reach out via [linmenxin9@gmail.com].

<!--
**TCDEED/TCDEED** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
