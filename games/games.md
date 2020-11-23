---
layout: page
title: Games
permalink: /games/
---

{% include chart.html %}

## Games I've Played

**Experimental**

Luck vs Skill

<canvas id="chart" width="400" height="400"></canvas>
<script>
var ctx = document.getElementById('chart');
var myBubbleChart = new Chart(ctx, {
    type: 'bubble',
    data: 
    {
        datasets: 
        [{
            label: 'Super Smash Brothers Melee',
            data:
            [{
                x: 2.4,
                y: 1.2,
                r: 10
            }]
        },
        {
            label: 'Chess',
            data:
            [{
                x: 3.0,
                y: 0.3,
                r: 10
            }]
        },
        {
            label: 'Call of Duty',
            data:
            [{
                x: 1.5,
                y: 2.1,
                r: 10
            }]
        }],
        labels: ["Little Skill", "Some Skill", "Skill Based"]
    },
    options: {
        ...Chart.defaults.bubble,
        legend: {
            display: true,
            labels: {
                fontColor: 'rgb(255, 99, 132)'
            }
        },
        title: {
            display: true,
            text: 'Custom Chart Title'
        }
    }
});
</script>