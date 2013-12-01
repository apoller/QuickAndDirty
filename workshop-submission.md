## Title ##

####Authors####

[Andreas Poller, Fraunhofer Institute for Secure Information Technology, Rheinstrasse 75, 64295 Darmstadt, Germany](mailto:andreas.poller@sit.fraunhofer.de)   
[Andreas Kramm, Goethe University, Grüneburgplatz 1, 60123 Frankfurt am Main, Germany](mailto:akramm@rz.uni-frankfurt.de)
  
####Abstract####

_Investigating privacy practices of online social network (OSN) users is a difficult task because (a) these practices rely on technical privacy controls combined with various other strategies like self-censorship or information obfuscation, and (b) for practical reasons, it is difficult to actually observe this complex user behavior and practices in such digital environments. We iteratively developed a research design that combines (a) participant observation with a privacy-friendly tracking tool for user actions and privacy settings in OSN, and (b) qualitative semi-structured interviews. Applying the research software requires little extra effort but considerably improves our interviews with participants and later data analysis. However this benefit comes for the cost of developing our toolkit. We are wondering whether there is more potential in the research community to (collaboratively) develop similar toolkits allowing significant improvements of research outcomes with limited extra effort in study execution._

###Introduction###

Many research projects aim at in-depth understanding of Online Social Network (OSN) users’ privacy strategies. One observation stands out in existing work: users’ privacy strategies rely only to a limited extent on privacy controls provided by the OSN software. Other means such as self-censorship, obfuscating information before sharing, multiple OSN accounts supplement or replace the use of OSN privacy controls.

When developing research designs for investigating how user try to manage and maintain their privacy in OSNs, we have to take into account this complexity and contextuality of user’ privacy strategies [1]. However, despite the complexity of our setting, we yet have to come up with research approaches still manageable in the field with limited research resources. In other words, we have to align our desire for broad and rich insights into user practices, and the practical feasibility of empirical field research approaches. [2] When using research designs with a too-narrow scope, we may not observe what is necessary to understand users’ strategies to their fullest extent. Applying very fine-grained, extensive approaches such as combinations of interviews, surveys, walkthroughs or diary studies, would be time-consuming and thus expensive for researchers as well as considerably demanding for study participants. Moreover, such procedures may be intrusive regarding participants’ privacy, e.g., when doing walkthroughs or screen capturing, or even error-prone when relying on self-reporting techniques where users may hesitate to provide sensitive or embarrassing information.

We present our two-stage research approach to investigate OSN users’ privacy strategies that combines (1) technical data elicitation about what our study participants actually do in OSNs, and (2) semi-structured interviews where our participants describe how they conceptualize and perceive their own and others actions in the OSN. We developed this approach iteratively after experiencing shortcomings with other empirical research methods and while we recognized that we have to extend our data collection to better understand users’ privacy strategies. Our approach allows us to focus interviews to participants individual OSN usage and to avoid issues of self-reporting. We forward the software we developed for our investigations to the research community allowing other researchers to incorporate it into their own research designs.

###Development of Our Research Approach###

We iteratively developed and continuously refined our research procedure over a period of about three years: we first started with one-on-one interviews. After we recognized that our study participants barely remember their own privacy settings, we used questionnaires to capture them. However, especially Facebook privacy settings turned out to be very complex. Thus, we decided to supplement our questionnaire with a simple software tool for supporting interviewers in gathering interviewees’ Facebook privacy settings.

We realized that in order to better understand participants daily practices, tracking participants’ actions over a certain period of time would be helpful. To this end, we tried out diary studies asking participants to take notes on their actions performed in the OSN. However, it became apparent that these studies are of limited benefit as our participants often perceived them as unwieldy and too time consuming. As a consequence, we developed our software tool further, and implemented a web browser plugin that can record actions participants executed in Facebook during a limited observation period. The new tool also contained a comment function, allowing participants to scribble down their experiences in situ and by using a diary function.

Within the course of our project, we experienced that not only type and time of actions of our participants is interesting to understand their usage practices, but also the structure how actions relate to each other. We added a feature to the software to additionally capture with whom users interact as well as the content on which interactions took place, e.g., a specific newsfeed item commented by the participant several times. However, for privacy reasons, our web browser plugin does not capture real names or shared content. Instead it records pseudo-unique identifiers, allowing us to find repeating action targets or interaction partners.  

With the increasing amount and complexity of collected data we developed a need for visualization and analysis tools. Currently, we have software support to analyze the flow of interactions, repeating interactions targets and partners, and preferred OSN functions.  

###Example Study###

####Procedure####

For a recent study with our research methodology, we recruited 15 active users of Facebook. All participants had to install our self-developed web browser plugin on their own personal computer to track type and timestamp for each user interaction with Facebook, applied privacy settings, and pseudo-unique identifiers revealing the structure of users’ interactions. The latter includes information such as how often users interacted with particular other users, with whom they shared information on Facebook’s Timeline, which Timeline posts they “liked” or commented on, and in which sequences that happened. We also asked participants to use our plugin to comment on their interactions in Facebook, and to write into a digital diary if something happened that kept their attention.

We analyzed plugin-collected data regarding (1) how permissive were the privacy settings and (2) which interaction functions of Facebook were used and how was this done. Based on the collected data, we prepared different interview questions asking to explain observed usage practices and particular actions, or provided comments. We incorporated these questions participant-wise into our interview guideline. During the following semi-structured interviews we asked participants to (1) describe their usage practices, (2) explain their privacy settings, and (3) to tell us their experiences with Facebook. 

####Practical Benefits of Our Approach ####

We observed that our approach helps to overcome several problems of self-reporting: users forgot to explain important aspects of their practices, misunderstand technical functions thus giving misleading answers, or users provide hard to evaluate estimates on how often they interact with the software.  

For instance, one of our interviewee stated that he did not chat a lot. But tool elicited data indicated differently. Confronted with the data this user added that he frequently used the chat to stay in contact with his brother and his girlfriend. He simply forgot in the interview. Because of the plugin-collected data we also recognized that interviewees may refer to a function by name but actually mean another, e.g. speaking of chats when they mean private messages. Moreover, this data also helped us to verify and quantify self-reporting: an interviewee claimed that she commented "very, very seldom". However, according to her data she commented six times during the two weeks which was an average value in our study. Another interviewee claimed to carefully select her Facebook contacts, and, indeed, she rejected three contact requests during our observation.

A benefit of our individualized interview questions is that they allowed us to focus on participants’ actual activities. For instance, one interviewee reported on his use of chat-like comment threads on Timeline items only after the interviewer asked to explain a sequence of comments visible in the participant’s activity data.

Combining interviews and plugin-collected data supply our understanding of users’ practices, of concepts of the technical environment and experiences users remember as meaningful to them as well as data on actual practices and comments in situ. Thereby it enables us to understand individual usage contexts. For instance, one interviewee explained a single chat on-off-sequence we observed in her data with a mistake, and stated that she typically uses private messages only. However, upon following up on that statement, she realized that earlier in the interview she mistakenly had spoken of "chatting" when actually she meant "to use [Facebook’s] regular message program". She considered the chat function as "totally stupid" because she had problems with being visible to others.  

###Discussion and Conclusion###


###References###

[1] boyd, D., Marwick, A.E. Social Privacy in Networked Publics: Teens’ Attitudes, Practices, and Strategies. In A Decade in in Internet Time: Symposium on the Dynamics of the Internet and Society. 2011
[2] Rotman, D., Preece J., He, Y., Druin, A. Extreme Ethnography: Challenges for Research in Large Scale Online Environments. In Proc. 2012 iConference, ACM (2012), 207–214
