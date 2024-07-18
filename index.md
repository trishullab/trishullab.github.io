{% include section.html %}

{% capture text %}

The Trishul lab at UT Austin, directed by Prof. Swarat Chaudhuri,
studies problems at the interface of automated reasoning, programming
languages, and machine learning. Through a combination of symbolic
knowledge representations, statistical learning, search, and automated
reasoning, we hope to build a new class of intelligent systems that
excel at reasoning-intensive tasks and are reliable, secure, and
transparent by construction.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}


{% capture text %}

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{% capture text %}

{%
  include button.html
  link="team"
  text="Our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}


