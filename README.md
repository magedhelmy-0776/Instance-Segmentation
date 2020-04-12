# Why Designing Transparent AI Matters?  <br/>

## Building a fair algorithm in an unfair society  <br/>

 
**Abstract**: 
<div style="text-align: justify ">
Although Artificial Intelligence (AI) has proven to have great potential in many industrial applications [1]–[3], research lacks sufficient methods to adequately interpret and decode the internal logic of such high performing algorithms [4]. Highly performing algorithms suffer from the black-box phenomenon where the calculations cannot be validated, and the methodology behind the algorithm cannot be verified [5]. This poses several ethical challenges since such systems can reflect or amplify the existing biases of its implementers and the dataset leading to discrimination against minorities and may repel society from using such promising technologies. In this article, we argue that using AI technology without the appropriate assessment and understanding of how it arrives at its decisions outweighs the benefits and can harm the individuals and society.
</div>  <br/>

**Background**:

<div style="text-align: justify ">
Deep Neural Networks (DNN), which are a subset of AI, is behind the majority of the recent successes in AI [6]. DNN can outperform a human expert in an infinitely large amount of datasets and can make more informed decisions in a shorter period [7]. For example, a DNN that is trained to diagnose cancer can be more accurate and faster than a radiologist with a Ph.D. [8]. However, these algorithms are highly complex, where the relationship between the data (input) and the conclusion (output) is uninterpretable [9]. Such algorithms pose an ethical challenge since they may inherit biases from human prejudices, which can lead to unfair decisions [5]. In light of this ethical challenge, we will present some examples of ethical dilemmas that may arise from using such high performing black box AI-based systems in decision-making processes that can have a significant impact on an individual’s human rights.
</div>  <br/>

*I. Interpretability in AI*

<div style="text-align: justify ">
An interpretable AI is an algorithm that can be explainable by its implementers to society and individuals (i.e., regulatory, customers, employees). For instance, the algorithmic patterns of how the conclusion has been reached are calculable and verifiable. Many high performing DNNs are not able to present the logic of the outcome due to the depth of the networks, and trying to simplify the network to gain interpretability will significantly reduce accuracy [10]. Furthermore, an interpretable algorithm will allow audibility where an algorithm can be reviewed, tested, and refined to reflect the moral codes and principles of society. However, the literature proves that auditable algorithms have reduced performance and, in many cases, minimal functionalities [11]–[13]. Some examples of commonly used algorithms where performance and interpretability correlates are GoogLeNet [14] with 6.7 million parameters and VGGNet [15] with 138 million parameters. Therefore, an ethical dilemma is using these deep neural networks that are capable of highly sophisticated functionalities like analyzing video, audio, and texts in an uninterpretable manner, versus using an interpretable algorithm with minimal functionally and low accuracy. How much accuracy and features are we willing to sacrifice to satisfy the transparency dilemma?
</div> <br/>

<div style="text-align: justify ">
An example of highly opaque DNNs that has significantly increased the safety of the roads is Tesla’s autopilot system (TAS) [16]. TAS crowdsources different types of structured and unstructured data from its cars and combines them using highly deep learning algorithms [17], making it the car with the lowest probability of injury [18]. Another example of high performing but opaque systems are the AI’s algorithms deployed in smart homes. Similar to Tesla’s autopilot; it combines sensor data using deep learning algorithms to arguably increase the quality of life in homes for senior citizens and persons with disabilities [19]–[22]. 
</div> <br/>

<div style="text-align: justify ">
However, not all high performing algorithms have been transformative. An example where an interpretable algorithm could have prevented an erroneous mistake was Microsoft AI chatbot Tay which was shut down 16 hours after launch as it turned into a Hitler-loving sex robot [23]. Another dilemma in the medical world is when the tissues of a healthy-looking man are flagged as cancerous to the algorithm. Although the prediction happened to be accurate since the algorithm has learned from the data of previous patients, it could not explain how it arrived to this conclusion. This leaves the doctor and the patient with a severe dilemma since it will be hard to come up with a preventive measure without knowing what the risk factors are. 
</div> <br/>

