I'm finishing the book "The Son Also Rises" by Gregory Clark. It's a dicey book, but the proponderance of evidence the author presents is indisputable, and the conclusions are incredibly important for people focused on the long-term flourishing of families.

The author traces the persistence of elite surnames across hundreds of years, meticulously and in many contexts. Typical estimates of intergenerational correlation of status markers like education or wealth vary by country -- usually in the range of 0.25 to 0.7. Clark shows that the long-run persistence of elite surnames shows that these rates tell only part of the story. There is noise within each generation and within individual markers of status. However, the data support a long-run, latent "status" variable that evolves smoothly over time with much higher correlation -- in the range of 0.7 to 0.9. 

Basically, individuals can break the mold through their efforts, but they and their descendants are constantly tugged back toward that mold, which evolves only slowly over time. Is that mold made by nature or nurture? Clark argues that it's at least indistinguishable from being genetic.

Normally, these are fighting words...or "stop reading here" words. The Economist magazine's book review said *The Son Also Rises* “may not be a racist book, but it certainly traffics in genetic determinism.” Yikes.

But the author is chair emeritus of the UC Davis Economics Department, and he is mostly careful about *not* extending the argument toward tired, racialist, colonial-apologist applications. The book is dry and often hard to follow. Frustratingly, it is also convincing.

This blog post is an attempt to take the premise offered by *The Son Also Rises* seriously, and consider what it means for those who want to build flourishing families.

---

Clark's central argument is that intergenerational correlations are usefully summarized in just two equations, a very short mathematical model.

 >I'll bypass rehashing or defending the author's evidence. For that, read the book or see other summaries online. Instead, I'll write out his argument in the mathematical terms he uses and explore the implications in terms of that model.
 
 >Reading this next part might be tough if you haven't encountered it before, but the pattern is worth learning. These equations comprise about the most vanilla type of "latent variable model" in statistics. Latent means it's something we think exists but cannot neatly observe. The variables are explained below.)

The first equation expresses intergenerational transmission of latent "social status". 

$$S_{t+1} = \rho \cdot S_t + \epsilon$$

where:
- $S_{t+1}$ is the social status of the offspring in the next generation.
- $S_t$ is the social status of the parent in the current generation.
- $\rho$ (rho) is the coefficient measuring how much parents' status affects their children.
- $\epsilon$ (epsilon) represents the random term accounting for other factors influencing the offspring's social status that are not directly related to the parent's status.

The second equation links latent "social status" to observable factors like education, occupation, income, and wealth.

$$S_t = \alpha + \beta X_t + \nu$$

where:
- $S_t$ is the social status of the individual.
- $\alpha$ (alpha) is a constant term.
- $\beta$ (beta) is the coefficients measuring the impact of traits $X_t$ (like wealth or education) on the social status. Note these are vectors, representing multiple traits.
- $X_t$ is the values of the individual traits.
- $\nu$ (nu) represents the random term accounting for other factors influencing social status not captured by the individual traits.

---

To take a model like this seriously, you can't take it literally. The point is to succinctly express an idea that explains *most* of what's happening in the real world.

I'll discuss some of what the model argues, what that implies, and some ready extensions/complications that could be added.

Apart for arguing that this model is relevant, the book's biggest conclusion is that parents' social status $\rho$ is relatively constant across time and space and is in the ballpark of 0.8.

If $\rho=0.8$, that means 80% of the average person's outcomes in life are determined by their parents. The remaining 20% is "random" -- simply meaning it is not determined by the model and has the same average value as the whole society.

The author argues that policymakers cannot change $\rho$...but he implies there is one way. He explores "endogamy" in India -- or mating exclusively within one's own social class. First, he argues that Brahmins, an upper class group in India, mostly only marry other Brahmins. Next, he shows that the prestige of a Brahmin surname drifts at about the normal rate *within the Brahmin pecking order*, but that Brahmin surnames maintain their elite status much more than expected relative to the rest of Indian surnames. Within their group, $\rho \approx 0.8$, but relative to the rest of society $\rho \approx 0.95$.

