---
layout: default
pagination: 
  enabled: true
---



Hello! I am a Ph.D. candidate in Economics at [Boston University](https://www.bu.edu/econ/). My research interets are in industrial organization and household finance. 

I make use of micro-data and employ structural techniques to quantitatively study the welfare implications of policies in the financial markets. In my current research, I use novel models to study price dispersion and information asymmetry in the US mortgage market. 

I hold both [MSc](https://www.lse.ac.uk/study-at-lse/Graduate/Degree-programmes-2024/MSc-Econometrics-and-Mathematical-Economics) and [BSc in Econometrics and Mathematical Economics](https://www.lse.ac.uk/study-at-lse/Undergraduate/degree-programmes-2024/BSc-Econometrics-and-Mathematical-Economics) from [the London School of Economics and Political Science](https://www.lse.ac.uk/economics).

Email: hhzhang@bu.edu

[CV](https://drive.google.com/file/d/1iFrYfe3i19xgL40cqhVtipmHF_m-gVOK/view?usp=sharing) and [resume](https://drive.google.com/file/d/18WSmE6mB5wZansjW8Lk3hEbgReWxGD7U/view?usp=sharing) here.

A summary of my <b>research projects</b> can be found [here](./research.md).




<nav class="pagination" role="navigation">
	<p>
    {% if paginator.previous_page %}
			{% if paginator.page == 2 %}
			<a class="newer-posts" href="{{ site.baseurl }}{{ paginator.previous_page_path }}">
        <span class="fa-stack fa-lg">
          <i class="fa fa-square fa-stack-2x"></i>
          <i class="fa fa-angle-double-left fa-stack-1x fa-inverse"></i>
        </span>
      </a>
			{% else %}
			<a class="newer-posts" href="{{ site.baseurl }}{{ paginator.next_page_path }}">
				<span class="fa-stack fa-lg">
					<i class="fa fa-square fa-stack-2x"></i>
					<i class="fa fa-angle-double-left fa-stack-1x fa-inverse"></i>
				</span>
			</a>
			{% endif %}
		{% else %}
		<span class="fa-stack fa-lg">
      <i class="fa fa-square fa-stack-2x"></i>
      <i class="fa fa-angle-double-left fa-stack-1x fa-inverse"></i>
    </span>
		{% endif %}
		<span class="page-number">Page {{ paginator.page }} of {{ paginator.total_pages }}</span>
		{% if paginator.next_page %}
		<a class="newer-posts" href="{{ site.baseurl }}{{ paginator.next_page_path }}">
      <span class="fa-stack fa-lg">
        <i class="fa fa-square fa-stack-2x"></i>
        <i class="fa fa-angle-double-right fa-stack-1x fa-inverse"></i>
      </span>
    </a>
		{% else %}
		<span class="fa-stack fa-lg">
      <i class="fa fa-square fa-stack-2x"></i>
      <i class="fa fa-angle-double-right fa-stack-1x fa-inverse"></i>
    </span>
		{% endif %}
	</p>
</nav>