<div style="text-align: justify ">
Few examples where auditability matters are COMPAS [24], which is used by the U.S. courts where the algorithm is discriminant against minorities based on an ethnic prejudice in the input dataset. Another example is the algorithm used by the United States Immigration and Customs Enforcement (ICE). A risk-assessment on ICE revealed that the algorithm was manipulated to produce only one recommendation, “..detain..” all immigrants in custody [25]. Last but not least, Amazon recruiting tool [26] preferred male software developers over females due to the dataset reflecting male dominance in the tech industry. 
</div> <br/>

<div style="text-align: justify ">
An auditable algorithm could have played an essential role in all the previous examples by allowing an unbiased third-party to verify the algorithm logic against ethical principles before deployment to prevent unjust discrimination. Society loses trust in such promising technologies when either directly or indirectly, they amplify discrimination and oppress specific individuals based on an uninterpretable logic from the dataset [27]. 
</div> <br/>

<div style="text-align: justify ">
One can argue if society is even ready to adopt such high performing algorithms when direct manipulation (in the case of ICE) or indirect human bias (in the case of Amazon) can have adverse effects on individuals? Society has witnessed the devastating effects of similar technologies[28], [29], amongst others, the atomic bomb, and the AK-47 (responsible for more deaths than any other rifle due to the cheap mass production design[30]). As of the evidence we have, one can conclude that an interpretable & auditable AI algorithm is inevitably more beneficial than a high performing algorithm that is not interpretable nor auditable.  
</div> <br/>

*II. Solutions that work, kind of.*

Tech leaders like Facebook and Microsoft are investing heavily in developing tools that attempt to tackle biases in DNNs while trying to maintain all the functionalities in a high performing algorithm[31] - however useful, this does not reveal the black box but merely tries to solve the symptoms of the problem. Moreover, companies should understand that this challenge requires more than a technical fix. For example, the lack of diversity amongst the teams building the technology, and collecting the dataset makes it more challenging to overcome biases. Human biases and prejudice implicitly gets reflected in the data collected [32]. Therefore, tech companies should also invest in educating the developers, programmers, and the data collectors to understand the moral principles and consequences that may result from developing such technologies solely based on results and profit. Moreover, companies should invest more in transparent AI to make it possible to scrutinize the logic and accustomed it to social and judicial expectations.

Furthermore, there are several methods in the literature on controlling the quality of the input to address algorithmic biases, which inevitably controls the output of the algorithm [33]. However, right, it will not be straightforward to detect if the dataset has been tampered with or hacked since the logic of the algorithm is still a black box. There are some other methods proposed that can reconstruct the algorithm to an extent by reverse-engineering the output into the input [34]. However, this does not adequately address the issue of the black box but rather try to deduce the algorithm based on experimental science. 

To conclude, by favoring a transparent AI approach over a highly functional one, it will encourage AI implements to first understand the technology more thoroughly before implementing it. This may in turn reduce unpropitious consequences. 

*III. Wait...What about Companies Competitive Advantage?*

Companies trade secrets can be lost if the algorithms are open for the public to test and scrutinize. Companies can also lose their competitive advantage if the logic gets replicated by other companies in countries where trade secrets and protection are not enforced or even applicable. However, when it comes to AI, nearly all tech leaders like Google [35] and Facebook [36] have open-sourced their AI technology. While debatable on why the tech leaders decided to do that, up to this day, regulations of applying AI have no satisfactory legal terms where companies can disclose their algorithms without harming their competitive advantages since the law stresses the auditability of the algorithm [37]. Therefore, as more companies thrive to open-source their AI technology to the public, this will inevitably increase the public trust in such emerging technology

