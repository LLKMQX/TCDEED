EEG Emotion Dataset (Coming Soon)
This repository is intended to present an upcoming EEG-based emotion recognition dataset and its associated code.

This dataset was collected using a 60-channel ESI NeuroScan system and contains multi-channel EEG signals recorded from participants under audiovisual stimuli. It is intended to support research in affective computing and brain–computer interfaces. All experiments were approved by the ethics committee, and written informed consent was obtained from all participants. 

The experiment consisted of 15 trials, each corresponding to an emotional video clip, including 5 positive, 5 negative, and 5 neutral videos. The total duration of the experiment was approximately 60 minutes. As illustrated in the figure, each trial comprised four consecutive stages: task cue, video stimulus, self-assessment, and rest.

During the task cue stage, a white fixation cross was presented at the center of a black screen for 10 seconds, instructing participants to focus their attention and prepare for the experiment. Once the cue disappeared, the experiment directly entered the emotion induction stage, during which the corresponding emotional video clip was automatically played. This stage aimed to help participants quickly immerse themselves in the target emotional context and form a stable emotional experience. No additional cognitive tasks were required, thereby reducing extra cognitive load.After the video playback, the experiment proceeded to the self-assessment stage. Participants were required to rate the intensity of their current emotional experience within 10 seconds using a 1–9 scale, with responses recorded by the experimenter. These ratings were used to validate the effectiveness of emotion induction and to provide reference information for subsequent EEG signal analysis.Following the assessment, a 30-second rest period was provided. During this stage, the screen switched to a white background to allow participants’ emotions to gradually return to baseline. This design ensured the independence of each trial and minimized emotional carryover effects between adjacent trials.
<img width="864" height="243" alt="image" src="https://github.com/user-attachments/assets/3ccee7ff-4b82-4183-9483-1f62463ae1d0" />

This dataset contains EEG data from 15 participants. Each participant’s data file is named numerically from 1 to 15 and saved in .mat format. Within each participant’s .mat file, there are 15 segments of EEG data, named data_1 to data_15. The corresponding emotion labels are [0, 0, 0, 0, 0, 1, 1, 1, 1, 1, 2, 2, 2, 2, 2], where 0, 1, and 2 represent different emotion categories. It should be noted that the presentation order of emotional stimuli during the experiment was not fixed as shown above; however, during data organization, samples belonging to the same emotion category were grouped together for subsequent processing. All data have undergone standardized preprocessing procedures.
<img width="782" height="511" alt="Data_TCDEED" src="https://github.com/user-attachments/assets/52b87e55-92ce-4e7a-8ab8-ceef6f23e148" />


The electrode distribution is shown in the figure below.
![EEG_Channels](https://github.com/user-attachments/assets/19603db8-1ef0-43ec-97a1-02b7d47dd49b)

📌 Status:
The dataset and related code will be released on a public platform after the official publication of the associated paper, accompanied by the necessary experimental description and user guidelines.
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
