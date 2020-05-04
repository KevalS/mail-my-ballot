{% extends "Base.md" %}

{% set guidance = 'the [Georgia Secretary of State](https://sos.ga.gov/admin/uploads/Absentee_Voting_Guide_20142.pdf)' %}

{% block body %}
- Phone: **{{phone}}**
- County: **{{county}}**
- Party: **{{party}}**
- Election: **{{election}}**

{% endblock %}