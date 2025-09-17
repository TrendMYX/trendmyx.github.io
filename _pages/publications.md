--- # layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Conference Papers

>- **Random Gradient Hyper-heuristics Can Learn to Escape Local Optima in Multimodal Optimisation** \[[link](https://dl.acm.org/doi/10.1145/3712256.3726406)\]<br>
  Yuxuan Ma, [Pietro S. Oliveto](https://peteroliveto.github.io/), [John Alasdair Warwicker](https://sop.ior.kit.edu/english/21_297.php)<br>
  *GECCO 2025 [Theory track](https://gecco-2025.sigevo.org/Accepted-Papers#&sort[wptrackerlist23-1]=0-1)*


## Manuscripts / In Submission

>- **On the Effectiveness of Random Gradient Hyper-heuristics for Multimodal Optimisation** \[[pdf](files/HHTwoRatesJournal.pdf)\]<br>
  Yuxuan Ma, [Pietro S. Oliveto](https://peteroliveto.github.io/), [John Alasdair Warwicker](https://sop.ior.kit.edu/english/21_297.php)<br>
  Extended version of the conference paper<br>
  Submitted to *Artificial Intelligence* journal
  
>- **Theoretical and Empirical Analysis of Lehmer Codes to Search Permutation Spaces with Evolutionary Algorithms**<br>
  Yuxuan Ma, [Valentino Santucci](https://valentinosantucci.github.io/), [Carsten Witt](https://www.imm.dtu.dk/~cawi/)<br>
  Under double-blind review at a major AI conference


<!-- {% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}


{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}



