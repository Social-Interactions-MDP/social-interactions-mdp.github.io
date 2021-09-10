---
layout: index
title: 'Social Interactions as Reward Functions in Social MDPs'
subtitle: 'Social Interactions in multi-agents have been explored as modeling the behavior of the other agent in cooperative(helping) or competitive(hindering) settings. However, humans exhibit broader social interactions which go beyond these two interactions including but not limited to coercion, exchange, cooperation, conflict, neutral, or competition. We demonstrate how these social interactions can be effectively incorporated into MDPs (Markov decision processes) as reward structures by reasoning recursively about the goals of other agents. In essence, in our method, we formulate these social interactions as mapping of reward functions of the agents based on their physical and social goals. Our formulation provides a mapping function of the other agents estimated reward structure and physical goals, enabling these social interactions at multiple levels of reasoning. We quantitatively establish the quality of the social inferences made by our model on different social interactions and compare it with the human judgements and the two baseline models. We report the results of the performance by measuring correlation against human judgements on 72 experimental scenarios varied across physical goals and social goals for the two agents. Each scenario has agents as having either the same physical goal or different physical goals and one of 6 different social goals (cooperate, conflict, coercion, exchange or neutral) (2*6*6=72 scenarios).'

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
            <img src="/images/index/s11-l1.gif"> 
        </td>
        <td>
            <img src="/images/index/s11-l2.gif">
        </td>
    </tr>
</table>
<b>Example:</b> Red robot is initialized with the physical goal of tree and social goal of exchange. Yellow robot is initialized with the physical goal of construction site and social goal of cooperation. Using S-MDP at different levels of reasoning, Yellow robot estimates the physical and social goal of the red robot at each time step.


## Contributions
* formulating Social MDPs where an agent's reward function estimated from a set of reward functions for each social interaction in a recursive estimation of another agent's reward and a physical goal,
* an implementation where that function is a linear transformation, which captures different social interactions such as cooperate, conflict, competition, coercion, exchange or neutral,
* demonstrating that the model performs zero-shot social reasoning in agreement with a human subjects experiment, and
* examples of the practical utility of recursive social reasoning

## Scenarios
We apply our MDP framework to a multi-agent grid world consisting of two agents, a yellow robot and red robot, two physical landmarks, 
a construction site and a tree, and three objects, an axe, wood and water. Axe and Wood are the objects that agents need to carry to construction site and water need to be carried to tree. Robots can have a physical goal of moving the desired objects to the landmark. The 72 different experiment scenarios are systematically created in this grid world for the two agents. Each scenario has agents as having either the same physical goal or different physical goals and one of 6 different social goals (cooperate, conflict, coercion, exchange or neutral) (2x6x6 = 72 scenarios). Refer to the list of <a href="{{ item.url | relative_url }}/scenarios">all scenarios</a>.   

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
<span style="font-size:medium;">Twelve human subjects, and our model, the Social MDP, watched and scored 144 videos at different snapshots. These videos consist of 72 scenarios where robots reason at either level 1 or level 2 (presented to the users in randomized order). Models and humans were asked to predict the social and physical goal of the agents and their confidence of the interaction at different time steps of the video. The straight black line represents the best linear fit to the data, and the light blue band around the line shows the uncertainty in the linear fit. The light blue band represents a 95% confidence interval.</span> 
<p>Refer to the <a href="{{ item.url | relative_url }}/results">results</a> for all experimenal scenarios.</p>


### Paper
The paper is currently under review. The latest version of the paper can be found <a href="{{ item.url | relative_url }}/paper">here</a>. 

### Code
Refer to the [Social-Interactions-MDP repository](https://github.com/Social-Interactions-MDP/social-interactions-mdp-framework) for the codebase.