Moreover, after the introduction of the GDPR in May 2018, the EU has created a panel to present a study on the governance of algorithmic accountability and transparency [37]. The study, which was published in April 2019, has concluded that there is no convincing evidence that black box algorithms provide the necessary safeguards required to the people and society when using such technology. The panel also recommended establishing a permanent global ‘Algorithm Governance Forum’ and giving regulatory agencies the rights to hold parties accountable for violations of European laws and human rights by using such black box algorithms. Another report was also released in 2019 by the EU, titled “Ethics guidelines for trustworthy AI” which stressed the reproducibility and traceability of AI algorithms [38]. Therefore, one can argue that a transparent AI might be the only competitive advantage in the future when the industrial frameworks are established and come into force.

Many companies face a competitive time pressure to get their software to market since their software must strictly adhere to its industry conformance certificates [39]. To mitigate such limitations, heavily regulated industries like aviation, finance, and medical devices have developed a set of certification models that can fast track software conformances for devices with lower risks [40]. Currently, there are no similar fast track routes to certify AI algorithms in the mentioned industries; therefore, time to market (TTM) is not a competitive factor for AI algorithms.

One can argue that the competitive advantage will belong to the companies that prioritize and prove an interpretable and auditable algorithm rather than the companies with the highest performing opaque algorithms. When the tech race is switched from the highest performing algorithm to the most interpretable and auditable algorithm, such technologies may start to gain the public trust.

*Conclusion:*

AI, and specifically deep learning, has proven to outperform human experts in their domain fields. However, such high performing algorithms come at the cost of interpretability where higher-performing algorithms are less interpretable then their lower-performing counterparts. This is due to the nature of how deep neural networks are built. The ethical dilemma is whether to use these high performing algorithms at the expense of interpretability, auditability, and transparency. 

In this article, we have presented some examples where a high performing algorithm may reinforce human biases and prejudices, and therefore a more interpretable is admissible even if it comes at the cost of losing functionalities. Creating and using interpretable algorithms can build public trust towards such emerging technologies. 

It is essential to highlight that the current solutions provided by the tech industries to deal with the black box phenomena addresses the symptoms but not the issue directly. Moreover, due to the tradition of how the industry is built, companies argue that the trade secrets will be lost if algorithms are made available for the public to scrutinize. However, it is essential to note that current regulations do not allow the deploying or usage of such high performing algorithms as it has proven to be discriminant and sexist. Therefore, at the current stage, an acceptable AI will be a transparent, interpretable, and auditable AI. 

Since the current high performing algorithm is not capable of satisfying the social and judicial expectations, a ‘watered-down’ transparent version of AI can be implemented. Algorithms transparency and accountability must be high on the agenda of AI implementers as it is the only way to gain a competitive advantage when the regulations come into force. AI implementers should understand that technologies should be made to combat discrimination and injustice and not merely reinforce human prejudices and social unfairness. 


### Get in Touch

Feel free to get in touch anywhere, anytime ! <br/>
[LinkedIn](https://www.linkedin.com/in/helmy47/) or Email me directly maged.helmy1@outlook.com <br/>

### Top contributors to this article

⋅⋅* Maged Helmy  <br/>
To contribute, simple create a pull request on the Github page! :) 


**References:**

[1]	M. Purdy and P. Daugherty, “How AI boosts industry profits and innovation,” Accenture. Frey, C, 2017.

[2]	P. Stone et al., “Artificial Intelligence and Life in 2030. One hundred year study on artificial intelligence: Report of the 2015-2016 Study Panel,” Stanford University, Stanford, CA, http://ai100. stanford. edu/2016-report. Accessed: September, vol. 6, p. 2016, 2016.

[3]	M. Chui et al., “Notes from the AI frontier: Insights from hundreds of use cases,” McKinsey Global Institute (Retrieved from McKinsey online database), 2018.

