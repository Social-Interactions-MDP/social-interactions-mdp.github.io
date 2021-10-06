---
layout: index
title: 'Incorporating Rich Social Interactions Into MDPs'
subtitle: 'As we aim to enable robots to engage socially with other agents much as we do as humans there is a need for a rich theory of social interactions. We formalize this by extending Social MDPs where agents reason about the arbitrary functions of each others hidden rewards with different levels of reasoning. The extended Social MDPs encode five basic social interactions: <i>cooperate, conflict, competition, coercion and exchange</i> and can produce actions that are close to human judgements.'
---

<img src="/images/index/levels-of-reasoning.gif" >

## Scenarios
We apply the extended Social MDP framework to a multi-agent gridworld which consists of two agents (a yellow robot and red robot), two physical landmarks (a construction site and a tree) and three objects (an axe, wooden log, and a water bucket). Physical goals consist of moving the desired objects to one of the landmarks. Agents can have *no social goal* or one of the five social goals: *cooperation, conflict, competition, coercion, or exchange* - leading to 2x6x6 = 72 scenarios. See <a href="{{ item.url | relative_url }}/scenarios">all scenarios</a> for the list of all experimental scenarios.

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
            <center>
                <img src="/images/index/s11-l1.gif" onmouseover="this.src='/images/index/s11-l1.gif';" onmouseout="this.src='/images/index/level-1.png';">
            </center>
        </td>
        <td>
            <center>
                <img src="/images/index/level-2.png" onmouseover="this.src='/images/index/output-x.gif';" onmouseout="this.src='/images/index/level-2.png';">
            </center>
        </td>
    </tr>
</table>
<span style="font-size:medium;"><b>Example Demonstration </b><br/><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Conflict** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**None** Physical:*Construction Site* <br/>Using extended Social MDP at different levels of reasoning, Yellow robot estimates the physical and social goal of the red robot, and takes optimal actions in order to reach its goal.</span>

## Results
<img src="/images/index/goal-weights.png" width="900">
<p><span style="font-size:medium;">Humans and our model scored 72 scenarios according to how likely each social interaction was and how likely one of the physical goals was. The straight line is the best linear fit and the light blue band represents the 95% confidence interval. Our model agrees with humans and predicts their confidence scores for both social interactions and the physical goal. See <a href="{{ item.url | relative_url }}/results">results for all scenarios</a>.</span></p>

### Paper
The paper is currently under review at the *39th IEEE Conference on Robotics and Automation (ICRA 2022)*. Refer to the <a href="{{ item.url | relative_url }}/paper">latest version of the paper</a>. 

### Code
Refer to the [Social-Interactions-MDP repository](https://github.com/Social-Interactions-MDP/social-interactions-mdp-framework) for the codebase.
