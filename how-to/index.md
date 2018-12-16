---
title: I need to know how to...
shortname: How to
css: "../"
---

<header markdown="1">

# [{{ page.title }}]()
	
</header>

<section>

<!-- market-member -->
	<details>
		<summary id="market-member">
			<span class="how-to-question">Add a new team member to a market page</span>
		</summary>
		<ol>
			{% include_relative how-to-includes/how-to-market-member.md %}		
		</ol>
</details>
	
<!-- project-member -->
	<details>
		<summary id="project-member">
			<span class="how-to-question">Add a new team member to a project page</span>
		</summary>
		<ol>
			{% include_relative how-to-includes/how-to-project-member.md %}		
		</ol>
	</details>

<!-- market-page -->
<!--
	<details>
		<summary id="market-page">
			<span class="how-to-question">Make a new market page</span>
		</summary>
		<ol>
			{% include_relative how-to-includes/how-to-market-page.md %}		
		</ol>
	</details>
-->

<!-- project-page -->
	<details>
		<summary id="project-page">
			<span class="how-to-question">Make a new project page</span>
		</summary>
		<ol>
			{% include_relative how-to-includes/how-to-project-page.md %}		
		</ol>
	</details>
	
<!-- project-section -->
	<details>
		<summary id="project-section">
			<span class="how-to-question">Add a section to a project page</span>
		</summary>
		<ol>
			{% include_relative how-to-includes/how-to-project-section.md %}		
		</ol>
	</details>

<!-- delete-project -->
	<details>
		<summary id="market-member">
			<span class="how-to-question">Delete a project page</span>
		</summary>
		<ol>
			{% include_relative how-to-includes/how-to-delete-project.md %}		
		</ol>
	</details>

<!-- style-page -->
	<details>
		<summary id="style-page">
			<span class="how-to-question">Style a page section</span>
		</summary>
		{% include_relative how-to-includes/how-to-style-section.md %}		
	</details>
	
</section>
