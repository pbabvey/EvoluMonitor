# EvoluMonitor

The convergence and divergence of existing products in the market are mainly a long-term processes. Looking back in the hisory, smart cellphones emerged almost 10 years after the academic breakthroughs in digital CMOS circuits. Research literatures, Patent records, and custormer reviews, and tweets are the main resources to monitor the evolution of products and predict the future of market. 

Any hardware or software product in the market can be defined as a set of funtionalities and features. Getting information about the new technological advancement on one hand, and customer interface on the other hand we can predict the possible trends in the market. I am applying recently developed text analysis methods to monitor the diffusion of features for the products in the market. The ultimate goal of my project is developing new methods  with predicting capability to study the evolution of new functionalities.

As a starting point, I focused on headphone reviews on the Amazon. I have extracted all the headphone reviews for a set of 15 renowned headphone brands (Sennheiser, Sony, Boss, AILIHEN, Panasonic, ...). Then, I extracted mainly discussed topics as features. I ended up with features like battery life, bass response, noise cancellation, sound isolation, earbuds, volume control, and bluetooth. Then I produced a table of brand-feature satisfaction. This table shows the extent of customer satisfaction on each specific feature for each brand. Moreover, I applied k-mean to cluster the reviews based on discussed features. In the next steps I am applying LDA (latend dirichlet allocation) for topic modeling. After, I will apply context-aware text analysis to learn the main resource of unsatisfaction for each of discussed features in the reviews. Then, I would apply the fully-automated analysis to some other products and may refine the process or add some more steps. This is all about the first phase of my project and I planned to finish this phase by the end of the March 2019.