Here, Clark is nodding to an obvious shortcoming of his model -- people have two parents and two lineages. In the first equation, $\rho S_t$ should conceptually be broken out into mothers' and fathers' contributions, $\rho_M M_t$ and $\rho_P P_t$ respectively. 

$$S_{t+1} = \rho_M M_t + \rho_P P_t + \epsilon$$

Realistically, Clark's surname data only allow estimates based on patrilinear (fathers') status, and the additional effect of mothers' status goes to the error term $\epsilon$. The more a typical mother's status varies from the father's, the more a fit of surname data to the model will overestimate the error term and underestimate the true $\rho$. 

To restate, Clark implies that endogamy allows us to more correctly estimate the model by better accounting for mothers' status. And when we do, we find that genetics determines even more of the outcome than found previously -- 90 or 95%.

Further extending this argument, half or more of long-term social mobility comes from mating choices. Assortatitive mating is a huge issue and the enemy of social mobility. 

---

Two distinct concepts are both being called "social mobility" in this book: Clark defines social mobility as how average status ($\rho$) varies across many generations. This is contrasted to to studies of how much children's income/education/status varies from their parents ($\nu$).

Both concepts matter. Even if Scandinavian countries cannot escape the universal value of $\rho$, they have succeeded in enlarging each person's ability to determine their success conditional on their background, $\nu$.

Policymakers can still make lemonade from lemons in Clark's world. If a poor-type person has a chance to become rich through their efforts, they'll work harder. (Same for the rich-types.) Policies like public education still benefit both individuals and society in Clark's model.

The difference is simply that policymakers should be modest in their expectations about how social policies can change relative pecking orders over time.

If we agree that everybody matters. If the children of poor-types are doomed to be poor-types, we should at least make them comfortable. Clark's assertion is that life is more predetermined than we think. So, his book calls for *more* redistributive policies toward the poor, with an understanding that these are permanent subsidies. 

---

Clark's work is repulsive on some level. Why? 

A viewpoint that human success is based on our environments ("nurture"), appeals to two ideological camps.
1. "I wish everybody could be equal, for its own sake."
2. "I want to maximize productivity. Ensuring everybody has an equal chance at getting rich, encourages everybody to work as hard as possible."

Whatever the motives, both sides support equality of opportunity if good parenting and hard work enable anybody to succeed.

If "nature" dominates, as Clark argues, not much changes for the equality-loving group. Clark presents that argument, showing how benevolent social planners only need to make a few adjustments.

Wisely omitted from *The Son Also Rises* is how a belief that "nature" dominates changes things for those who only value themself or their own group. They care about the greater society only insofar as it maximizes productivity. For them, genetic determinism leads quickly to bad things. Eugenics, genocide, immigration restrictions, and racism become smart strategies.

Thus, ideological resistance to genetic-determinism is about fear of our society's demons. We proclaim that "all men are created equal", but we don't trust ourselves to live up to that ideal. 

The project for any reader of *The Son Also Rises* who is convinced by Clark's arguments but values equality for its own sake is to (1) shut up about it and (2) prepare for the day when genetic determinism becomes a mainstream view, when our better angels will have to prevail.

---

As discussed above social baddies design horrible policies if "nature" dominates, but decent policies if "nurture" dominates. 

On the other hand social do-gooders would cope well with an understanding that "nature" dominates but have a history of destructive interventions when they think "nurture" dominates. 

During the European conquest of the Americas, US and Canadian "welfare" policies sanctioned stealing Native children from their parents to be acculturated by adoptive European parents.

Today, the child welfare system continues in that tradition by re-assigning children to different parents when birth parents are deemed not good enough. Unsurprisingly, that power is applied unevenly across race. 

If child removal is justified as "harsh today, but it will help the child later", genetic predeterminism waters down that logic. If the child's future is predetermined, removing them from loved parents is simply cruel, with no future payoff.

---

Critiques of the Evidence

The evidence is pretty thin in a lot of places. It's mostly focused on whether the elite can keep their status long term, rather than the whole distribution. And it disagrees with other evidence on the importance of genetics. Don't take this book as gospel. The better takeaway is the model, that we are rooted *to some extent* to a type, rather than the specific coefficients he reports.