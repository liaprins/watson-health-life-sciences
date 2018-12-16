## Team members {#team}

<div class="overflowautodiv">

{% for profile in site.profiles %}

{% if page.team_members contains profile.name %}

<div class="profilegroup">
	<div class="personalitybg"></div>
	<p class="personalitytext">
		<a href="https://www.16personalities.com/{{ profile.personality_acronym | downcase }}-personality" target="_blank">Personality type: 
			<span class="personalityname">{{ profile.personality_word | downcase }}</span><br />
			<span class="acronym">{{ profile.personality_acronym }}</span>
		</a>
	</p>
	<img src="../../profiles/profile-images/{{ profile.image_file_name }}" class="profilepic" alt="{{ profile.name }} profile photo">
	<h4 class="name">{{ profile.name }}</h4>
	<p class="role">{{ profile.role }}</p>
	<img src="{{ page.css }}images/slacklogo.png" class="slacklogo" alt="Slack logo">
	<span class="slackhandle">@{{ profile.slack_handle_sans_at }}</span>
	<div class="email">
		<img src="{{ page.css }}images/emailicon.png" class="emailicon" alt="email icon">
		<span class="emailaddress">{{ profile.email }}</span>
	</div>
</div>

{% endif %}

{% endfor %}

</div>