[4]	A. Adadi and M. Berrada, “Peeking Inside the Black-Box: A Survey on Explainable Artificial Intelligence (XAI),” IEEE Access, vol. 6, pp. 52138–52160, 2018.

[5]	R. Guidotti, A. Monreale, S. Ruggieri, F. Turini, F. Giannotti, and D. Pedreschi, “A Survey of Methods for Explaining Black Box Models,” ACM Comput. Surv., vol. 51, no. 5, pp. 93:1–93:42, Aug. 2018.

[6]	J. Schmidt, M. R. G. Marques, S. Botti, and M. A. L. Marques, “Recent advances and applications of machine learning in solid-state materials science,” npj Computational Materials, vol. 5, no. 1, p. 83, Aug. 2019.

[7]	M. Ide, “Human-Machine Work Teams,” Medium, 05-Jun-2018. [Online]. Available: https://medium.com/mit-initiative-on-the-digital-economy/human-machine-work-teams-2ecd8f71fd5b. [Accessed: 14-Dec-2019].

[8]	K. Hume, Designing AI to Make Decisions. 2018.

[9]	G. B. Goh, C. Siegel, A. Vishnu, N. Hodas, and N. Baker, “How Much Chemistry Does a Deep Neural Network Need to Know to Make Accurate Predictions?,” in 2018 IEEE Winter Conference on Applications of Computer Vision (WACV), 2018, pp. 1340–1349.

[10]	H. Mhaskar, Q. Liao, and T. Poggio, “When and why are deep networks better than shallow ones?,” in Thirty-First AAAI Conference on Artificial Intelligence, 2017.

[11]	M. Ananny and K. Crawford, “Seeing without knowing: Limitations of the transparency ideal and its application to algorithmic accountability,” New Media & Society, vol. 20, no. 3, pp. 973–989, Mar. 2018.

[12]	M. L. Jones, “The right to a human in the loop: Political constructions of computer automation and personhood,” Soc. Stud. Sci., vol. 47, no. 2, pp. 216–239, Apr. 2017.

[13]	J. A. Kroll, S. Barocas, E. W. Felten, J. R. Reidenberg, D. G. Robinson, and H. Yu, “Accountable algorithms,” Univ. PA Law Rev., vol. 165, p. 633, 2016.

[14]	C. Szegedy et al., “Going deeper with convolutions,” in Proceedings of the IEEE conference on computer vision and pattern recognition, 2015, pp. 1–9.

[15]	K. Simonyan and A. Zisserman, “Very Deep Convolutional Networks for Large-Scale Image Recognition,” arXiv [cs.CV], 04-Sep-2014.

[16]	“Autopilot.” [Online]. Available: https://www.tesla.com/sv_SE/autopilot. [Accessed: 20-Dec-2019].

[17]	K. Pei, Y. Cao, J. Yang, and S. Jana, “DeepXplore: Automated Whitebox Testing of Deep Learning Systems,” in Proceedings of the 26th Symposium on Operating Systems Principles, Shanghai, China, 2017, pp. 1–18.

[18]	“Tesla Vehicle Safety Report,” 08-Jan-2019. [Online]. Available: https://www.tesla.com/VehicleSafetyReport?redirect=no. [Accessed: 16-Dec-2019].

[19]	U. Cortés et al., “Assistive technologies for the disabled and for the new generation of senior citizens: the e-Tools architecture,” AI Commun., vol. 16, no. 3, pp. 193–207, 2003.

[20]	M. E. Pollack, “Intelligent technology for an aging population: The use of AI to assist elders with cognitive impairment,” AI magazine, vol. 26, no. 2, pp. 9–9, 2005.

[21]	H. R. Marston and J. Samuels, “A Review of Age Friendly Virtual Assistive Technologies and their Effect on Daily Living for Carers and Dependent Adults,” Healthcare (Basel), vol. 7, no. 1, Mar. 2019.

