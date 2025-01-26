{% from "content-macros.jinja" import qtn, mcq, fitb, alert, jsscripts  %}
{{ jsscripts() }}

{% call alert(type="info", title="") %}
  Understanding indices
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


{{ qtn("What is the capital of France", "Paris", "qn1") }}

{{ fitb("What is 2 + 2?", "4", "qn2") }}

{{ mcq(
  "What is the capital of France?", 
  ["Paris", "Berlin", "Madrid", "Rome"], 
  "Paris", 
  "It's a city of art, fashion, and culture.", 
  "Paris is the capital of France and home to many cultural landmarks like the Eiffel Tower and the Louvre Museum.",
  id="mcq1_indices"
) }}

{{ mcq(
  "What is $5 + 7$?", 
  ["10", "11", "12", "13"], 
  "12", 
  "Think about simple addition.", 
  "5 + 7 equals 12 because it’s a basic arithmetic sum.",
  id="mcq2_indices"
) }}