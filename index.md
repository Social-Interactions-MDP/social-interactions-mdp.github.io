---
layout: index
title: 'Incorporating Rich Social Interactions Into MDPs'
subtitle: 'Much of what we do as humans is engage socially with other agents, a skill that robots must also eventually possess. We demonstrate that a rich theory of social interactions originating from microsociology and economics can be formalized by extending a nested MDP where agents reason about arbitrary functions of each others hidden rewards. This extended Social MDP allows us to encode the five basic interactions that underlie microsociology: cooperation, conflict, coercion, competition, and exchange. The result is a robotic agent capable of executing social interactions zero-shot in new environments; like humans it can engage socially in novel ways even without a single example of that social interaction. Moreover, the judgments of these Social MDPs align closely with those of humans when considering which social interaction is taking place in an environment. This method both sheds light on the nature of social interactions, by providing concrete mathematical definitions, and brings rich social interactions into a mathematical framework that has proven to be natural for robotics, MDPs.'

---

<table cellpadding="1">
    <tr>
        <td style="width:50%; text-align:center">
            <b>Level 1</b>
        </td>
        <td style="width:50%; text-align:center">
            <b>Level 2</b>
        </td>
    </tr>
    
    <tr>
        <td>
            <center><img src="/images/index/s11-l1.gif" ></center>
        </td>
        <td>
            <center><img src="/images/index/s11-l2.gif"></center>
        </td>
    </tr>
</table>
<b>Example:</b> Red robot is initialized with the physical goal of tree and social goal of exchange. Yellow robot is initialized with the physical goal of construction site and social goal of cooperation. Using S-MDP at different levels of reasoning, Yellow robot estimates the physical and social goal of the red robot at each time step.


## Contributions
* A novel Social MDP that allows robots to execute five fundamental social interactions from microsociology.
* The first formalization of what those interactions are.
* Computational implementation that enables robots to engage in social interactions zero-shot, without any social-interaction-specific training.
* Extensive human experiments that validate the model and demonstrate its ability to capture human judgments about social interactions.

## Scenarios
We apply our extended Social MDP framework to a multi-agent gridworld. This 10x10 world consists of two agents (a yellow robot and red robot), two physical landmarks (a construction site and a tree) and three objects (an axe, wooden log, and a water bucket). Objects can be pushed to either destination. Physical goals consist of moving the desired objects to one of the landmarks. Agents can have *no social goal* or one of the five social goals: *cooperation, conflict, competition, coercion, or exchange* - leading to 2x6x6 = 72 scenarios. At any point in time, agents can push an object forward, move in one of the four cardinal directions or choose to take no actions. Refer to the list of <a href="{{ item.url | relative_url }}/scenarios">all scenarios</a>.

#### Highlighted Scenarios

###### Scenario 11 ######
Red robot is initialized with the physical goal of tree and social goal of exchange. Yellow robot is initialized with the physical goal of construction site and social goal of cooperation. Using S-MDP at different levels of reasoning, Yellow robot estimates the physical and social goal of the red robot at each time step.

<table cellpadding="1">
    <tr>
        <td style="width:50%; text-align:center">
            Level 1
        </td>
        <td style="width:50%; text-align:center">
            Level 2
        </td>
    </tr>
    
    <tr>
        <td>
            <iframe width="857" height="482" src="https://www.youtube.com/embed/bmw3qBhe9FM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </td>
        <td>
            <iframe width="857" height="482" src="https://www.youtube.com/embed/TY0oP-kcW7c" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </td>
    </tr>
</table>  

---

###### Scenario 12 ######
Red robot is initialized with the physical goal of construction site and social goal of neutral. Yellow robot is initialized with the physical goal of Tree and social goal of cooperate. Using S-MDP at different levels of reasoning, Yellow robot estimates the physical and social goal of the red robot at each time step.

<table cellpadding="1">
    <tr>
        <td style="width:50%; text-align:center">
            Level 1
        </td>
        <td style="width:50%; text-align:center">
            Level 2
        </td>
    </tr>
    
    <tr>
        <td>
            <iframe width="857" height="482" src="https://www.youtube.com/embed/lGhqyo31pTI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </td>
        <td>
            <iframe width="857" height="482" src="https://www.youtube.com/embed/G24tUCnQwYs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </td>
    </tr>
</table>  

---

###### Scenario 25 ######
Red robot is initialized with the physical goal of tree and social goal of cooperate. Yellow robot is initialized with the physical goal of construction site and social goal of coercion. Using S-MDP at different levels of reasoning, Yellow robot estimates the physical and social goal of the red robot at each time step.

