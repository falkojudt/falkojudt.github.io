---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


<ol>
    <li>Chen, S. S., B. W. Kerns, N. Guy, and 7 co-authors (incl. <strong>F. Judt,</strong>), 2016: Aircraft Observations of Dry Air, ITCZ, Convective Cloud Systems and Cold Pools in MJO During DYNAMO. <em>Bull. Amer. Meteor. Soc.,</em> <strong>97,</strong> 405–423, <a href="https://doi.org/10.1175/BAMS-D-13-00196.1">https://doi.org/10.1175/BAMS-D-13-00196.1</a>. <a href="https://falkojudt.github.io/files/Chen%20et%20al.%202016%20-%20Aircraft%20Observations%20of%20Dry%20Air%2C%20the%20ITCZ%2C%20Convective%20Cloud%20Systems%2C%20and%20Cold%20Pools%20in%20MJO%20during%20DYNAMO.pdf">[pdf]</a></li>
    <li><strong>Judt, F.,</strong> S. S. Chen, 2015: A New Aircraft Hurricane Wind Climatology and Applications in Assessing the Predictive Skill of Tropical Cyclone Intensity using High-Resolution Ensemble Forecasts. <em>Geophys. Res. Let.,</em> <strong>42,</strong> 6043–6050, <a href="https://doi.org/10.1002/2015GL064609">https://doi.org/10.1002/2015GL064609</a>. <a href="https://falkojudt.github.io/files/Judt%20and%20Chen%202015%20-%20A%20New%20Aircraft%20Hurricane%20Wind%20Climatology%20and%20Appli%20...%20f%20Tropical%20Cyclone%20Intensity%20Using%20High-Resolution%20Ensemble%20Forecasts.pdf">[pdf]</a></li>
    <li>Coelho E., P. Hogan, G. Jacobs, and 23 co-authors (incl. <strong>Judt, F.</strong>), 2015: Ocean Current Estimation Using a Multi-Model Ensemble Kalman Filter During the Grand Lagrangian Deployment Experiment (GLAD). <em>Ocean Model.,</em> <strong>87,</strong> 86–106, <a href="https://doi.org/10.1016/j.ocemod.2014.11.001">https://doi.org/10.1016/j.ocemod.2014.11.001</a>. <a href="https://falkojudt.github.io/files/Coelho%20et%20al.%202015%20-%20Ocean%20current%20estimation%20using%20a%20Multi-Model%20Ensemble%20Kalman%20Filter%20during%20the%20Grand%20Lagrangian%20Deployment%20experiment%20(GLAD).pdf">[pdf]</a></li>
    <li>Jacobs, G. A., B. Bartels, D. Bogucki, and 30 co-authors (incl. <strong>Judt, F.</strong>), 2014: Data Assimilation Considerations for Improved Ocean Predictability during the Gulf of Mexico Grand Lagrangian Deployment (GLAD). <em>Ocean Model.,</em> <strong>83,</strong> 98–117, <a href="https://doi.org/10.1016/j.ocemod.2014.09.003">https://doi.org/10.1016/j.ocemod.2014.09.003</a>. <a href="https://falkojudt.github.io/files/Jacobs%20et%20al.%202014%20-%20Data%20assimilation%20considerations%20for%20improved%20ocean%20...%20tability%20during%20the%20Gulf%20of%20Mexico%20Grand%20Lagrangian%20Deployment%20(GLAD).pdf">[pdf]</a></li>   
    <li><strong>Judt, F.,</strong> and S. S. Chen, 2014: An Explosive Convective Cloud System and its Environmental Con- ditions in MJO Initiation Observed during DYNAMO. <em>J. Geophys. Res. Atmos.,</em> <strong>119,</strong> 2781–2795, <a href="https://doi.org/10.1002/2013JD021048">https://doi.org/10.1002/2013JD021048</a>. <a href="https://falkojudt.github.io/files/Judt%20and%20Chen%202014%20-%20An%20explosive%20convective%20cloud%20system%20and%20its%20environmental%20conditions%20in%20MJO%20initiation%20observed%20during%20DYNAMO.pdf">[pdf]</a></li> 
    <li><strong>Judt, F.,</strong> and S. S. Chen, 2013: Reply to “Comments on ‘Convectively Generated Potential Vorticity in Rainbands and Formation of the Secondary Eyewall in Hurricane Rita of 2005’”. <em>J. Atmos. Sci.,</em> <strong>70,</strong> 989–992, <a href="https://doi.org/10.1175/JAS-D-12-0151.1">https://doi.org/10.1175/JAS-D-12-0151.1</a>. <a href="https://falkojudt.github.io/files/Judt%20and%20Chen%202013%20-%20Reply%20to%20“Comments%20on%20‘Convectively%20Generated%20Poten%20...%20ds%20and%20Formation%20of%20the%20Secondary%20Eyewall%20in%20Hurricane%20Rita%20of%202005'”.pdf">[pdf]</a></li>
    <li><strong>Judt, F.,</strong> and S. S. Chen, 2010: Convectively Generated Potential Vorticity in Rainbands and Formation of the Secondary Eyewall in Hurricane Rita of 2005. <em>J. Atmos. Sci.,</em> <strong>67</strong>, 3581–3599, <a href="https://doi.org/10.1175/2010JAS3471.1">https://doi.org/10.1175/2010JAS3471.1</a>. <a href="https://falkojudt.github.io/files/Judt%20and%20Chen%202010%20-%20Convectively%20Generated%20Potential%20Vorticity%20in%20Rainbands%20and%20Formation%20of%20the%20Secondary%20Eyewall%20in%20Hurricane%20Rita%20of%202005.pdf">[pdf]</a></li>
</ol>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