[22]	X. Guo, Z. Shen, Y. Zhang, and T. Wu, “Review on the Application of Artificial Intelligence in Smart Homes,” Smart Cities, vol. 2, no. 3, pp. 402–420, Aug. 2019.

[23]	E. Hunt, “Tay, Microsoft’s AI chatbot, gets a crash course in racism from Twitter,” The Guardian, 24-Mar-2016.

[24]	C. Rudin, C. Wang, and B. Coker, “The age of secrecy and unfairness in recidivism prediction,” arXiv [stat.AP], 02-Nov-2018.

[25]	N. Sonnad, “US border agents hacked their ‘risk assessment’ system to recommend detention 100% of the time,” Quartz, 26-Jun-2018. [Online]. Available: https://qz.com/1314749/us-border-agents-hacked-their-risk-assessment-system-to-recommend-immigrant-detention-every-time/. [Accessed: 14-Dec-2019].

[26]	J. Dastin, “Amazon scraps secret AI recruiting tool that showed bias against women,” Reuters, 10-Oct-2018.

[27]	C. Rudin, “Stop Explaining Black Box Machine Learning Models for High Stakes Decisions and Use Interpretable Models Instead,” arXiv [stat.ML], 26-Nov-2018.

[28]	Andrés Grases, “Bill Gates on AI at Stanford University Symposium on March18, 2019,” 20-Mar-2019. [Online]. Available: https://www.youtube.com/watch?v=qC9KvgkpEk8. [Accessed: 20-Dec-2019].

[29]	C. Clifford, “Elon Musk: ‘Mark my words — A.I. is far more dangerous than nukes,’” CNBC, 13-Mar-2018. [Online]. Available: https://www.cnbc.com/2018/03/13/elon-musk-at-sxsw-a-i-is-more-dangerous-than-nuclear-weapons.html. [Accessed: 20-Dec-2019].

[30]	D. Blair, “AK-47 Kalashnikov: The firearm which has killed more people than any other,” The Daily Telegraph, 02-Jul-2015.

[31]	M. Whittaker et al., AI now report 2018. AI Now Institute at New York University, 2018.

[32]	F.-F. Li, Fostering a Human-Centered Approach to Artificial Intelligence (SSIR). Inside Social Innovation Podcast, Stanford Social Innovation Review.

[33]	Z. Zhang et al., “Opening the black box of neural networks: methods for interpreting neural network models in clinical applications,” Ann Transl Med, vol. 6, no. 11, p. 216, Jun. 2018.

[34]	D. Castelvecchi, “Can we open the black box of AI?,” Nature, vol. 538, no. 7623, pp. 20–23, Oct. 2016.

[35]	“TensorFlow,” TensorFlow. [Online]. Available: https://www.tensorflow.org/. [Accessed: 19-Dec-2019].

[36]	“Facebook Open Source.” [Online]. Available: https://opensource.facebook.com/. [Accessed: 19-Dec-2019].

[37]	Ansgar Koene, Chris Clifton, Yohko Hatada, Helena Webb, Rashida Richardson, “A governance framework for algorithmic accountability and transparency,” European Parliament, Apr-2019. [Online]. Available: https://www.europarl.europa.eu/RegData/etudes/STUD/2019/624262/EPRS_STU(2019)624262_EN.pdf. [Accessed: 18-Dec-2019].

[38]	A. I. Hleg, “Ethics guidelines for trustworthy AI.” Retrieved from High-Level Expert Group on Artificial Intelligence(AI HLEG …, 2019.

[39]	G. Ferreira, “Software Certification in Practice: How Are Standards Being Applied?,” in 2017 IEEE/ACM 39th International Conference on Software Engineering Companion (ICSE-C), 2017, pp. 100–102.

[40]	P. Heck, M. Klabbers, and M. van Eekelen, “A software product certification model,” Software Quality Journal, vol. 18, no. 1, p. 37, Jun. 2009.

