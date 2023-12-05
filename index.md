---
layout: default
---
I am a Ph.D. candidate in Economics at Boston University. My research field falls in empirical industrial organization and household finance. My current projects make use of micro-data and employ structural techniques to quantitatively study the industrial organization of the US mortgage market. I hold both a BSc and MSc in Econometrics and Mathematical Economics from the London School of Economics.


[CV](https://drive.google.com/file/d/1iFrYfe3i19xgL40cqhVtipmHF_m-gVOK/view?usp=sharing)


[Resume](https://drive.google.com/file/d/18WSmE6mB5wZansjW8Lk3hEbgReWxGD7U/view?usp=sharing)

Contact Information:  

Email: hhzhang@bu.edu


<b>Research Projects<b>

<p><em>Price Discrimination and Adverse Selection in the U.S. Mortgage Market</em></p>

<p><em> Cross-subsidies through Loan Guarantee: A Study of Shadow Bank Lending in the U.S. Mortgage Market</em></p>

<p><em>A Retrospective Analysis of U.S. Bank Mergers (with Tim Lee)</em></p>


 <!-- pagination -->
  {% if paginator.total_pages > 1 %}
  <div class="pagination">
    {% if paginator.previous_page %}
      <a href="{{ paginator.previous_page_path | prepend: site.baseurl | replace: '//', '/' }}">&laquo; Prev</a>
    {% else %}
      <span>&laquo; Prev</span>
    {% endif %}

    {% for page in (1..paginator.total_pages) %}
      {% if page == paginator.page %}
        <span class="webjeda">{{ page }}</span>
      {% elsif page == 1 %}
        <a href="{{ '/' | prepend: site.baseurl | replace: '//', '/' }}">{{ page }}</a>
      {% else %}
        <a href="{{ site.paginate_path | prepend: site.baseurl | replace: '//', '/' | replace: ':num', page }}">{{ page }}</a>
      {% endif %}
    {% endfor %}

    {% if paginator.next_page %}
      <a href="{{ paginator.next_page_path | prepend: site.baseurl | replace: '//', '/' }}">Next &raquo;</a>
    {% else %}
      <span>Next &raquo;</span>
    {% endif %}
  </div>
  {% endif %}
</div>