<table cellpadding="1">
    <tr>
        <td style="width:50%; text-align:center">
            Level 1
        </td>
        <td style="width:50%; text-align:center">
            Level 2
        </td>
    </tr>
    
    <tr>
        <td>
            <iframe width="857" height="482" src="https://www.youtube.com/embed/5MLA5jTWafA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </td>
        <td>
            <iframe width="857" height="482" src="https://www.youtube.com/embed/9ZqOn80avUQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </td>
    </tr>
</table>  

---

###### Scenario 35 ######
Red robot is initialized with the physical goal of construction site and social goal of exchange. Yellow robot is initialized with the physical goal of tree and social goal of exchange. Using S-MDP at different levels of reasoning, Yellow robot estimates the physical and social goal of the red robot at each time step.

<table cellpadding="1">
    <tr>
        <td style="width:50%; text-align:center">
            Level 1
        </td>
        <td style="width:50%; text-align:center">
            Level 2
        </td>
    </tr>
    
    <tr>
        <td>
            <iframe width="857" height="482" src="https://www.youtube.com/embed/sMTkHizQRjc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </td>
        <td>
            <iframe width="857" height="482" src="https://www.youtube.com/embed/UcElWwq3XFA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </td>
    </tr>
</table>  

---

###### Scenario 49 ######
Red robot is initialized with the physical goal of construction site and social goal of cooperate. Yellow robot is initialized with the physical goal of construction site and social goal of conflict. Using S-MDP at different levels of reasoning, Yellow robot estimates the physical and social goal of the red robot at each time step.

<table cellpadding="1">
    <tr>
        <td style="width:50%; text-align:center">
            Level 1
        </td>
        <td style="width:50%; text-align:center">
            Level 2
        </td>
    </tr>
    
    <tr>
        <td>
            <iframe width="857" height="482" src="https://www.youtube.com/embed/pPUnspVGXxM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </td>
        <td>
            <iframe width="857" height="482" src="https://www.youtube.com/embed/CdQ9I2z2IDU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </td>
    </tr>
</table>  

---

###### Scenario 52 ######
Red robot is initialized with the physical goal of tree and social goal of coercion. Yellow robot is initialized with the physical goal of tree and social goal of conflict. Using S-MDP at different levels of reasoning, Yellow robot estimates the physical and social goal of the red robot at each time step.

<table cellpadding="1">
    <tr>
        <td style="width:50%; text-align:center">
            Level 1
        </td>
        <td style="width:50%; text-align:center">
            Level 2
        </td>
    </tr>
    
    <tr>
        <td>
            <iframe width="857" height="482" src="https://www.youtube.com/embed/Q3WwP8wdu14" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </td>
        <td>
            <iframe width="857" height="482" src="https://www.youtube.com/embed/NTayxcWqxCU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </td>
    </tr>
</table>  

---

###### Scenario 63 ######
Red robot is initialized with the physical goal of tree and social goal of competition. Yellow robot is initialized with the physical goal of tree and social goal of coercion. Using S-MDP at different levels of reasoning, Yellow robot estimates the physical and social goal of the red robot at each time step.

<table cellpadding="1">
    <tr>
        <td style="width:50%; text-align:center">
            Level 1
        </td>
        <td style="width:50%; text-align:center">
            Level 2
        </td>
    </tr>
    
    <tr>
        <td>
            <iframe width="857" height="482" src="https://www.youtube.com/embed/xDG-sbhzdzw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </td>
        <td>
            <iframe width="857" height="482" src="https://www.youtube.com/embed/8VUD-SKQzCc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </td>
    </tr>
</table>  

---

## Results
<div class="gallery" data-columns="1">  
    <img src="/images/index/goal-weights.png">
</div>
<span style="font-size:medium;">Humans and our model scored 72 scenarios according to how likely each social interaction was and how likely one of the physical goals was. The straight line is the best linear fit and the light blue band represents the 95% confidence interval. Our model agrees with humans and predicts their confidence scores for both social interactions and the physical goal.</span> 
<p>Refer to the results of <a href="{{ item.url | relative_url }}/results">all experimenal scenarios</a>.</p>


### Paper
The paper is currently under review at the *39th IEEE Conference on Robotics and Automation (ICRA 2022)*. The latest version of the paper can be found <a href="{{ item.url | relative_url }}/paper">here</a>. 

### Code
Refer to the [Social-Interactions-MDP repository](https://github.com/Social-Interactions-MDP/social-interactions-mdp-framework) for the codebase.
