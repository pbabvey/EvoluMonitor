# EvoluMonitor

The convergence and divergence of existing products in the market are mainly a long-term processes. Looking back in the hisory, smart cellphones emerged almost 10 years after the academic breakthroughs in digital CMOS circuits. Research literatures, Patent records, and custormer reviews, and tweets are the main resources to monitor the evolution of products and predict the future of market. 

Any hardware or software product in the market can be defined as a set of funtionalities and features. Getting information about the new technological advancement on one hand, and customer interface on the other hand we can predict the possible trends in the market. I am applying recently developed text analysis methods to monitor the diffusion of features for the products in the market. The ultimate goal of my project is developing new methods to predict the evolution of new functionalities.

As a starting point, I focused on headphone reviews on the Amazon. I have extracted all the headphone reviews for a set of 15 renowned headphone brands (Sennheiser, Sony, Boss, AILIHEN, Panasonic, ...). Then, I extracted mainly discussed topics as features. I ended up with features like battery life, bass response, noise cancellation, noise isolation, bluetooth. Then I produced a table of brand-feature satisfaction. This table shows the extent of customer satisfaction for each brand on each specific feature. Moreover, I applied k-mean as a clustering method to the reviews to limit the scope of analysis to find the reviews regarding each feature. The next steps are LDA (latend dirichlet allocation) to topic modeling for the reviews. At the next step, I will apply context-aware text analysis to get main problems using each feature. 




