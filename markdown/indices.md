{% from "content-macros.jinja" import qtn, mcq, fitb, alert, jsscripts  %}
{{ jsscripts() }}

{% call alert(type="info") %}

**Learning Objectives:**

- Understanding indices
- Solving indices problems
{% endcall %}


Indices provide an easier way of expressing large numbers. An index is a power to a given base.

For example instead of writing $2 \times 2 \times 2$ we can write: $2^3$

Where:

- $2$ - base 
- $3$ - index or power


### Law 1:  $\quad a^m \times a^n = a^{m+n}$
---
When multiplying numbers in the same base the base is maintained and the powers are added.


#### Examples


{{ qtn("1. What is the capital of France", "Paris", "qn1") }}

{{ fitb("2. What is 2 + 2?", "4", "qn2") }}

{{ mcq(
  question="3. What is the capital of France?", 
  options=["Paris", "Berlin", "Madrid", "Rome"], 
  correct_answer="Paris", 
  hint="It's a city of art, fashion, and culture."|replace("'", "\\'"), 
  explanation="Paris is the capital of France and home to many cultural landmarks like the Eiffel Tower and the Louvre Museum.",
  id="mcq1_indices"
) }}

{{ mcq(
  question="4. What is $5 + 7$?", 
  options=["10", "11", "12", "13"], 
  correct_answer="12", 
  hint="Think about simple addition.", 
  explanation="5 + 7 equals 12 because it’s a basic arithmetic sum.",
  id="mcq2_indices"
) }}